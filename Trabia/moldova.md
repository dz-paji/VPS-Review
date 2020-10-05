LemonBench Linux System Benchmark Utility Version 20190917 BetaVersion *Unstable* 
 
 测试开始时间：	2019-10-05 13:27:57
 测试结束时间：	2019-10-05 14:07:32
 测试模式：	全面测试
 
 -> 系统信息
 
 系统名称:		CentOS Linux 7.7.1908 (x86_64)
 CPU型号:		QEMU Virtual CPU version (cpu64-rhel6)
 CPU缓存大小:		4096 KB
 CPU数量:		1 vCPU
 虚拟化类型:		KVM
 内存使用率:		114.08 MB / 991.08 MB
 Swap使用率:		0 KB / 1024.00 MB
 磁盘使用率:		1.68 GB / 24.74 GB
 引导设备:		/dev/vda1
 系统负载(1/5/15min):	0.01 0.46 0.60 

 -> 网络信息

 IPV4 - 本机IP:		178.17.*.*
 IPV4 - ASN信息:	AS43289 (摩尔多瓦 基希讷乌 )
 IPV4 - 运营商:		trabia.com
 IPV6 - 本机IP:		[MD] 2a00:1dc0:caff:30::b379
 IPV6 - ASN信息:	AS43289 (I.C.S. Trabia-Network S.R.L.)
 IPV6 - 归属地:		Republic of Moldova, null

 -> 流媒体解锁测试

 HBO Now:		测试失败 (解析失败)
 巴哈姆特動畫瘋:	否
 哔哩哔哩-港澳台限定:	否
 哔哩哔哩-台湾限定:	否

 -> CPU性能测试 (标准模式, 3-Pass @ 30sec)

 1 线程测试:	1232 分

 -> 内存性能测试 (标准模式, 3-Pass @ 30sec)

 1 线程测试-顺序读:	366.53K ops (341.36 MB/s)
 1 线程测试-顺序写:	367.95K ops (342.68 MB/s)
 1 线程测试-随机读:	311.70K ops (290.29 MB/s)
 1 线程测试-随机写:	308.26K ops (287.09 MB/s)

 -> 磁盘性能测试 (4K块/1M块, Direct写入)

 测试项目		写入速度				读取速度
 10MB-4K块		1.3 MB/s (323 IOPS, 7.92 秒)		67.5 MB/s (16485 IOPS, 0.16 秒)
 10MB-1M块		15.2 MB/s (14 IOPS, 0.69 秒)		4.0 GB/s (3789 IOPS, 0.00 秒)
 100MB-4K块		1.1 MB/s (274 IOPS, 93.13 秒)		71.9 MB/s (17544 IOPS, 1.46 秒)
 100MB-1M块		31.1 MB/s (29 IOPS, 3.37 秒)		4.0 GB/s (3776 IOPS, 0.03 秒)
 1000MB-4K块		1.1 MB/s (270 IOPS, 945.55 秒)		69.9 MB/s (17066 IOPS, 15.00 秒)
 1000MB-1M块		50.2 MB/s (47 IOPS, 20.87 秒)		861 MB/s (821 IOPS, 1.22 秒)

-> Speedtest.net 网速测试

 节点名称		上传速度	下载速度	Ping延迟
 距离最近测速点		14.67 MB/s	13.54 MB/s	1.294 ms
 东北-吉林联通		2.50 MB/s	3.30 MB/s	865.216 ms
 东北-沈阳移动		0.04 MB/s	0.11 MB/s	786.676 ms
 华北-山东联通		 MB/s	 MB/s	No ms
 华中-南京联通		2.32 MB/s	3.20 MB/s	366.936 ms
 华中-杭州电信		0.68 MB/s	0.26 MB/s	329.971 ms
 华中-杭州移动		 MB/s	 MB/s	No ms
 华东-上海联通		2.61 MB/s	1.96 MB/s	307.748 ms
 华东-上海移动		0.39 MB/s	2.96 MB/s	707.928 ms
 华南-广州电信		 MB/s	 MB/s	No ms
 西南-重庆联通		 MB/s	 MB/s	No ms
 西南-南宁移动		0.35 MB/s	3.84 MB/s	390.681 ms
 西北-兰州联通		2.17 MB/s	0.44 MB/s	422.745 ms
 西北-兰州电信		0.04 MB/s	0.07 MB/s	589.195 ms
 西北-兰州移动		0.58 MB/s	1.96 MB/s	652.369 ms

 -> 路由追踪测试 (IPV4)


路由追踪到 北京联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 123.125.99.1 (123.125.99.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.32 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.29 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  9.31 ms  AS8928  罗马尼亚 interoute.com
 4  89.149.186.181  34.07 ms  AS3257,AS8928  德国 黑森州 法兰克福 gtt.net
 5  *
 6  219.158.98.5  263.55 ms  AS4837  中国 北京 联通
 7  219.158.16.77  242.82 ms  AS4837  中国 北京 联通
 8  219.158.4.169  275.87 ms  AS4837  中国 北京 联通
 9  202.96.12.82  254.41 ms  AS4808  中国 北京 联通
10  61.51.169.178  275.07 ms  AS4808  中国 北京 联通
11  124.65.194.138  258.44 ms  AS4808  中国 北京 联通
12  61.135.113.154  270.74 ms  AS4808  中国 北京 联通
13  *
14  *
15  123.125.99.1  242.82 ms  AS4808  中国 北京 联通


路由追踪到 北京电信 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 180.149.128.1 (180.149.128.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.77 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  28.60 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  87.245.240.185  9.44 ms  AS9002  罗马尼亚 布加勒斯特 retn.net
 4  87.245.232.234  35.08 ms  AS9002  RETN.NET 骨干网 retn.net
 5  87.245.236.153  45.27 ms  AS9002  RETN.NET 骨干网 retn.net
 6  202.97.52.69  206.23 ms  AS4134  中国 电信
 7  202.97.27.157  243.19 ms  AS4134  中国 北京 电信
 8  *
 9  180.149.159.6  304.20 ms  AS23724  中国 北京 电信
10  180.149.128.1  300.92 ms  AS23724  中国 北京 电信


路由追踪到 北京移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.136.88.117 (211.136.88.117), 30 hops max, 60 byte packets
 1  178.17.170.1  0.34 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.13 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.87 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.122  59.52 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.119.50  63.06 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  80.91.249.10  57.83 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.117.123  60.21 ms  AS1299  TELIA.COM 骨干网 telia.com
 8  62.115.171.223  57.93 ms  AS1299  欧洲地区 telia.com
 9  223.120.10.41  60.14 ms  AS58453  英国 伦敦 移动
10  *
11  *
12  *
13  *
14  221.176.27.253  296.01 ms  AS9808  中国 北京 移动
15  *
16  211.136.67.190  279.64 ms  AS56048  中国 北京 移动
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


路由追踪到 上海联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 58.247.0.49 (58.247.0.49), 30 hops max, 60 byte packets
 1  178.17.170.1  0.64 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  73.26 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  85.67 ms  AS8928  罗马尼亚 interoute.com
 4  89.149.129.37  112.83 ms  AS3257,AS8928  GTT.NET 骨干网 gtt.net
 5  *
 6  219.158.98.5  266.29 ms  AS4837  中国 北京 联通
 7  219.158.3.141  278.49 ms  AS4837  中国 北京 联通
 8  219.158.5.149  274.85 ms  AS4837  中国 北京 联通
 9  219.158.7.230  301.61 ms  AS4837  中国 上海 联通
10  139.226.225.190  295.62 ms  AS17621  中国 上海 联通
11  58.247.0.49  363.31 ms  AS17621  中国 上海 联通


路由追踪到 上海电信 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 180.153.28.1 (180.153.28.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.37 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.73 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  11.91 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.40 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.27 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.42 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  41.03 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.12 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  149.14.159.114  46.97 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  202.97.90.185  266.17 ms  AS4134  中国 上海 电信
12  202.97.90.30  364.48 ms  AS4134  中国 上海 电信
13  202.97.61.5  256.72 ms  AS4134  中国 上海 电信
14  101.95.120.157  274.92 ms  AS4812  中国 上海 电信
15  101.95.207.230  405.31 ms  AS4812  中国 上海 电信
16  124.74.232.66  377.80 ms  AS4812  中国 上海 电信
17  101.227.255.46  396.15 ms  AS4812  中国 上海 电信
18  *
19  101.227.250.3  388.99 ms  AS4812  中国 上海 电信
20  *
21  101.227.250.3  362.00 ms  AS4812  中国 上海 电信
22  *
23  180.153.28.1  360.58 ms  AS4812  中国 上海 电信


路由追踪到 上海移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 221.183.55.22 (221.183.55.22), 30 hops max, 60 byte packets
 1  178.17.170.1  35.26 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.83 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.12 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.34 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.36 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.72 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.205  51.19 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.174  128.09 ms  AS174  法国 法兰西岛大区 巴黎 cogentco.com
10  154.54.42.85  126.86 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.40.110  134.23 ms  AS174  美国 弗吉尼亚州 阿灵顿 cogentco.com
12  154.54.24.222  143.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.54.28.130  162.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
14  154.54.30.162  175.59 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
15  154.54.42.65  182.70 ms  AS174  美国 亚利桑那州 凤凰城 cogentco.com
16  154.54.45.162  195.11 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
17  154.54.45.162  192.43 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
18  38.19.140.58  227.46 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
19  223.118.10.153  232.67 ms  AS58453  美国 加利福尼亚州 洛杉矶 移动
20  *
21  221.183.25.118  351.46 ms  AS9808  中国 广东 广州 移动
22  221.183.25.118  359.26 ms  AS9808  中国 广东 广州 移动
23  *
24  221.176.16.205  343.11 ms  AS9808  中国 上海 移动
25  221.176.22.10  315.99 ms  AS9808  中国 上海 移动
26  221.183.55.22  329.55 ms  AS9808  中国 上海 移动


路由追踪到 广州联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.21.4.130 (210.21.4.130), 30 hops max, 60 byte packets
 1  178.17.170.1  23.97 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  19.76 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.140.27.237  9.47 ms  AS3356  罗马尼亚 布加勒斯特 level3.com
 4  4.69.153.125  194.31 ms  AS3356  美国 加利福尼亚州 洛杉矶 level3.com
 5  4.26.1.158  222.43 ms  AS3356  美国 加利福尼亚州 洛杉矶 level3.com
 6  219.158.96.233  360.20 ms  AS4837  中国 广东 广州 联通
 7  219.158.103.37  396.20 ms  AS4837  中国 广东 广州 联通
 8  219.158.8.117  379.33 ms  AS4837  中国 广东 广州 联通
 9  112.91.0.246  391.24 ms  AS17816  中国 广东 广州 联通
10  120.80.170.250  376.02 ms  AS17622  中国 广东 广州 联通
11  210.21.4.130  379.62 ms  AS17622  中国 广东 广州 联通


路由追踪到 广州电信 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 113.108.209.1 (113.108.209.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.30 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.84 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.26 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  11.95 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.14 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.48 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.60 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  40.77 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.17 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  149.14.159.114  46.94 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  202.97.52.93  331.81 ms  AS4134  中国 广东 广州 电信
12  202.97.94.70  336.88 ms  AS4134  中国 广东 广州 电信
13  202.97.91.153  261.24 ms  AS4134  中国 广东 广州 电信
14  113.108.208.226  251.63 ms  AS58466  中国 广东 广州 电信
15  113.108.209.1  244.90 ms  AS58466  中国 广东 广州 电信


路由追踪到 广州移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.139.129.5 (211.139.129.5), 30 hops max, 60 byte packets
 1  178.17.170.1  0.36 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.70 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.30 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.135.228  44.53 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.114.89  40.28 ms  AS1299  德国 黑森州 法兰克福 telia.com
 6  *
 7  *
 8  *
 9  221.183.55.90  242.28 ms  AS9808  中国 广东 广州 移动
10  221.176.19.209  238.40 ms  AS9808  中国 广东 广州 移动
11  221.176.22.125  240.02 ms  AS9808  中国 广东 广州 移动
12  *
13  *
14  *
15  211.139.129.5  233.68 ms  AS56040  中国 广东 广州 移动


路由追踪到 上海联通精品网 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.13.66.238 (210.13.66.238), 30 hops max, 60 byte packets
 1  178.17.170.1  0.33 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.40 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  87.245.240.185  16.36 ms  AS9002  罗马尼亚 布加勒斯特 retn.net
 4  87.245.232.234  34.10 ms  AS9002  RETN.NET 骨干网 retn.net
 5  *
 6  *
 7  4.68.75.102  122.78 ms  AS3356  美国 华盛顿 level3.com
 8  *
 9  208.222.0.98  341.69 ms  AS701  中国 北京 verizon.com
10  218.105.2.205  339.74 ms  AS9929  中国 上海 联通
11  218.105.2.210  336.55 ms  AS9929  中国 上海 联通
12  210.13.75.138  337.43 ms  AS9929  中国 上海 联通
13  210.13.66.237  338.65 ms  AS9929  中国 上海 联通
14  *
15  210.13.66.238  340.99 ms  AS9929  中国 上海 联通


路由追踪到 上海电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 58.32.0.1 (58.32.0.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.37 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.31 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  10.33 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.116  30.76 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.139.208  42.73 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  80.91.249.10  56.79 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.134.135  59.29 ms  AS1299  英国 伦敦 telia.com
 8  80.239.193.226  61.70 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  59.43.246.205  282.15 ms  AS4809  中国 上海 电信
10  *
11  59.43.138.69  287.69 ms  AS4809  中国 上海 电信
12  101.95.88.62  273.31 ms  AS4812  中国 上海 电信
13  58.32.0.1  252.29 ms  AS4812  中国 上海 电信


路由追踪到 北京鹏博士/电信通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.167.230.100 (211.167.230.100), 30 hops max, 60 byte packets
 1  178.17.170.1  0.28 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.56 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  9.19 ms  AS8928  罗马尼亚 interoute.com
 4  89.149.129.37  33.96 ms  AS3257,AS8928  GTT.NET 骨干网 gtt.net
 5  *
 6  219.158.98.13  276.86 ms  AS4837  中国 北京 联通
 7  219.158.3.145  247.13 ms  AS4837  中国 北京 联通
 8  219.158.18.65  245.17 ms  AS4837  中国 北京 联通
 9  *
10  61.148.159.86  250.05 ms  AS4808  中国 北京 联通
11  61.148.156.190  272.69 ms  AS4808  中国 北京 联通
12  *
13  *
14  124.205.97.166  212.39 ms  AS4847,AS17816  中国 北京 鹏博士/电信/铁通/联通
15  *
16  211.167.230.100  321.50 ms  AS4808,AS17964  中国 北京 鹏博士


路由追踪到 北京教育网 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 202.205.109.205 (202.205.109.205), 30 hops max, 60 byte packets
 1  178.17.170.1  0.30 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.77 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  5.36 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.63 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.70 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.37 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.61  41.82 ms  AS174  捷克 布拉格 cogentco.com
 8  154.54.38.205  50.41 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.174  129.99 ms  AS174  法国 法兰西岛大区 巴黎 cogentco.com
10  154.54.42.85  126.79 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.40.154  126.98 ms  AS174  美国 纽约州 纽约 cogentco.com
12  154.54.24.222  143.36 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.54.28.70  159.24 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
14  154.54.29.222  174.89 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
15  154.54.30.162  172.48 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
16  154.54.45.162  194.76 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
17  154.54.45.162  192.10 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
18  38.88.196.186  200.06 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
19  101.4.117.169  342.62 ms  AS4538  中国 北京 教育网
20  101.4.117.101  343.27 ms  AS4538  中国 北京 教育网
21  101.4.114.197  341.51 ms  AS4538  中国 北京 教育网
22  219.224.102.234  344.30 ms  AS4538  中国 北京 教育网
23  202.112.38.82  340.69 ms  AS4538  中国 北京 教育网
24  202.205.109.205  341.54 ms  AS4538  中国 北京 赛尔网络信息资源部 教育网


路由追踪到 北京科技网 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 159.226.254.1 (159.226.254.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.53 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.85 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.92 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.02 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  29.29 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.72 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  130.117.0.17  41.01 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.61.90  44.96 ms  AS174  意大利 伦巴第大区 米兰广域市 cogentco.com
10  154.54.36.69  53.78 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.1.118  223.74 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
12  *
13  159.226.254.5  256.40 ms  AS7497  中国 北京 科技网
14  159.226.254.49  256.92 ms  AS7497  中国 北京 科技网
15  159.226.254.1  258.76 ms  AS7497  中国 北京 科技网


路由追踪到 北京广电网 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.156.140.17 (211.156.140.17), 30 hops max, 60 byte packets
 1  178.17.170.1  0.55 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.95 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.06 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.67 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.49 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.37 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  40.82 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  41.43 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  149.14.159.114  47.56 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  202.97.52.69  208.65 ms  AS4134  中国 电信
12  202.97.58.97  304.49 ms  AS4134  中国 北京 电信
13  202.97.94.181  302.85 ms  AS4134  中国 北京 电信
14  *
15  *
16  *
17  *
18  211.156.140.17  229.04 ms  AS7641  中国 北京 chinabtn.com 广电网/联通/电信


路由追踪到 香港联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.160.95.218 (203.160.95.218), 30 hops max, 60 byte packets
 1  178.17.170.1  0.28 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.09 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  11.13 ms  AS8928  罗马尼亚 interoute.com
 4  89.149.184.38  210.31 ms  AS3257,AS8928  中国 香港 gtt.net
 5  69.174.124.134  214.03 ms  AS3257,AS8928  中国 香港 gtt.net
 6  119.252.139.14  213.95 ms  AS10099  中国 香港 联通
 7  202.77.22.89  211.33 ms  AS10099  中国 香港 联通
 8  203.160.95.218  211.04 ms  AS10099  中国 香港 联通


路由追踪到 香港电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.215.232.173 (203.215.232.173), 30 hops max, 60 byte packets
 1  178.17.170.1  0.39 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.72 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.84 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.09 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.31 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.46 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.59 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.21 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.46 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  149.14.159.114  46.40 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  202.97.95.158  352.32 ms  AS4134  中国 广东 广州 电信
12  *
13  203.215.232.173  294.86 ms  AS4134  中国 香港 电信


路由追踪到 香港电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.8.25.187 (203.8.25.187), 30 hops max, 60 byte packets
 1  178.17.170.1  0.38 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.18 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  10.71 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.116  30.56 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.119.66  43.37 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  *
 7  62.115.134.135  59.43 ms  AS1299  英国 伦敦 telia.com
 8  80.239.193.226  59.37 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  59.43.183.73  199.34 ms  AS4809  中国 北京 电信
10  59.43.250.174  218.60 ms  AS4809  中国 香港 电信
11  59.43.248.146  222.02 ms  AS4809  中国 香港 电信
12  203.8.25.187  228.91 ms  AS4809  中国 香港 电信


路由追踪到 香港移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.142.105.9 (203.142.105.9), 30 hops max, 60 byte packets
 1  178.17.170.1  0.48 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.33 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.17 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.29 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.52 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.80 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.79 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.209  50.86 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  58.03 ms  AS174  英国 伦敦 cogentco.com
10  154.54.58.174  59.84 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.60.242  58.14 ms  AS174  欧洲地区 cogentco.com
12  149.14.81.186  58.63 ms  AS174  英国 伦敦 cogentco.com
13  223.118.18.162  242.96 ms  AS58453  中国 香港 移动
14  223.119.0.2  243.42 ms  AS58453  中国 香港 移动
15  203.142.100.165  244.38 ms  AS9231  中国 香港 移动
16  203.142.100.22  243.78 ms  AS9231  中国 香港 移动
17  203.142.105.9  243.59 ms  AS9231  中国 香港 移动


路由追踪到 香港HGC (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 218.188.104.30 (218.188.104.30), 30 hops max, 60 byte packets
 1  178.17.170.1  0.46 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.97 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  5.89 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.98 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.56 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.105  33.25 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.46 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.205  50.62 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  126.96 ms  AS174  英国 伦敦 cogentco.com
10  154.54.27.169  129.83 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.40.106  134.33 ms  AS174  美国 弗吉尼亚州 阿灵顿 cogentco.com
12  154.54.24.222  144.63 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.54.28.70  161.43 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
14  154.54.30.162  174.56 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
15  154.54.42.65  183.99 ms  AS174  美国 亚利桑那州 凤凰城 cogentco.com
16  154.54.45.162  192.45 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
17  154.54.42.102  192.66 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
18  154.54.25.150  192.60 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
19  218.189.5.179  254.12 ms  AS9304  美国 加利福尼亚州 洛杉矶 hgc.com.hk
20  118.143.224.13  283.66 ms  AS9304  中国 香港 hgc.com.hk
21  218.189.5.24  254.66 ms  AS9304  中国 香港 hgc.com.hk
22  218.188.104.30  261.78 ms  AS9304  中国 香港 hgc.com.hk


路由追踪到 香港HKBN (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.6.23.239 (210.6.23.239), 30 hops max, 60 byte packets
 1  178.17.170.1  0.32 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.85 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.10 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.88 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.50 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  29.36 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  130.117.0.61  40.69 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.61.82  45.38 ms  AS174  意大利 伦巴第大区 米兰广域市 cogentco.com
10  154.54.36.69  53.13 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.1.118  222.57 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
12  *
13  61.244.225.68  218.92 ms  AS9269  中国 香港 hkbn.com.hk
14  203.186.235.137  220.22 ms  AS9269  中国 香港 hkbn.com.hk
15  203.80.215.70  218.16 ms  AS9269  中国 香港 hkbn.com.hk
16  210.6.23.239  218.42 ms  AS9269  中国 香港 hkbn.com.hk


路由追踪到 香港PCCW (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 202.85.125.60 (202.85.125.60), 30 hops max, 60 byte packets
 1  178.17.170.1  0.27 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.85 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.76 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.03 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.24 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  29.37 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  36.62 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.24 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  41.81 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  130.117.14.234  38.52 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  63.223.17.62  361.25 ms  AS3491  中国 香港 pccw.com
12  63.223.15.178  341.67 ms  AS3491  中国 香港 pccw.com
13  203.215.255.197  340.61 ms  AS9925  中国 香港 pbase.net
14  203.215.255.197  340.27 ms  AS9925  中国 香港 pbase.net
15  202.153.99.203  340.07 ms  AS9925  中国 香港 pbase.net
16  202.85.125.60  345.18 ms  AS9925  中国 香港 pccw.com


路由追踪到 香港TGT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 61.4.15.137 (61.4.15.137), 30 hops max, 60 byte packets
 1  178.17.170.1  0.39 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.89 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.09 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.36 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.47 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.105  33.69 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.61  41.85 ms  AS174  捷克 布拉格 cogentco.com
 8  154.54.38.209  50.46 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  126.88 ms  AS174  英国 伦敦 cogentco.com
10  154.54.42.85  126.95 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.46.34  128.22 ms  AS174  美国 纽约州 纽约 cogentco.com
12  154.54.7.158  146.22 ms  AS174  美国 乔治亚州 亚特兰大 cogentco.com
13  154.54.28.130  161.99 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
14  154.54.30.162  173.50 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
15  154.54.42.65  182.66 ms  AS174  美国 亚利桑那州 凤凰城 cogentco.com
16  154.54.44.86  193.66 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
17  154.54.42.102  194.99 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
18  38.142.238.218  195.29 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
19  62.216.140.113  351.18 ms  AS15412  英国 globalcloudxchange.com
20  85.95.26.137  336.46 ms  AS15412  GLOBALCLOUDXCHANGE.COM 骨干网 globalcloudxchange.com
21  85.95.26.89  348.02 ms  AS15412  中国 香港 globalcloudxchange.com
22  85.95.25.90  330.24 ms  AS15412  GLOBALCLOUDXCHANGE.COM 骨干网 globalcloudxchange.com
23  80.77.0.198  340.82 ms  AS15412  中国 香港 globalcloudxchange.com
24  203.78.72.112  337.82 ms  AS10098  中国 香港 towngastelecom.com
25  203.78.73.73  349.42 ms  AS10098  中国 香港 towngastelecom.com
26  203.78.73.73  339.80 ms  AS10098  中国 香港 towngastelecom.com
27  203.78.72.177  338.19 ms  AS10098  中国 香港 towngastelecom.com
28  202.123.74.2  350.98 ms  AS10098  中国 香港 towngastelecom.com
29  *
30  *


路由追踪到 香港WTT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 59.152.252.242 (59.152.252.242), 30 hops max, 60 byte packets
 1  178.17.170.1  0.63 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.69 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.60 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.76 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.20 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  31.35 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.69 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  130.117.0.17  41.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.61.90  45.33 ms  AS174  意大利 伦巴第大区 米兰广域市 cogentco.com
10  154.54.36.69  53.38 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.1.118  222.53 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
12  154.54.0.17  224.86 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.18.7.42  223.73 ms  AS174  中国 香港 cogentco.com
14  115.160.187.54  223.89 ms  AS9381  中国 香港 wtthk.com
15  10.104.131.158  223.74 ms  *  局域网
16  59.152.252.196  223.43 ms  AS9381  中国 香港 wtthk.com
17  59.152.252.242  223.65 ms  AS9381  中国 香港 wtthk.com


路由追踪到 新加坡电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.215.233.1 (203.215.233.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.45 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  2.19 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  5.06 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.52 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.85 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  42.59 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.25 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  149.14.159.114  48.04 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  202.97.17.81  333.21 ms  AS4134  中国 电信
12  203.215.233.1  241.99 ms  AS4134  新加坡 电信


路由追踪到 新加坡电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 183.91.61.1 (183.91.61.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.29 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.11 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.84 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.122  29.54 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.119.50  53.16 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.122.161  62.15 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.134.139  64.21 ms  AS1299  英国 伦敦 telia.com
 8  80.239.193.226  61.64 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  59.43.249.213  249.56 ms  AS4809  新加坡 电信
10  183.91.61.1  252.04 ms  AS4809  新加坡 电信


路由追踪到 新加坡Singtel (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 118.201.1.11 (118.201.1.11), 30 hops max, 60 byte packets
 1  178.17.170.1  0.41 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  10.56 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.23 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.135.228  186.21 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.123.13  185.77 ms  AS1299  法国 法兰西岛大区 巴黎 telia.com
 6  62.115.122.159  123.13 ms  AS1299  美国 弗吉尼亚州 阿什本 telia.com
 7  62.115.121.220  184.34 ms  AS1299  美国 加利福尼亚州 洛杉矶 telia.com
 8  62.115.8.203  185.07 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  203.208.158.29  366.30 ms  AS7473  新加坡 singtel.com
10  203.208.172.145  371.89 ms  AS7473  新加坡 singtel.com
11  203.208.182.253  402.36 ms  AS7473  新加坡 singtel.com
12  203.208.158.42  381.82 ms  AS7473  新加坡 singtel.com
13  203.208.158.42  376.58 ms  AS7473  新加坡 singtel.com
14  203.125.232.130  377.90 ms  AS3758  新加坡 singtel.com
15  165.21.49.126  354.49 ms  AS3758  新加坡 singtel.com
16  *
17  203.125.232.130  375.48 ms  AS3758  新加坡 singtel.com
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


路由追踪到 新加坡StarHub (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.116.221.47 (203.116.221.47), 30 hops max, 60 byte packets
 1  178.17.170.1  0.26 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.11 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.16 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.113.38  188.44 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.133.179  58.84 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.116.27  58.11 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  80.239.132.22  181.47 ms  AS1299  新加坡 telia.com
 8  203.118.15.133  197.56 ms  AS4657  新加坡 starhub.com
 9  203.118.6.117  185.36 ms  AS4657  新加坡 starhub.com
10  203.117.132.114  181.60 ms  AS4657  新加坡 starhub.com
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *


路由追踪到 新加坡M1 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.123.8.123 (203.123.8.123), 30 hops max, 60 byte packets
 1  178.17.170.1  16.96 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.65 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  3.96 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.47 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.24 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.69 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  40.92 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.15.66  38.27 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  195.22.197.25  226.61 ms  AS6762  意大利 西西里大区 巴勒莫广域市 tisparkle.com
11  93.186.133.69  291.27 ms  AS6762  新加坡 tisparkle.com
12  203.211.158.58  193.30 ms  AS17547  新加坡 m1.com.sg
13  203.211.158.118  206.08 ms  AS17547  新加坡 m1.com.sg
14  203.123.8.123  217.42 ms  AS17547  新加坡 m1.com.sg


路由追踪到 新加坡AWS (TCP 模式, 最大 50 跃点)
============================================================
traceroute to 13.228.0.251 (13.228.0.251), 50 hops max, 60 byte packets
 1  178.17.170.1  0.26 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.68 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.03 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.17 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  29.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.149  27.51 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.36  216.77 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.4.145  39.44 ms  AS2914  NTT.COM 骨干网 ntt.com
10  129.250.5.81  38.98 ms  AS2914  德国 黑森州 法兰克福 ntt.com
11  129.250.7.63  207.98 ms  AS2914  新加坡 ntt.com
12  129.250.3.100  216.45 ms  AS2914  新加坡 ntt.com
13  129.250.2.92  222.85 ms  AS2914  新加坡 ntt.com
14  116.51.17.46  218.15 ms  AS2914  新加坡 ntt.com
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  13.228.0.251  198.36 ms  AS16509  新加坡 amazon.com


路由追踪到 日本NTT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 61.213.155.84 (61.213.155.84), 30 hops max, 60 byte packets
 1  178.17.170.1  27.85 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.03 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.94 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.61 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.185  29.30 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.129  28.19 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.111  52.15 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.6.162  130.51 ms  AS2914  NTT.COM 骨干网 ntt.com
10  129.250.3.84  130.47 ms  AS2914  NTT.COM 骨干网 ntt.com
11  129.250.2.183  189.55 ms  AS2914  美国 加利福尼亚州 圣何塞 ntt.com
12  129.250.5.77  274.24 ms  AS2914  日本 东京都 东京 ntt.com
13  129.250.3.28  288.74 ms  AS2914  日本 东京都 东京 ntt.com
14  61.213.179.34  290.46 ms  AS2914  日本 东京都 东京 ntt.com
15  *
16  *
17  61.213.155.84  316.97 ms  AS2914  日本 东京都 东京 ntt.com


路由追踪到 日本IIJ (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 202.232.15.70 (202.232.15.70), 30 hops max, 60 byte packets
 1  178.17.170.1  0.38 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.39 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  24.42 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.116  58.99 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.119.66  139.91 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.122.161  62.19 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.114.235  59.18 ms  AS1299  TELIA.COM 骨干网 telia.com
 8  202.232.1.61  58.87 ms  AS2497  英国 伦敦 iij.ad.jp
 9  58.138.89.229  238.14 ms  AS2497  日本 东京都 东京 iij.ad.jp
10  58.138.101.14  239.10 ms  AS2497  日本 东京都 东京 iij.ad.jp
11  210.130.142.114  241.44 ms  AS2497  日本 东京都 iij.ad.jp
12  202.232.15.70  240.87 ms  AS2497  日本 iij.ad.jp


路由追踪到 日本SoftBank (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.175.32.26 (210.175.32.26), 30 hops max, 60 byte packets
 1  178.17.170.1  5.77 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.63 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  8.62 ms  AS8928  罗马尼亚 interoute.com
 4  213.254.230.250  187.00 ms  AS3257,AS8928  GTT.NET 骨干网 gtt.net
 5  221.111.203.109  238.88 ms  AS17676  BBTEC.NET 骨干网 bbtec.net
 6  *
 7  143.90.232.241  227.18 ms  AS4725  日本 东京都 东京 odn.ne.jp
 8  143.90.47.33  239.50 ms  AS4725  日本 odn.ne.jp
 9  143.90.26.230  237.99 ms  AS4725  日本 odn.ne.jp
10  143.90.54.30  232.90 ms  AS4725  日本 odn.ne.jp
11  210.175.32.123  244.06 ms  AS4725  日本 odn.ne.jp
12  210.175.32.26  239.05 ms  AS4725  日本 odn.ne.jp


路由追踪到 日本KDDI (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 106.162.242.108 (106.162.242.108), 30 hops max, 60 byte packets
 1  178.17.170.1  0.40 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.13 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.41 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.69 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.35 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.84 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  42.17 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.209  50.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  146.76 ms  AS174  英国 伦敦 cogentco.com
10  154.54.82.34  145.89 ms  AS174  美国 马萨诸塞州 波士顿 cogentco.com
11  154.54.43.18  152.24 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
12  154.54.26.129  151.79 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.54.7.129  197.46 ms  AS174  美国 伊利诺伊州 芝加哥 cogentco.com
14  154.54.42.165  158.52 ms  AS174  美国 伊利诺伊州 芝加哥 cogentco.com
15  154.54.31.89  197.08 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
16  154.54.41.145  185.07 ms  AS174  美国 科罗拉多州 丹佛 cogentco.com
17  154.54.44.137  196.80 ms  AS174  美国 加利福尼亚州 旧金山 cogentco.com
18  154.54.43.14  197.31 ms  AS174  美国 加利福尼亚州 圣何塞 cogentco.com
19  38.142.245.138  194.83 ms  AS174  美国 加利福尼亚州 圣何塞 cogentco.com
20  38.142.245.138  211.90 ms  AS174  美国 加利福尼亚州 圣何塞 cogentco.com
21  106.187.13.17  293.50 ms  AS2516  日本 东京都 东京 kddi.com
22  106.187.13.9  298.60 ms  AS2516  日本 东京都 东京 kddi.com
23  182.248.164.90  298.75 ms  AS2516  日本 kddi.com
24  182.248.164.90  297.17 ms  AS2516  日本 kddi.com
25  106.162.242.108  294.61 ms  AS2516  日本 kddi.com


路由追踪到 日本电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.215.236.3 (203.215.236.3), 30 hops max, 60 byte packets
 1  178.17.170.1  0.36 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.87 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.01 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.42 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.19 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.185  29.69 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.37 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  40.97 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.86 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  149.14.159.114  45.77 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  202.97.90.185  264.72 ms  AS4134  中国 上海 电信
12  202.97.6.70  299.00 ms  AS4134  日本 东京都 东京 电信
13  203.215.236.3  301.12 ms  AS4134  日本 东京都 东京 电信


路由追踪到 日本电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 202.55.27.4 (202.55.27.4), 30 hops max, 60 byte packets
 1  178.17.170.1  0.30 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.41 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  14.06 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.116  30.36 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.119.50  53.89 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.122.161  61.75 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.134.139  65.34 ms  AS1299  英国 伦敦 telia.com
 8  80.239.193.226  60.62 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  59.43.246.205  279.48 ms  AS4809  中国 上海 电信
10  59.43.186.186  314.15 ms  AS4809  日本 东京都 东京 电信
11  202.55.27.4  314.77 ms  AS4809  日本 东京都 东京 电信


路由追踪到 日本AWS (TCP 模式, 最大 50 跃点)
============================================================
traceroute to 13.112.63.251 (13.112.63.251), 50 hops max, 60 byte packets
 1  178.17.170.1  0.38 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.02 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.13 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.01 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.17 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  29.50 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.129  28.27 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.111  56.91 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.6.162  129.42 ms  AS2914  NTT.COM 骨干网 ntt.com
10  129.250.6.237  188.42 ms  AS2914  NTT.COM 骨干网 ntt.com
11  129.250.3.189  194.41 ms  AS2914  NTT.COM 骨干网 ntt.com
12  129.250.3.192  286.48 ms  AS2914  日本 东京都 东京 ntt.com
13  129.250.6.127  279.99 ms  AS2914  日本 东京都 东京 ntt.com
14  61.213.161.50  275.72 ms  AS2914  日本 东京都 东京 ntt.com
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  52.95.31.63  241.40 ms  AS16509  日本 东京都 东京 amazon.com
23  52.95.31.169  244.77 ms  AS16509  日本 东京都 东京 amazon.com
24  52.95.31.216  241.84 ms  AS16509  日本 东京都 东京 amazon.com
25  52.95.31.88  244.74 ms  AS16509  日本 东京都 东京 amazon.com
26  54.239.52.185  259.93 ms  AS16509  日本 东京都 东京 amazon.com
27  *
28  *
29  *
30  *
31  *
32  13.112.63.251  235.56 ms  AS16509  日本 东京都 东京 amazon.com


路由追踪到 韩国KT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 59.10.184.64 (59.10.184.64), 30 hops max, 60 byte packets
 1  178.17.170.1  0.32 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.17 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  87.245.240.185  8.68 ms  AS9002  罗马尼亚 布加勒斯特 retn.net
 4  87.245.234.83  172.12 ms  AS9002  RETN.NET 骨干网 retn.net
 5  87.245.240.209  180.91 ms  AS9002  RETN.NET 骨干网 retn.net
 6  112.174.89.185  248.98 ms  AS4766  KT.COM 骨干网 kt.com
 7  112.174.83.33  270.87 ms  AS4766  韩国 首尔 kt.com
 8  *
 9  112.174.120.86  268.45 ms  AS4766  韩国 首尔 kt.com
10  112.189.28.110  271.31 ms  AS4766  韩国 首尔 kt.com
11  112.189.48.146  272.65 ms  AS4766  韩国 首尔 kt.com
12  59.10.184.64  273.32 ms  AS4766  韩国 首尔 kt.com


路由追踪到 韩国SK (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 175.113.80.201 (175.113.80.201), 30 hops max, 60 byte packets
 1  178.17.170.1  1.19 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.72 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.09 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.28 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.00 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.44 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.149  27.82 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.111  50.49 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.6.162  132.82 ms  AS2914  NTT.COM 骨干网 ntt.com
10  129.250.3.84  125.44 ms  AS2914  NTT.COM 骨干网 ntt.com
11  129.250.3.189  185.32 ms  AS2914  NTT.COM 骨干网 ntt.com
12  129.250.6.49  188.83 ms  AS2914  NTT.COM 骨干网 ntt.com
13  129.250.2.214  190.82 ms  AS2914  美国 加利福尼亚州 洛杉矶 ntt.com
14  129.250.193.182  198.69 ms  AS2914  NTT.COM 骨干网 ntt.com
15  58.229.15.113  338.14 ms  AS9318  韩国 skbroadband.com
16  118.221.7.41  330.74 ms  AS9318  韩国 首尔 skbroadband.com
17  10.222.8.43  332.25 ms  *  局域网
18  *
19  110.11.28.242  329.95 ms  AS9318  韩国 首尔 skbroadband.com
20  175.113.80.201  336.08 ms  AS9318  韩国 skbroadband.com


路由追踪到 韩国LG (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.174.62.44 (211.174.62.44), 30 hops max, 60 byte packets
 1  178.17.170.1  1.07 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.58 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.140.27.237  10.05 ms  AS3356  罗马尼亚 布加勒斯特 level3.com
 4  *
 5  4.68.38.242  190.49 ms  AS3356  美国 level3.com
 6  1.213.105.17  189.65 ms  AS3786  美国 加利福尼亚州 帕洛阿尔托 uplus.co.kr
 7  1.208.104.213  266.30 ms  AS3786  韩国 首尔 uplus.co.kr
 8  *
 9  1.208.148.142  273.42 ms  AS3786  韩国 首尔 uplus.co.kr
10  1.213.150.77  267.80 ms  AS3786  韩国 首尔 uplus.co.kr
11  1.213.152.158  266.81 ms  AS3786  韩国 首尔 uplus.co.kr
12  61.111.0.154  264.36 ms  AS3786  韩国 首尔 uplus.co.kr
13  114.108.170.54  264.83 ms  AS3786  韩国 首尔 uplus.co.kr
14  211.174.62.44  264.53 ms  AS3786  韩国 首尔 uplus.co.kr


路由追踪到 韩国电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 218.185.246.1 (218.185.246.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.53 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.25 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  10.37 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.116  31.18 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.119.50  50.53 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.122.161  62.15 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.134.135  59.24 ms  AS1299  英国 伦敦 telia.com
 8  80.239.193.226  59.71 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  59.43.246.221  243.67 ms  AS4809  中国 上海 电信
10  218.185.246.1  261.16 ms  AS4809  韩国 首尔 电信


路由追踪到 韩国AWS (TCP 模式, 最大 50 跃点)
============================================================
traceroute to 13.124.63.251 (13.124.63.251), 50 hops max, 60 byte packets
 1  178.17.170.1  0.56 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.71 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.13 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.43 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.149  27.58 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.111  51.58 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.6.162  132.05 ms  AS2914  NTT.COM 骨干网 ntt.com
10  129.250.6.237  187.87 ms  AS2914  NTT.COM 骨干网 ntt.com
11  129.250.3.189  186.07 ms  AS2914  NTT.COM 骨干网 ntt.com
12  129.250.3.192  287.58 ms  AS2914  日本 东京都 东京 ntt.com
13  129.250.6.133  279.40 ms  AS2914  日本 东京都 东京 ntt.com
14  61.213.161.50  283.43 ms  AS2914  日本 东京都 东京 ntt.com
15  *
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  54.239.123.90  265.31 ms  AS16509  韩国 首尔 amazon.com
24  54.239.123.75  269.65 ms  AS16509  韩国 首尔 amazon.com
25  54.239.122.28  265.11 ms  AS16509  韩国 首尔 amazon.com
26  *
27  54.239.122.22  266.97 ms  AS16509  韩国 首尔 amazon.com
28  *
29  13.124.63.251  266.75 ms  AS16509  韩国 首尔 amazon.com


路由追踪到 台湾Chief (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 202.133.242.116 (202.133.242.116), 30 hops max, 60 byte packets
 1  178.17.170.1  0.39 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.67 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.15 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.40 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.29 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.47 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.209  50.54 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  146.62 ms  AS174  英国 伦敦 cogentco.com
10  154.54.44.162  152.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.43.18  152.26 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
12  154.54.26.129  146.16 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.54.7.129  150.98 ms  AS174  美国 伊利诺伊州 芝加哥 cogentco.com
14  154.54.42.165  163.94 ms  AS174  美国 伊利诺伊州 芝加哥 cogentco.com
15  154.54.5.89  169.89 ms  AS174  美国 科罗拉多州 丹佛 cogentco.com
16  154.54.41.145  180.20 ms  AS174  美国 科罗拉多州 丹佛 cogentco.com
17  154.54.44.137  201.18 ms  AS174  美国 加利福尼亚州 旧金山 cogentco.com
18  154.54.7.174  195.71 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
19  202.39.84.29  194.82 ms  AS9680  美国 加利福尼亚州 洛杉矶 cht.com.tw
20  202.39.84.29  194.74 ms  AS9680  美国 加利福尼亚州 洛杉矶 cht.com.tw
21  220.128.12.2  314.09 ms  AS3462  中国 台湾 台北市 cht.com.tw
22  220.128.7.118  316.02 ms  AS3462  中国 台湾 台北市 cht.com.tw
23  220.128.2.237  314.40 ms  AS3462  中国 台湾 台北市 cht.com.tw
24  203.75.228.157  457.88 ms  AS3462  中国 台湾 台北市 cht.com.tw
25  *
26  113.21.95.72  321.54 ms  AS17408  中国 台湾 台北市 chief.com.tw
27  113.21.95.72  319.19 ms  AS17408  中国 台湾 台北市 chief.com.tw
28  103.123.254.38  326.91 ms  AS17408  中国 台湾 台北市 chief.com.tw
29  202.133.242.114  316.44 ms  AS17408  中国 台湾 台北市 chief.com.tw
30  202.133.242.116  315.34 ms  AS17408  中国 台湾 台北市 chief.com.tw


路由追踪到 台湾APTG (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.200.69.90 (210.200.69.90), 30 hops max, 60 byte packets
 1  178.17.170.1  0.49 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.91 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  3.90 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.19 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.04 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.97  33.50 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.61  41.79 ms  AS174  捷克 布拉格 cogentco.com
 8  154.54.38.205  50.93 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  58.37 ms  AS174  英国 伦敦 cogentco.com
10  154.54.57.154  57.85 ms  AS174  英国 伦敦 cogentco.com
11  134.159.95.224  57.27 ms  AS4637  英国 伦敦 telstra.com
12  202.40.148.33  58.55 ms  AS4637,AS10026  英国 伦敦 reach.com
13  202.84.141.125  251.64 ms  AS4637,AS10026  TELSTRA.COM 骨干网 telstra.com
14  202.84.138.182  287.39 ms  AS4637,AS10026  中国 台湾 台北市 telstra.com
15  202.84.137.253  290.08 ms  AS4637,AS10026  中国 台湾 台北市 telstra.com
16  210.176.44.78  287.22 ms  AS4637,AS10026  中国 台湾 台北市 telstra.com
17  211.76.109.158  289.13 ms  AS17709  中国 台湾 台北市 aptg.com.tw
18  *
19  211.76.96.76  287.81 ms  AS17709  中国 台湾 台北市 aptg.com.tw
20  211.76.100.61  288.59 ms  AS17709  中国 台湾 台北市 aptg.com.tw
21  210.200.80.254  287.77 ms  AS131142  中国 台湾 台北市 aptg.com.tw
22  *
23  210.200.69.90  289.60 ms  AS131142  中国 台湾 台北市 aptg.com.tw


路由追踪到 台湾CHT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.75.129.162 (203.75.129.162), 30 hops max, 60 byte packets
 1  178.17.170.1  0.28 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.07 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  87.245.240.185  9.23 ms  AS9002  罗马尼亚 布加勒斯特 retn.net
 4  87.245.232.234  34.22 ms  AS9002  RETN.NET 骨干网 retn.net
 5  80.231.65.1  34.28 ms  AS6453  德国 黑森州 法兰克福 tatacommunications.com
 6  5.23.30.16  49.88 ms  AS6453  德国 黑森州 法兰克福 tatacommunications.com
 7  195.219.156.133  48.46 ms  AS6453  德国 黑森州 法兰克福 tatacommunications.com
 8  *
 9  80.231.200.17  287.27 ms  AS6453  中国 台湾 tatacommunications.com
10  220.128.6.38  287.87 ms  AS3462  中国 台湾 新北市 cht.com.tw
11  220.128.12.38  305.38 ms  AS3462  中国 台湾 新北市 cht.com.tw
12  220.128.26.78  285.64 ms  AS3462  中国 台湾 台北市 cht.com.tw
13  220.128.1.5  286.10 ms  AS3462  中国 台湾 台北市 cht.com.tw
14  211.22.229.45  285.94 ms  AS3462  中国 台湾 台北市 cht.com.tw
15  1.1.1.2  286.05 ms  AS12445  CLOUDFLARE.COM apnic.net
16  *
17  203.75.129.162  285.61 ms  AS3462  中国 台湾 台北市 cht.com.tw


路由追踪到 台湾TFN (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 219.87.66.3 (219.87.66.3), 30 hops max, 60 byte packets
 1  178.17.170.1  2.34 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.06 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.140.27.237  12.13 ms  AS3356  罗马尼亚 布加勒斯特 level3.com
 4  4.69.203.121  189.15 ms  AS3356  美国 加利福尼亚州 圣何塞 level3.com
 5  4.79.238.26  189.21 ms  AS3356  美国 加利福尼亚州 圣何塞 level3.com
 6  60.199.20.33  332.85 ms  AS9924  中国 台湾 twmbroadband.com
 7  60.199.18.10  323.10 ms  AS9924  中国 台湾 台北市 twmbroadband.com
 8  60.199.3.138  323.20 ms  AS9924  中国 台湾 台北市 twmbroadband.com
 9  60.199.16.62  324.23 ms  AS9924  中国 台湾 台北市 twmbroadband.com
10  219.87.66.3  323.58 ms  AS9924  中国 台湾 台北市 twmbroadband.com


路由追踪到 台湾FET (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.73.144.38 (211.73.144.38), 30 hops max, 60 byte packets
 1  178.17.170.1  0.32 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.82 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.73 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.00 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.41 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.34 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.149  27.81 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.111  51.66 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.4.9  215.58 ms  AS2914  新加坡 ntt.com
10  129.250.3.74  212.96 ms  AS2914  新加坡 ntt.com
11  129.250.7.67  233.49 ms  AS2914  中国 香港 ntt.com
12  129.250.2.181  283.74 ms  AS2914  NTT.COM 骨干网 ntt.com
13  199.245.16.34  302.17 ms  AS2914  中国 台湾 台北市 ntt.com
14  192.72.155.25  284.12 ms  AS4780  中国 台湾 台北市 fetnet.net
15  192.72.155.98  231.60 ms  AS4780  中国 台湾 台北市 fetnet.net
16  *
17  *
18  *
19  211.73.144.38  234.71 ms  AS9674  中国 台湾 fetnet.net


路由追踪到 台湾KBT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 61.63.0.102 (61.63.0.102), 30 hops max, 60 byte packets
 1  178.17.170.1  0.27 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.70 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  3.99 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  11.99 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.97  33.37 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.92 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.209  50.81 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  130.117.2.142  129.51 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  154.54.42.85  126.06 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.40.106  134.24 ms  AS174  美国 弗吉尼亚州 阿灵顿 cogentco.com
12  154.54.40.106  131.64 ms  AS174  美国 弗吉尼亚州 阿灵顿 cogentco.com
13  154.54.28.70  160.32 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
14  154.54.30.162  173.42 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
15  154.54.42.77  184.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
16  154.54.44.86  193.27 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
17  154.54.27.118  197.29 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
18  38.104.85.130  184.91 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
19  203.78.181.145  334.06 ms  AS9505  中国 台湾 台北市 twgate.net
20  175.41.61.174  328.37 ms  AS9505  中国 台湾 台北市 twgate.net
21  175.41.61.174  327.07 ms  AS9505  中国 台湾 台北市 twgate.net
22  203.187.9.241  329.31 ms  AS9416  中国 台湾 台北市 kbtelecom.net
23  203.187.9.238  332.18 ms  AS9416  中国 台湾 台北市 kbtelecom.net
24  203.187.9.238  328.09 ms  AS9416  中国 台湾 台北市 kbtelecom.net
25  58.86.1.174  334.43 ms  AS18042  中国 台湾 台北市 kbtelecom.net
26  58.86.0.26  334.21 ms  AS18042  中国 台湾 台北市 kbtelecom.net
27  58.86.0.26  346.47 ms  AS18042  中国 台湾 台北市 kbtelecom.net
28  61.63.0.102  331.52 ms  AS18042  中国 台湾 台北市 kbtelecom.net


路由追踪到 台湾TAIFO (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 103.31.196.203 (103.31.196.203), 30 hops max, 60 byte packets
 1  178.17.170.1  0.38 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.64 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.01 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.02 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  29.49 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.105  33.39 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.77 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.205  50.72 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  130.117.51.41  131.01 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  154.54.27.169  130.11 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.40.106  134.35 ms  AS174  美国 弗吉尼亚州 阿灵顿 cogentco.com
12  154.54.24.222  144.25 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  154.54.28.130  159.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
14  154.54.30.162  173.74 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
15  154.54.42.65  182.73 ms  AS174  美国 亚利桑那州 凤凰城 cogentco.com
16  154.54.44.86  193.44 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
17  154.54.25.150  193.53 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
18  38.142.238.218  193.41 ms  AS174  美国 加利福尼亚州 洛杉矶 cogentco.com
19  62.216.140.113  318.35 ms  AS15412  英国 globalcloudxchange.com
20  62.216.128.94  319.26 ms  AS15412  中国 台湾 台北市 globalcloudxchange.com
21  62.216.136.141  317.35 ms  AS15412  中国 台湾 台北市 globalcloudxchange.com
22  80.77.2.198  334.97 ms  AS15412  中国 台湾 台北市 globalcloudxchange.com
23  103.123.253.9  319.11 ms  AS17408  中国 台湾 台北市 chief.com.tw
24  113.21.95.123  320.30 ms  AS17408  中国 台湾 台北市 chief.com.tw
25  *
26  103.31.197.122  333.86 ms  AS131584  中国 台湾 台北市 taifo.com.tw
27  *
28  103.31.197.70  317.14 ms  AS131584  中国 台湾 台北市 taifo.com.tw
29  103.31.196.203  320.14 ms  AS131584  中国 台湾 台北市 taifo.com.tw


路由追踪到 美国洛杉矶电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 218.30.33.17 (218.30.33.17), 30 hops max, 60 byte packets
 1  178.17.170.1  0.30 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.68 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  5.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.93 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.35 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.65 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.67 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.06 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  41.12 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  149.14.159.114  45.55 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  218.30.33.17  131.76 ms  AS4134  美国 ctamericas.com


路由追踪到 美国洛杉矶电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 66.102.252.100 (66.102.252.100), 30 hops max, 60 byte packets
 1  178.17.170.1  0.98 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  14.33 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.140.27.237  9.52 ms  AS3356  罗马尼亚 布加勒斯特 level3.com
 4  *
 5  *
 6  212.187.165.22  56.37 ms  AS3356  英国 伦敦 level3.com
 7  *
 8  *
 9  66.102.252.100  195.50 ms  AS4809  美国 加利福尼亚州 洛杉矶 ctamericas.com


路由追踪到 美国洛杉矶PCCW (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 63.218.42.81 (63.218.42.81), 30 hops max, 60 byte packets
 1  178.17.170.1  4.87 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.06 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.19 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.77 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  36.00 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.21 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  40.92 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  130.117.14.234  38.71 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  63.218.42.81  186.69 ms  AS3491  美国 加利福尼亚州 洛杉矶 pccw.com


路由追踪到 美国洛杉矶HE (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 66.220.18.42 (66.220.18.42), 30 hops max, 60 byte packets
 1  178.17.170.1  23.88 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.79 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  86.104.125.69  8.63 ms  AS7713,AS9009  罗马尼亚 布加勒斯特 interlan.ro
 4  184.105.65.45  22.85 ms  AS6939  HE.NET 骨干网 he.net
 5  184.105.213.249  23.68 ms  AS6939  HE.NET 骨干网 he.net
 6  184.105.65.5  40.66 ms  AS6939  HE.NET 骨干网 he.net
 7  184.105.213.173  116.31 ms  AS6939  HE.NET 骨干网 he.net
 8  184.105.80.202  171.78 ms  AS6939  HE.NET 骨干网 he.net
 9  66.220.18.42  170.67 ms  AS6939  美国 加利福尼亚州 洛杉矶 he.net


路由追踪到 美国洛杉矶GTT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 173.205.77.98 (173.205.77.98), 30 hops max, 60 byte packets
 1  178.17.170.1  0.52 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.45 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  9.31 ms  AS8928  罗马尼亚 interoute.com
 4  89.149.181.102  176.00 ms  AS3257,AS8928  美国 加利福尼亚州 洛杉矶 gtt.net
 5  173.205.77.98  175.51 ms  AS3257,AS8928  美国 加利福尼亚州 洛杉矶 gtt.net


路由追踪到 美国旧金山ATT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 12.169.215.33 (12.169.215.33), 30 hops max, 60 byte packets
 1  178.17.170.1  0.31 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.81 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  5.92 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  11.98 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.13 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.37 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  42.02 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.209  50.51 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  127.25 ms  AS174  英国 伦敦 cogentco.com
10  154.54.42.85  128.33 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.0.142  131.12 ms  AS174  美国 纽约州 纽约 cogentco.com
12  154.54.10.98  128.23 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
13  12.122.131.102  197.63 ms  AS7018  美国 纽约州 纽约 att.com
14  12.122.2.237  203.25 ms  AS7018  美国 伊利诺伊州 芝加哥 att.com
15  12.122.2.237  200.40 ms  AS7018  美国 伊利诺伊州 芝加哥 att.com
16  12.122.1.174  208.81 ms  AS7018  美国 加利福尼亚州 旧金山 att.com
17  12.122.110.13  199.61 ms  AS7018  美国 加利福尼亚州 att.com
18  12.244.156.30  202.64 ms  AS7018  美国 加利福尼亚州 att.com
19  12.169.215.33  203.34 ms  AS7018  美国 加利福尼亚州 att.com


路由追踪到 美国纽约TATA (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 66.198.181.100 (66.198.181.100), 30 hops max, 60 byte packets
 1  178.17.170.1  0.70 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.81 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.34 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.05 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.40 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.34 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.50 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  40.83 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  41.00 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  130.117.15.86  38.19 ms  AS174  西班牙 马德里自治区 马德里 cogentco.com
11  195.219.50.2  127.14 ms  AS6453  德国 黑森州 法兰克福 tatacommunications.com
12  5.23.30.16  119.04 ms  AS6453  德国 黑森州 法兰克福 tatacommunications.com
13  195.219.194.6  123.43 ms  AS6453  荷兰 北荷兰省 阿姆斯特丹 tatacommunications.com
14  80.231.131.160  122.60 ms  AS6453  英国 伦敦 tatacommunications.com
15  80.231.131.158  122.25 ms  AS6453  美国 纽约州 纽约 tatacommunications.com
16  216.6.90.21  127.52 ms  AS6453  美国 纽约州 纽约 tatacommunications.com
17  216.6.90.73  125.54 ms  AS6453  美国 纽约州 纽约 tatacommunications.com
18  209.58.75.198  129.27 ms  AS6453  美国 纽约州 纽约 tatacommunications.com
19  209.58.75.198  129.27 ms  AS6453  美国 纽约州 纽约 tatacommunications.com
20  66.198.181.100  123.23 ms  AS6453  美国 纽约州 纽约 tatacommunications.com


路由追踪到 美国圣何塞电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 218.30.33.17 (218.30.33.17), 30 hops max, 60 byte packets
 1  178.17.170.1  0.27 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.19 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.04 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.51 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.12 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.53 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.74 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  40.87 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  41.35 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  149.14.159.114  46.59 ms  AS174  德国 黑森州 法兰克福 cteurope.net cogentco.com
11  218.30.33.17  131.39 ms  AS4134  美国 ctamericas.com


路由追踪到 美国圣何塞NTT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 23.11.26.62 (23.11.26.62), 30 hops max, 60 byte packets
 1  178.17.170.1  0.35 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.09 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.33 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.15 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.30 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.35 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  129.250.9.149  27.73 ms  AS2914  NTT.COM 骨干网 ntt.com
 8  129.250.2.111  51.57 ms  AS2914  NTT.COM 骨干网 ntt.com
 9  129.250.6.162  125.96 ms  AS2914  NTT.COM 骨干网 ntt.com
10  129.250.6.237  193.57 ms  AS2914  NTT.COM 骨干网 ntt.com
11  129.250.3.121  190.55 ms  AS2914  NTT.COM 骨干网 ntt.com
12  129.250.3.163  187.59 ms  AS2914  NTT.COM 骨干网 ntt.com
13  23.11.26.62  193.93 ms  AS2914  美国 加利福尼亚州 圣何塞 akamai.com


路由追踪到 美国费利蒙HE (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 72.52.104.74 (72.52.104.74), 30 hops max, 60 byte packets
 1  178.17.170.1  0.76 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.39 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  86.104.125.69  8.50 ms  AS7713,AS9009  罗马尼亚 布加勒斯特 interlan.ro
 4  184.105.65.45  19.49 ms  AS6939  HE.NET 骨干网 he.net
 5  184.105.213.249  24.39 ms  AS6939  HE.NET 骨干网 he.net
 6  184.105.65.5  40.48 ms  AS6939  HE.NET 骨干网 he.net
 7  184.105.81.77  110.27 ms  AS6939  美国 纽约州 纽约 he.net
 8  184.104.192.242  109.66 ms  AS6939  HE.NET 骨干网 he.net
 9  184.105.81.61  180.46 ms  AS6939  HE.NET 骨干网 he.net
10  72.52.104.74  173.82 ms  AS6939  美国 加利福尼亚州 费利蒙 he.net


路由追踪到 美国达拉斯Level3 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 205.216.62.38 (205.216.62.38), 30 hops max, 60 byte packets
 1  178.17.170.1  0.28 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.63 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  11.89 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.12 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.105  33.46 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  130.117.1.205  41.65 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.38.205  50.77 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.174  127.73 ms  AS174  法国 法兰西岛大区 巴黎 cogentco.com
10  154.54.27.169  130.03 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  66.28.4.182  126.22 ms  AS174  美国 纽约州 纽约 cogentco.com
12  66.28.4.182  126.04 ms  AS174  美国 纽约州 纽约 cogentco.com
13  67.14.14.34  146.16 ms  AS209  美国 乔治亚州 亚特兰大 centurylink.com
14  216.34.172.50  173.78 ms  AS3561  美国 德克萨斯州 达拉斯 centurylink.com
15  216.34.164.106  174.56 ms  AS3561  美国 德克萨斯州 达拉斯 centurylink.com
16  216.34.164.90  169.14 ms  AS3561  美国 德克萨斯州 达拉斯 centurylink.com
17  205.216.7.204  171.26 ms  AS3561  美国 德克萨斯州 达拉斯 centurylink.com
18  205.216.62.38  171.42 ms  AS3561  美国 德克萨斯州 达拉斯 centurylink.com


路由追踪到 美国迈阿密ZAYO (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 64.125.191.144 (64.125.191.144), 30 hops max, 60 byte packets
 1  178.17.170.1  0.53 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.24 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  3.96 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.20 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.41 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  30.56 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.31 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.32 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.40 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  64.125.12.53  44.14 ms  AS6461  德国 黑森州 法兰克福 zayo.com
11  64.125.26.233  43.68 ms  AS6461  德国 黑森州 法兰克福 zayo.com
12  64.125.31.216  157.79 ms  AS6461  ZAYO.COM 骨干网 zayo.com
13  64.125.29.59  162.51 ms  AS6461  荷兰 北荷兰省 阿姆斯特丹 zayo.com
14  64.125.29.80  148.50 ms  AS6461  荷兰 北荷兰省 阿姆斯特丹 zayo.com
15  64.125.29.17  149.02 ms  AS6461  英国 伯克郡 斯劳 zayo.com
16  64.125.29.118  155.78 ms  AS6461  英国 伯克郡 斯劳 zayo.com
17  64.125.29.126  167.61 ms  AS6461  美国 纽约州 纽约 zayo.com
18  64.125.29.203  155.89 ms  AS6461  美国 华盛顿 zayo.com
19  64.125.31.169  191.36 ms  AS6461  ZAYO.COM 骨干网 zayo.com
20  64.125.30.205  153.43 ms  AS6461  美国 zayo.com
21  64.125.28.17  149.43 ms  AS6461  ZAYO.COM 骨干网 zayo.com
22  64.125.191.144  149.09 ms  AS6461  美国 佛罗里达州 迈阿密 zayo.com


路由追踪到 美国阿什本Cogentco (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 149.127.109.166 (149.127.109.166), 30 hops max, 60 byte packets
 1  178.17.170.1  0.30 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.98 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.12 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  12.27 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.46 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.97  33.70 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.61  41.59 ms  AS174  捷克 布拉格 cogentco.com
 8  154.54.38.209  51.15 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 9  154.54.56.93  126.16 ms  AS174  英国 伦敦 cogentco.com
10  154.54.42.85  129.14 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
11  154.54.40.106  133.71 ms  AS174  美国 弗吉尼亚州 阿灵顿 cogentco.com
12  154.54.46.190  135.45 ms  AS174  美国 弗吉尼亚州 赫恩登 cogentco.com
13  38.140.164.58  136.55 ms  AS174  美国 弗吉尼亚州 赫恩登 cogentco.com
14  149.127.109.2  136.69 ms  AS174  美国 弗吉尼亚州 阿什本 cogentco.com
15  149.127.109.166  135.57 ms  AS174  美国 弗吉尼亚州 阿什本 cogentco.com


路由追踪到 德国北莱茵－威斯特法伦州Telekom (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 80.146.191.1 (80.146.191.1), 30 hops max, 60 byte packets
 1  178.17.170.1  0.71 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  2.25 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.19 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  11.97 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.28 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.185  29.43 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.94 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  40.80 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  40.81 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  *
11  *
12  80.146.191.1  60.23 ms  AS3320  德国 北莱茵－威斯特法伦州 telekom.de


路由追踪到 德国法兰克福O2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 82.113.108.25 (82.113.108.25), 30 hops max, 60 byte packets
 1  178.17.170.1  0.41 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.45 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  87.245.240.185  31.33 ms  AS9002  罗马尼亚 布加勒斯特 retn.net
 4  87.245.233.164  35.41 ms  AS9002  德国 黑森州 法兰克福 retn.net
 5  80.81.192.89  35.86 ms  AS18403,AS29686,AS39912  德国 黑森州 法兰克福 de-cix.net
 6  62.53.28.170  41.91 ms  AS6805  德国 telefonica.de
 7  62.53.2.51  41.99 ms  AS6805  德国 telefonica.de
 8  62.53.28.151  42.88 ms  AS6805  德国 telefonica.de
 9  82.113.101.77  41.95 ms  AS39706  德国 黑森州 法兰克福 o2online.de
10  62.53.2.55  41.57 ms  AS6805  德国 黑森州 法兰克福 telefonica.de
11  82.113.108.25  41.48 ms  AS39706  德国 黑森州 法兰克福 o2online.de


路由追踪到 德国法兰克福Vodafone (TCP 模式, 最大 50 跃点)
============================================================
traceroute to 139.7.146.11 (139.7.146.11), 50 hops max, 60 byte packets
 1  178.17.170.1  0.69 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.12 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.140.27.237  9.53 ms  AS3356  罗马尼亚 布加勒斯特 level3.com
 4  *
 5  4.68.74.10  46.81 ms  AS3356  美国 level3.com
 6  145.254.16.128  51.01 ms  AS3209  德国 vodafone.de
 7  92.79.230.14  51.06 ms  AS3209  德国 vodafone.de
 8  139.7.148.84  51.09 ms  AS3209  德国 vodafone.de
 9  *
10  *
11  *
12  *
13  139.7.146.11  79.07 ms  AS3209  德国 vodafone.de


路由追踪到 德国法兰克福电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 118.85.205.101 (118.85.205.101), 30 hops max, 60 byte packets
 1  178.17.170.1  0.40 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  1.57 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  5.26 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.07 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.42 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.43 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.56 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.36 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.0.2  41.67 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  118.85.205.101  43.78 ms  AS4134  德国 黑森州 法兰克福 电信


路由追踪到 德国法兰克福电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 5.10.138.33 (5.10.138.33), 30 hops max, 60 byte packets
 1  178.17.170.1  6.08 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.09 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.140.27.237  9.68 ms  AS3356  罗马尼亚 布加勒斯特 level3.com
 4  *
 5  *
 6  212.187.165.22  55.79 ms  AS3356  英国 伦敦 level3.com
 7  59.43.180.113  72.19 ms  AS4809  中国 电信
 8  5.10.138.33  71.02 ms  AS4809  德国 cteurope.net


路由追踪到 德国法兰克福GTT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 213.200.65.70 (213.200.65.70), 30 hops max, 60 byte packets
 1  178.17.170.1  0.35 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.51 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  213.39.84.57  8.78 ms  AS8928  罗马尼亚 interoute.com
 4  213.200.116.213  34.70 ms  AS3257,AS8928  GTT.NET 骨干网 gtt.net
 5  213.200.65.70  34.87 ms  AS3257,AS8928  GTT.NET 骨干网 gtt.net


路由追踪到 德国法兰克福Cogentco (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 212.20.150.5 (212.20.150.5), 30 hops max, 60 byte packets
 1  178.17.170.1  0.47 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.95 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.34 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.20 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.27 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.185  29.27 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.51 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.34 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  154.54.56.34  41.12 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  212.20.150.5  40.98 ms  AS174  德国 cogentco.com


路由追踪到 英国Vodafone (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 194.62.232.211 (194.62.232.211), 30 hops max, 60 byte packets
 1  178.17.170.1  0.37 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.59 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  154.54.56.62  8.28 ms  AS174  罗马尼亚 布加勒斯特 cogentco.com
 4  130.117.48.181  17.60 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  195.2.17.73  33.49 ms  AS1273  VODAFONE.COM 骨干网 vodafone.com
 6  195.2.27.174  59.40 ms  AS1273  VODAFONE.COM 骨干网 vodafone.com
 7  195.2.22.189  59.27 ms  AS1273  VODAFONE.COM 骨干网 vodafone.com
 8  195.2.28.29  53.56 ms  AS1273  VODAFONE.COM 骨干网 vodafone.com
 9  195.2.24.65  59.08 ms  AS1273  英国 伯克郡 斯劳 vodafone.com
10  *
11  *
12  194.62.232.211  60.27 ms  AS25135  英国 vodafone.com


路由追踪到 英国BT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 213.121.43.24 (213.121.43.24), 30 hops max, 60 byte packets
 1  178.17.170.1  23.26 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  9.16 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  87.245.240.185  9.15 ms  AS9002  罗马尼亚 布加勒斯特 retn.net
 4  87.245.234.114  46.78 ms  AS9002  RETN.NET 骨干网 retn.net
 5  109.159.253.20  49.29 ms  AS2856  英国 伦敦 bt.com
 6  194.72.16.183  48.01 ms  AS2856  英国 bt.com
 7  109.159.249.8  47.60 ms  AS2856  英国 bt.com
 8  194.72.7.69  47.02 ms  AS2856  英国 bt.com
 9  *
10  *
11  *
12  *
13  *
14  213.121.43.24  54.70 ms  AS2856  英国 bt.com


路由追踪到 英国伦敦TATA (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 80.231.60.38 (80.231.60.38), 30 hops max, 60 byte packets
 1  178.17.170.1  0.31 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.64 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  3.99 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.01 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.54 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.86  29.62 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  36.79 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  40.83 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  40.98 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  130.117.15.86  40.59 ms  AS174  西班牙 马德里自治区 马德里 cogentco.com
11  195.219.50.21  53.74 ms  AS6453  德国 黑森州 法兰克福 tatacommunications.com
12  195.219.194.149  58.10 ms  AS6453  荷兰 北荷兰省 阿姆斯特丹 tatacommunications.com
13  195.219.194.6  52.18 ms  AS6453  荷兰 北荷兰省 阿姆斯特丹 tatacommunications.com
14  195.219.194.6  52.14 ms  AS6453  荷兰 北荷兰省 阿姆斯特丹 tatacommunications.com
15  80.231.131.160  52.68 ms  AS6453  英国 伦敦 tatacommunications.com
16  80.231.130.130  52.60 ms  AS6453  英国 伦敦 tatacommunications.com
17  80.231.60.38  52.39 ms  AS6453  英国 伦敦 tatacommunications.com


路由追踪到 俄罗斯电信163 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 118.85.205.121 (118.85.205.121), 30 hops max, 60 byte packets
 1  178.17.170.1  0.30 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.67 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.20 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  154.54.58.241  12.10 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.60.205  28.12 ms  AS174  欧洲地区 cogentco.com
 6  154.54.59.185  29.47 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.58.5  35.51 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.253  41.12 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  130.117.1.117  41.00 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
10  118.85.205.121  43.58 ms  AS4134  德国 黑森州 法兰克福 电信


路由追踪到 俄罗斯电信CN2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 185.75.173.17 (185.75.173.17), 30 hops max, 60 byte packets
 1  178.17.170.1  0.28 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.45 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  10.10 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.122  28.77 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.139.208  43.38 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  80.91.249.10  56.01 ms  AS1299  TELIA.COM 骨干网 telia.com
 7  62.115.134.135  59.35 ms  AS1299  英国 伦敦 telia.com
 8  80.239.193.226  61.26 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  59.43.180.113  73.56 ms  AS4809  中国 电信
10  185.75.173.17  109.60 ms  AS4809  俄罗斯 莫斯科 cteurope.net


路由追踪到 俄罗斯莫斯科RT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 87.226.162.77 (87.226.162.77), 30 hops max, 60 byte packets
 1  178.17.170.1  0.32 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  10.21 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.11 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.113.38  36.18 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.121.1  56.02 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.151.97  40.46 ms  AS1299  德国 黑森州 法兰克福 telia.com
 7  213.59.211.241  137.06 ms  AS8997,AS12389  俄罗斯 莫斯科 rt.ru
 8  87.226.140.2  76.64 ms  AS8997,AS12389  俄罗斯 莫斯科 rt.ru
 9  *
10  87.226.162.77  80.24 ms  AS8997,AS12389  俄罗斯 莫斯科 rt.ru


路由追踪到 俄罗斯莫斯科TTK (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 217.150.32.2 (217.150.32.2), 30 hops max, 60 byte packets
 1  178.17.170.1  1.31 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  149.14.58.73  0.90 ms  AS174  摩尔多瓦 基希讷乌 cogentco.com
 3  130.117.48.154  4.40 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 4  130.117.3.45  11.95 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 5  154.54.58.245  28.38 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 6  154.54.59.86  29.26 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 7  154.54.59.182  35.40 ms  AS174  COGENTCO.COM 骨干网 cogentco.com
 8  154.54.36.53  41.24 ms  AS174  德国 黑森州 法兰克福 cogentco.com
 9  154.54.37.30  41.15 ms  AS174  德国 黑森州 法兰克福 cogentco.com
10  154.25.9.46  41.63 ms  AS174  德国 黑森州 法兰克福 cogentco.com
11  149.14.68.166  45.49 ms  AS174  德国 黑森州 法兰克福 cogentco.com
12  *
13  62.33.207.217  82.86 ms  AS20485  俄罗斯 莫斯科 ttk.ru
14  80.237.46.177  78.33 ms  AS20485  俄罗斯 ttk.ru
15  217.150.32.243  84.57 ms  AS20485  俄罗斯 莫斯科 ttk.ru
16  *
17  217.150.32.2  79.06 ms  AS20485  俄罗斯 莫斯科 ttk.ru


路由追踪到 俄罗斯莫斯科MTS (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 195.34.53.186 (195.34.53.186), 30 hops max, 60 byte packets
 1  178.17.170.1  0.32 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 2  193.239.165.2  8.40 ms  AS43289  摩尔多瓦 基希讷乌 trabia.com
 3  62.115.153.6  9.35 ms  AS1299  TELIA.COM 骨干网 telia.com
 4  62.115.119.116  68.30 ms  AS1299  TELIA.COM 骨干网 telia.com
 5  62.115.139.208  75.14 ms  AS1299  TELIA.COM 骨干网 telia.com
 6  62.115.115.59  67.75 ms  AS1299  瑞典 斯德哥尔摩省 斯德哥尔摩 telia.com
 7  80.91.246.85  66.08 ms  AS1299  芬兰 新地区 赫尔辛基 telia.com
 8  62.115.151.195  91.20 ms  AS1299  TELIA.COM 骨干网 telia.com
 9  212.188.29.110  99.29 ms  AS8359  俄罗斯 圣彼得堡 mts.ru
10  212.188.2.54  106.29 ms  AS8359  俄罗斯 莫斯科 mts.ru
11  212.188.28.137  101.15 ms  AS8359  俄罗斯 伊万诺沃州 伊万诺沃 mts.ru
12  195.34.53.186  104.94 ms  AS8359  俄罗斯 莫斯科 mts.ru


 -> 路由追踪测试 (IPV6)

路由追踪到 北京联通-IPV6 (ICMP 模式, 最大 30 跃点)
============================================================
traceroute to 2408:80f0:4100:2005::3 (2408:80f0:4100:2005::3), 30 hops max, 60 byte packets
 1  2a00:1dc0:cafe::1  0.75 ms  AS43289  摩尔多瓦 trabia.com
 2  2001:978:2:ad::8:1  1.07 ms  AS174  欧洲地区 cogentco.com
 3  2001:550:0:1000::8275:309a  8.29 ms  AS174  美国 cogentco.com
 4  2001:550:0:1000::8275:32d  12.24 ms  AS174  美国 cogentco.com
 5  *
 6  2001:550:0:1000::9a36:3b69  33.42 ms  AS174  美国 cogentco.com
 7  2001:550:0:1000::8275:1cd  41.88 ms  AS174  美国 cogentco.com
 8  *
 9  2001:550:0:1000::9a36:385d  57.87 ms  AS174  美国 cogentco.com
10  *
11  2001:550:0:1000::421c:4b6  125.17 ms  AS174  美国 cogentco.com
12  2600:802:3ff::1  124.46 ms  AS701  美国 verizon.com
13  2600:80a::13  176.08 ms  AS701  美国 verizon.com
14  *
15  *
16  *
17  *
18  2408:8000:2:685::  456.59 ms  AS4837  中国 联通
19  2408:8000:1100:31f::3  455.96 ms  AS4808  中国 北京 联通
20  2408:8000:1120:291::3  458.10 ms  AS4808  中国 北京 联通
21  2408:8000:1f10:3d01::3  456.57 ms  AS4808  中国 北京 联通
22  2408:80f0:4100:2006::1  453.73 ms  AS4808  中国 北京 联通
23  2408:80f0:4100:2006::b  455.56 ms  AS4808  中国 北京 联通
24  *
25  2408:80f0:4100:2005::3  459.35 ms  AS4808  中国 北京 联通

路由追踪到 北京电信-IPV6 (ICMP 模式, 最大 30 跃点)
============================================================
traceroute to 240e:0:a::c9:1cb4 (240e:0:a::c9:1cb4), 30 hops max, 60 byte packets
 1  2a00:1dc0:cafe::1  0.64 ms  AS43289  摩尔多瓦 trabia.com
 2  2001:978:2:ad::8:1  2.08 ms  AS174  欧洲地区 cogentco.com
 3  2001:550:0:1000::8275:309a  4.46 ms  AS174  美国 cogentco.com
 4  2001:550:0:1000::9a36:3af1  12.72 ms  AS174  美国 cogentco.com
 5  2001:550:0:1000::9a36:3af5  28.49 ms  AS174  美国 cogentco.com
 6  2001:550:0:1000::9a36:3b56  29.30 ms  AS174  美国 cogentco.com
 7  2001:550:0:1000::9a36:3a05  35.52 ms  AS174  美国 cogentco.com
 8  *
 9  *
10  *
11  240e:0:a::cc:5ab4  346.51 ms  AS4134  中国 电信
12  240e:0:a::c9:5b20  384.78 ms  AS4134  中国 电信
13  240e:0:a::c9:1cb4  382.99 ms  AS4134  中国 电信

路由追踪到 北京移动-IPV6 (ICMP 模式, 最大 30 跃点)
============================================================
traceroute to 2409:8080:0:2:103:1b1:0:1 (2409:8080:0:2:103:1b1:0:1), 30 hops max, 60 byte packets
 1  2a00:1dc0:cafe::1  0.59 ms  AS43289  摩尔多瓦 trabia.com
 2  2001:978:2:ad::8:1  0.56 ms  AS174  欧洲地区 cogentco.com
 3  2001:550:0:1000::8275:309a  4.28 ms  AS174  美国 cogentco.com
 4  2001:550:0:1000::9a36:3af1  12.41 ms  AS174  美国 cogentco.com
 5  2001:550:0:1000::9a36:3af5  28.39 ms  AS174  美国 cogentco.com
 6  2001:550:0:1000::9a36:3b61  33.73 ms  AS174  美国 cogentco.com
 7  *
 8  2001:550:0:1000::9a36:26cd  50.95 ms  AS174  美国 cogentco.com
 9  *
10  2001:550:0:1000::9a36:3aae  58.20 ms  AS174  美国 cogentco.com
11  2001:550:0:1000::9a36:3d06  57.92 ms  AS174  美国 cogentco.com
12  2001:978:2:21::bb:2  61.84 ms  AS174  欧洲地区 cogentco.com
13  2402:4f00:2000:100::cd  51.82 ms  AS58453  中国 香港 移动
14  2402:4f00:2000:100::156  274.20 ms  AS58453  中国 香港 移动
15  2409:8080:0:4:2f1:291::  274.99 ms  AS9808  中国 移动
16  *
17  *
18  *
19  *
20  *
21  *
22  *
23  *
24  *
25  *
26  *
27  *
28  *
29  *
30  *

路由追踪到 北京教育网CERNET2-IPV6 (ICMP 模式, 最大 30 跃点)
============================================================
traceroute to 2001:da8:a0:1001::1 (2001:da8:a0:1001::1), 30 hops max, 60 byte packets
 1  2a00:1dc0:cafe::1  0.42 ms  AS43289  摩尔多瓦 trabia.com
 2  2a00:1dc0:ffff:aa0a::2  37.96 ms  AS43289  摩尔多瓦 trabia.com
 3  2001:7f8:64:225::6939:1  9.25 ms  *  罗马尼亚 interlan.ro
 4  2001:470:0:405::1  20.86 ms  AS6939  美国 he.net
 5  2001:470:0:365::1  25.53 ms  AS6939  美国 he.net
 6  2001:470:0:3f4::1  40.01 ms  AS6939  美国 he.net
 7  *
 8  2001:470:0:299::1  116.30 ms  AS6939  美国 he.net
 9  2001:470:0:324::2  171.31 ms  AS6939  美国 he.net
10  2001:470:0:72::2  170.27 ms  AS6939  美国 he.net
11  *
12  2001:252:0:302::1  323.96 ms  AS23911  中国 北京 教育网
13  *
14  2001:252:0:1::1  324.74 ms  AS23911  中国 北京 教育网
15  2001:da8:a0:1001::1  325.14 ms  AS23910  中国 国家网络中心 教育网

 Generated by LemonBench on 2019-10-05T18:07:32Z Version 20190917 BetaVersion *Unstable*
