# NicoVM 618 活动 VPS 评测

NicoVM 是古博群群友尼古拉斯搞的一个品牌，这个评测是他们将于 618 推出的活动 VPS，感谢商家提供的测试机。商家承诺，该机型可赠送一个端口的 Cloudflare Spectrum. 使用此机型的朋友记得及时备份数据，商家曾声明 “我们再次在此郑重承诺 绝对不把用户的数据当回事 随时搞丢 随时暂停服务 随时跑路 请自己备份好数据 谢谢”. 这个小鸡是美国伊利诺州的家宽，具体位置看下图，离芝加哥比较近。

![1](https://i.loli.net/2019/06/15/5d04886334c3728052.png)

除非另有说明，本评测均在 CentOS7 开启 BBR 的前提下进行

---

简单说下这个 Cloudflare Spectrum 是啥。我对这个 spectrum 的理解是，让 cloudflare 给你这个 IP 的非 80/443 端口也来个反代，可以防点攻击，还能降低延迟(30 ms+)

---

## 基础配置

### 硬件配置

| 配置项       | 详情                                     |
|--------------|------------------------------------------|
| CPU 型号     | Intel Xeon E3-12xx v2 (Ivy Bridge, IBRS) |
| CPU 核心数   | 1                                        |
| CPU 主频     | 3192.746 MHz                             |
| 总硬盘大小   | 49.0 GB (2.0 GB Used)                    |
| 总内存大小   | 485 MB (81 MB Used)                      |
| 总 Swap 大小 | 1023 MB (1 MB Used)                      |
| 虚拟化技术   | KVM                                      |

### IO

| 序数    | IO 值     |
|---------|-----------|
| 1       | 66.5 MB/s |
| 2       | 53.0 MB/s |
| 3       | 56.0 MB/s |
| 平均 IO | 58.5 MB/s |

### Unixbench

``` BASH
========================================================================
   BYTE UNIX Benchmarks (Version 5.1.3)

   System: s-27-227.flex.volo.net: GNU/Linux
   OS: GNU/Linux -- 4.9.177-35.el7.x86_64 -- #1 SMP Tue May 21 11:43:40 UTC 2019
   Machine: x86_64 (x86_64)
   Language: en_US.utf8 (charmap="UTF-8", collate="UTF-8")
   CPU 0: Intel Xeon E3-12xx v2 (Ivy Bridge, IBRS) (6385.5 bogomips)
          x86-64, MMX, Physical Address Ext, SYSENTER/SYSEXIT, SYSCALL/SYSRET, Intel virtualization
   22:26:50 up 12:39,  1 user,  load average: 1.05, 0.36, 0.13; runlevel 3

------------------------------------------------------------------------
Benchmark Run: Fri Jun 14 2019 22:26:50 - 22:55:03
1 CPU in system; running 1 parallel copy of tests

Dhrystone 2 using register variables       37675712.7 lps   (10.0 s, 7 samples)
Double-Precision Whetstone                     4484.9 MWIPS (10.5 s, 7 samples)
Execl Throughput                               4070.7 lps   (30.0 s, 2 samples)
File Copy 1024 bufsize 2000 maxblocks        619476.4 KBps  (30.0 s, 2 samples)
File Copy 256 bufsize 500 maxblocks          166236.0 KBps  (30.0 s, 2 samples)
File Copy 4096 bufsize 8000 maxblocks       1974734.7 KBps  (30.0 s, 2 samples)
Pipe Throughput                              884773.9 lps   (10.0 s, 7 samples)
Pipe-based Context Switching                 160373.8 lps   (10.0 s, 7 samples)
Process Creation                               9645.5 lps   (30.0 s, 2 samples)
Shell Scripts (1 concurrent)                   4610.9 lpm   (60.0 s, 2 samples)
Shell Scripts (8 concurrent)                    568.4 lpm   (60.1 s, 2 samples)
System Call Overhead                         774863.8 lps   (10.0 s, 7 samples)

System Benchmarks Index Values               BASELINE       RESULT    INDEX
Dhrystone 2 using register variables         116700.0   37675712.7   3228.4
Double-Precision Whetstone                       55.0       4484.9    815.4
Execl Throughput                                 43.0       4070.7    946.7
File Copy 1024 bufsize 2000 maxblocks          3960.0     619476.4   1564.3
File Copy 256 bufsize 500 maxblocks            1655.0     166236.0   1004.4
File Copy 4096 bufsize 8000 maxblocks          5800.0    1974734.7   3404.7
Pipe Throughput                               12440.0     884773.9    711.2
Pipe-based Context Switching                   4000.0     160373.8    400.9
Process Creation                                126.0       9645.5    765.5
Shell Scripts (1 concurrent)                     42.4       4610.9   1087.5
Shell Scripts (8 concurrent)                      6.0        568.4    947.3
System Call Overhead                          15000.0     774863.8    516.6
                                                                   ========
System Benchmarks Index Score                                        1037.1



======= Script description and score comparison completed! ======= 
```

好高的结果，可能是主频较高，负载低的缘故。

---

## 网络

### IP 归属地

![Snipaste_2019-06-15_14-07-27.png](https://i.loli.net/2019/06/15/5d048b2c9f6ab38559.png)

美国原生 IP

### 三网路由

| 运营商   | 去程 | 回程 |
|----------|------|------|
| 中国电信 | he   | he   |
| 中国联通 | he   | he   |
| 中国移动 | he   | he   |

---

### 海外 wget

| 节点名称                 | 下载速度 |
|--------------------------|----------|
| CacheFly                 | 90.6MB/s |
| Linode, Tokyo, JP        | 8.16MB/s |
| Linode, Singapore, SG    | 7.64MB/s |
| Linode, London, UK       | 4.26MB/s |
| Linode, Frankfurt, DE    | 13.6MB/s |
| Linode, Fremont, CA      | 21.7MB/s |
| Softlayer, Dallas, TX    | 14.8MB/s |
| Softlayer, Seattle, WA   | 2.66MB/s |
| Softlayer, Frankfurt, DE | 1.85MB/s |
| Softlayer, Singapore, SG | 1.50MB/s |
| Softlayer, HongKong, CN  | 2.41MB/s |

美国本土的速度都还算不错

---

### 回程路由详情

#### 泉州移动

| 跳数 | IP                                                                        | 延迟      | AS      | 备注                                             |
|------|---------------------------------------------------------------------------|-----------|---------|--------------------------------------------------|
| 1    | s-x-x.flex.volo.net (x.x.x.x)                                             | 1.16 ms   | AS33097 | United States Illinois Champaign volo.net        |
| 2    | v1104.core1.chi1.he.net (184.105.24.41)                                   | 4.56 ms   | AS6939  | United States Illinois Chicago he.net            |
| 3    | 100ge2-2.core2.chi1.he.net (184.104.192.118)                              | 3.64 ms   | AS6939  | United States Illinois Chicago he.net            |
| 4    | 100ge2-2.core1.mci3.he.net (184.105.81.209)                               | 16.42 ms  | AS6939  | United States Missouri Kansas City he.net        |
| 5    | 100ge10-2.core1.dal1.he.net (184.105.81.206)                              | 33.65 ms  | AS6939  | United States Texas Dallas he.net                |
| 6    | 100ge4-2.core1.phx2.he.net (184.105.81.173)                               | 52.52 ms  | AS6939  | United States Arizona Phoenix he.net             |
| 7    | 100ge11-2.core1.lax2.he.net (184.105.81.177)                              | 54.64 ms  | AS6939  | United States California Los Angeles he.net      |
| 8    | cmi-int-hk-as58453.10gigabitethernet3-1.core1.lax2.he.net (216.218.134.6) | 57.72 ms  | AS6939  | United States California Los Angeles he.net      |
| 9    | 223.120.6.17                                                              | 57.48 ms  | AS58453 | United States California Los Angeles ChinaMobile |
| 10   | 223.120.6.38                                                              | 57.60 ms  | AS58453 | United States California Los Angeles ChinaMobile |
| 11   | 223.120.12.18                                                             | 274.22 ms | AS58453 | China Shanghai ChinaMobile                       |
| 12   | 221.183.55.46                                                             | 226.33 ms | AS9808  | China Shanghai ChinaMobile                       |
| 13   | *                                                                         |           |         |                                                  |
| 14   | 221.176.19.221                                                            | 264.85 ms | AS9808  | China Jiangsu Nanjing ChinaMobile                |
| 15   | 221.183.11.238                                                            | 246.03 ms | AS9808  | China Jiangsu Nanjing ChinaMobile                |
| 16   | *                                                                         |           |         |                                                  |
| 17   | 54.20.207.183.static.js.chinamobile.com (183.207.20.54)                   | 264.07 ms | AS56046 | China Jiangsu Suqian ChinaMobile                 |
| 18   | *                                                                         |           |         |                                                  |
| 19   | 112.3.27.1                                                                | 262.42 ms | AS56046 | China Jiangsu Suqian ChinaMobile                 |

#### 天津联通

| 跳数 | IP                                                                              | 延迟      | AS      | 备注                                        |
|------|---------------------------------------------------------------------------------|-----------|---------|---------------------------------------------|
| 1    | s-x-x.flex.volo.net (x.x.x.x)                                                   | 1.14 ms   | AS33097 | United States Illinois Champaign volo.net   |
| 2    | v1104.core1.chi1.he.net (184.105.24.41)                                         | 3.86 ms   | AS6939  | United States Illinois Chicago he.net       |
| 3    | 100ge2-2.core2.chi1.he.net (184.104.192.118)                                    | 9.19 ms   | AS6939  | United States Illinois Chicago he.net       |
| 4    | 100ge8-2.core1.mci3.he.net (184.105.222.77)                                     | 16.34 ms  | AS6939  | United States Missouri Kansas City he.net   |
| 5    | 100ge10-2.core1.dal1.he.net (184.105.81.206)                                    | 33.71 ms  | AS6939  | United States Texas Dallas he.net           |
| 6    | 100ge4-2.core1.phx2.he.net (184.105.81.173)                                     | 52.81 ms  | AS6939  | United States Arizona Phoenix he.net        |
| 7    | 100ge11-2.core1.lax2.he.net (184.105.81.177)                                    | 54.69 ms  | AS6939  | United States California Los Angeles he.net |
| 8    | china169-backbone-as4837.100gigabitethernet12-2.core1.lax2.he.net (72.52.93.38) | 216.60 ms | AS6939  | United States California Los Angeles he.net |
| 9    | 219.158.96.233                                                                  | 220.68 ms | AS4837  | China Guangdong Guangzhou ChinaUnicom       |
| 10   | 219.158.97.26                                                                   | 217.18 ms | AS4837  | China Guangdong Guangzhou ChinaUnicom       |
| 11   | 219.158.24.125                                                                  | 218.29 ms | AS4837  | China Guangdong Guangzhou ChinaUnicom       |
| 12   | 219.158.114.202                                                                 | 227.20 ms | AS4837  | China ChinaUnicom                           |
| 13   | *                                                                               |           |         |                                             |
| 14   | dns82.online.tj.cn (117.8.160.82)                                               | 218.29 ms | AS4837  | China Tianjin ChinaUnicom                   |
| 15   | dns14.online.tj.cn (117.8.226.14)                                               | 234.06 ms | AS4837  | China Tianjin ChinaUnicom                   |
| 16   | 103.24.228.1                                                                    | 248.30 ms | AS4837  | China Tianjin cnkuai.cn ChinaUnicom         |

#### 德州电信

| 跳数 | IP                                                                               | 延迟      | AS      | 备注                                              |
|------|----------------------------------------------------------------------------------|-----------|---------|---------------------------------------------------|
| 1    | s-x-x.flex.volo.net (x.x.x.x)                                           | 0.79 ms   | AS33097 | United States Illinois Champaign volo.net         |
| 2    | v1104.core1.chi1.he.net (184.105.24.41)                                          | 4.14 ms   | AS6939  | United States Illinois Chicago he.net             |
| 3    | 100ge2-2.core2.chi1.he.net (184.104.192.118)                                     | 3.94 ms   | AS6939  | United States Illinois Chicago he.net             |
| 4    | 100ge8-1.core1.nyc4.he.net (184.104.193.37)                                      | 25.46 ms  | AS6939  | United States New York New York City he.net       |
| 5    | 100ge11-1.core1.nyc5.he.net (184.105.213.218)                                    | 23.13 ms  | AS6939  | United States New Jersey Secaucus he.net          |
| 6    | chinanet-backbone-as4134.10gigabitethernet7-4.core1.nyc5.he.net (209.51.191.138) | 31.10 ms  | AS6939  | United States New Jersey Secaucus he.net          |
| 7    | 202.97.97.178                                                                    | 71.71 ms  | AS4134  | United States California Los Angeles ChinaTelecom |
| 8    | 202.97.49.141                                                                    | 210.12 ms | AS4134  | China Shanghai ChinaTelecom                       |
| 9    | 202.97.91.45                                                                     | 229.86 ms | AS4134  | China Shanghai ChinaTelecom                       |
| 10   | 202.97.61.85                                                                     | 278.36 ms | AS4134  | China Shanghai ChinaTelecom                       |
| 11   | *                                                                                |           |         |                                                   |
| 12   | 60.235.112.18                                                                    | 303.13 ms | AS4134  | China Shandong Dezhou ChinaTelecom                |
| 13   | x.xx.x.x                                                                     | 306.83 ms | AS4134  | China Shandong Dezhou ChinaTelecom                |

---

### 上手

#### SpeedTest

山东电信 100M 直连. 15:38

![speedtest](https://www.speedtest.net/result/8338881152.png)

山东电信 100M 使用联通中转. 20:38
![speedtest](https://www.speedtest.net/result/8339408211.png)

山东电信 100M 使用 Cloudflare Spectrum. 10:43
![speedtest](https://www.speedtest.net/result/8340776698.png)

山东电信 100M 使用 Cloudflare Spectrum. 20:46
![speedtest](https://www.speedtest.net/result/8341607374.png)

---

#### Fast

山东电信 100M 直连. 21:07
![Snipaste_2019-06-15_21-08-52.png](https://i.loli.net/2019/06/15/5d04edf13177c79807.png)

山东电信 100M 使用联通中转. 21:04
![fast](https://i.loli.net/2019/06/15/5d04ecdfcb70e44725.png)

山东电信 100M 使用 Cloudflare Spectrum. 10:46
![fast](https://t.halu.lu/t/275)

山东电信 100M 使用 Cloudflare Spectrum. 20:46
![fast](https://t.halu.lu/t/276)

---

## 流媒体

### Netflix

![nf](https://t.halu.lu/t/274)

可以看 Netflix

---

## 最后

该机型联通直连的速度还可以，但是电信的话，还是放弃直连的梦想吧。对速度要求不是很高的话，可以拿商家送的 cloudflare spectrum 来加速梯子，50M 的速度，看看 4K 流媒体没啥压力。土豪们拿来当落地或许也是不错的选择，毕竟美国的家宽，流媒体啥的都是能看的。

![flag](https://t.halu.lu/t/277)
