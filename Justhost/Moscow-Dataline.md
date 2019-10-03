这次带来的是 justhost 莫斯科 dataline 机房的评测。该机型的 offer 贴在 [这里](https://zhuji.lu/topic/573)

# 基础配置

## 硬件信息

配置 | 详情
---|---
CPU 型号| Intel(R) Xeon(R) CPU E5-2680 v2 @ 2.80GHz
核心数 | 1
CPU 频率 | 2799.998 MHz
硬盘大小 | 5.3 GB (2.6 GB Used)
总内存大小 | 485 MB (94 MB Used)
总 Swap 大小 | 0 MB (0 MB Used)
虚拟化 | KVM
测试 IP |  `45.147.200.53`

---

## 内存性能

测试内容 | 结果
---|---
 1 线程测试-顺序读|    4335.63K ops (4037.87 MB/s)
 1 线程测试-顺序写|     4349.38K ops (4050.68 MB/s)
 1 线程测试-随机读|     1033.33K ops (962.37 MB/s)
 1 线程测试-随机写|     1150.72K ops (1071.69 MB/s)

内存的性能过关

---

## IO 测试

测试项 | 写入速度 | 读取速度
---|---|---
10MB-4K块          |    13.5 MB/s (3293 IOPS, 0.78 秒)      |    27.7 MB/s (6761 IOPS, 0.38 秒)
 10MB-1M块        |      51.0 MB/s (48 IOPS, 0.21 秒)       |     38.5 MB/s (36 IOPS, 0.27 秒)
 100MB-4K块       |      22.4 MB/s (5469 IOPS, 4.68 秒)     |     26.3 MB/s (6426 IOPS, 3.98 秒)
 100MB-1M块        |     32.7 MB/s (31 IOPS, 3.21 秒)       |     32.3 MB/s (30 IOPS, 3.25 秒)
 1000MB-4K块       |     10.4 MB/s (2546 IOPS, 100.54 秒)   |             23.1 MB/s (5640 IOPS, 45.39 秒)
 1000MB-1M块       |     31.6 MB/s (30 IOPS, 33.22 秒)      |     31.5 MB/s (30 IOPS, 33.32 秒)

他家 IO 一直这样，屌慢。HDD 水平。

---

## UnixBench

测试项 | 标准 | 结果 | 指数
---|---|---|---|
Dhrystone 2 using register variables    |     116700.0|   28519996.5   |2443.9
Double-Precision Whetstone               |        55.0 |      4155.3    |755.5
Execl Throughput                         |        43.0  |     2721.9    |633.0
File Copy 1024 bufsize 2000 maxblocks     |     3960.0   |  353780.7    |893.4
File Copy 256 bufsize 500 maxblocks        |    1655.0|      95298.1   | 575.8
File Copy 4096 bufsize 8000 maxblocks       |   5800.0 |   1005621.9  | 1733.8
Pipe Throughput                      |         12440.0  |    676739.8|    544.0
Pipe-based Context Switching          |         4000.0    |  76902.5    |192.3
Process Creation                       |         126.0     |  5720.5   | 454.0
Shell Scripts (1 concurrent)            |         42.4      | 3305.2  |  779.5
Shell Scripts (8 concurrent)             |         6.0 |       449.6 |   749.3
System Call Overhead                      |    15000.0  |   581099.8|    387.4
System Benchmarks Index Score        ||                                 687.8

---

# 网络

## IP 归属地

![image.png](https://i.loli.net/2019/10/03/DRuWxMgSUc3Jm5Y.png)
俄罗斯原生 IP

---

## 海外速度

测速节点 | 下载速度
---|---
CacheFly                       |         15.0MB/s
Linode, Tokyo2, JP            |         2.74MB/s
Linode, Singapore, SG           |           1.99MB/s
Linode, London, UK             |       15.5MB/s
Linode, Frankfurt, DE         |        9.62MB/s
Linode, Fremont, CA            |           2.54MB/s
Softlayer, Dallas, TX          |         7.62MB/s
Softlayer, Seattle, WA         |         7.68MB/s
Softlayer, Frankfurt, DE       |           11.4MB/s
Softlayer, Singapore, SG        |        3.74MB/s
Softlayer, HongKong, CN        |         6.16MB/s

带宽算达标吧，欧洲的速度挺好，美国也还算不错

---

## 三网路由

注：因为不知道啥原因，无法以 TCP 模式测试路由，故下方结果均为 icmp 路由

运营商 | 去程 | 回程
---|---|---
中国电信 | ttk   | CN2 GT
中国联通 | ttk   | CN2
中国移动 | telia | CN2

电信联通去程走 ttk 伯立，移动走 telia 欧洲，三网都不绕美。回程也都是 CN2.

---

## 回程路由详情(均为 icmp)

### 天津联通

跳数| IP | 延迟 | ASN | 备注
---|---|---|---|---
 1|45.147.200.1|8.26 ms|AS51659|Russian Federation Moscow justhost.ru
 2|*
 3|*
 4|*
 5|59.43.246.17|231.72 ms|AS4809|China Beijing ChinaTelecom
 6|*
 7|202.97.12.57|115.80 ms|AS4134|China Beijing ChinaTelecom
 8|202.97.34.157|117.86 ms|AS4134|China Beijing ChinaTelecom
 9|*
10|*
11|219.158.4.157|113.47 ms|AS4837|China Beijing ChinaUnicom
12|*
13|*
14|dns106.online.tj.cn (117.8.156.106)|114.97 ms|AS4837|China Tianjin ChinaUnicom

### 北京电信

跳数| IP | 延迟 | ASN | 备注
---|---|---|---|---
 1|45.147.200.1|5.47 ms|AS51659|Russian Federation Moscow justhost.ru
 2|*
 3|*
 4|*
 5|59.43.246.17|231.65 ms|AS4809|China Beijing ChinaTelecom
 6|*
 7|202.97.81.141|120.00 ms|AS4134|China Beijing ChinaTelecom
 8|202.97.53.17|131.02 ms|AS4134|China Beijing ChinaTelecom
 9|42.99.32.6|130.43 ms|AS4134|China Beijing ChinaTelecom
10|*
11|113.59.224.1|736.23 ms|AS4134|China Beijing ChinaTelecom

### 合肥移动

跳数| IP | 延迟 | ASN | 备注
---|---|---|---|---
 1|45.147.200.1|2.49 ms|AS51659|Russian Federation Moscow justhost.ru
 2|*
 3|*
 4|*
 5|59.43.246.17|231.79 ms|AS4809|China Beijing ChinaTelecom
 6|59.43.247.126|240.14 ms|AS4809|China Shanghai ChinaTelecom
 7|*
 8|202.97.33.189|160.03 ms|AS4134|China Shanghai ChinaTelecom
 9|202.97.50.177|193.07 ms|AS4134|China Shanghai ChinaTelecom
10|*
11|*
12|221.183.21.169|187.61 ms|AS9808|China Jiangsu Nanjing ChinaMobile
13|221.176.22.45|197.72 ms|AS9808|China Jiangsu Wuxi ChinaMobile
14|221.176.18.33|209.04 ms|AS9808|China Anhui Hefei ChinaMobile
15|221.183.19.138|209.58 ms|AS9808|China Anhui Hefei ChinaMobile
16|112.29.129.14|210.51 ms|AS9808|China Anhui Hefei ChinaMobile
17|*
18|112.29.129.146|214.94 ms|AS9808|China Anhui Hefei ChinaMobile
19|120.210.192.130|216.41 ms|AS9808|China Anhui Hefei ChinaMobile
20|120.210.204.1|285.08 ms|AS9808|China Anhui Hefei ChinaMobile

---

## MTR

### 山东电信，家宽

10:27
![image.png](https://i.loli.net/2019/10/03/1ygdPqEuK4F8aMV.png)

---

## 实测

### 电信 100M 家宽

20:27

![image](https://www.speedtest.net/result/8644249713.png)
![image.png](https://i.loli.net/2019/10/03/7mICehnMUZuAslQ.png)

---

### 上海联通

speedtest cli 数据

20:36
![image](http://www.speedtest.net/result/8644270787.png)

---

### 北京移动

speedtest cli 数据

20:38
![image](http://www.speedtest.net/result/8644276711.png)

---

告辞

# 总结

1.8$ 的价格，在很多小鸡里面确实是算便宜的。但是不可避免的，超售是存在的，别对性能有太多指望。根据测试结果来看，欧洲的带宽还算可以，能到 150Mbps，勉强算他达标吧。但是实际代理用起来（晚高峰期间），速度不算好看，YouTube 勉强看个 720p。据群友称能看 Netflix，但是我账号到期了，没法测了。