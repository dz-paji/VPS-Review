===
来自： HostEvaluate
===
 LemonBench Linux System Benchmark Utility Version 20190610 BetaVersion *Unstable* 
 
 测试开始时间：	2019-06-13 10:46:34
 测试结束时间：	2019-06-13 11:10:02
 测试模式：	全面测试
 
-> 系统信息
 
 系统名称:		 6.8 (x86_64)
 CPU型号:		Intel(R) Xeon(R) CPU E5-2630 v3 @ 2.40GHz
 CPU缓存大小:		20480 KB
 CPU数量:		1 vCPU
 虚拟化类型:		hyperv
 内存使用率:		161.46 MB / 966.63 MB
 Swap使用率:		0 KB / 4.00 GB
 引导设备:		/dev/mapper/vg_kuroha-lv_root
 系统负载(1/5/15min):	0.53 0.15 0.07 

 -> 网络信息

 IPV4 - 本机IP:		[MY] 103.106.*.*
 IPV4 - ASN信息:	AS55720 (Gigabit Hosting Sdn Bhd)
 IPV4 - 归属地:		Malaysia, Kuala Lumpur, Kuala Lumpur

 -> CPU性能测试 (标准模式, 3-Pass @ 30sec)

 1 线程测试:	708 分

 -> 内存性能测试 (标准模式, 3-Pass @ 30sec)

 1 线程测试-顺序读:	182.89K ops (170.33 MB/s)
 1 线程测试-顺序写:	183.08K ops (170.51 MB/s)
 1 线程测试-随机读:	164.05K ops (152.78 MB/s)
 1 线程测试-随机写:	159.70K ops (148.73 MB/s)

 -> 磁盘性能测试 (4K块/1M块, Direct写入)

 10MB-4K块		4.7 MB/s (1158 IOPS, 2.21 秒)		4.9 MB/s (1197 IOPS, 2.14 秒)
 10MB-1M块		565 MB/s (538 IOPS, 0.02 秒)		650 MB/s (619 IOPS, 0.02 秒)
 100MB-4K块		5.1 MB/s (1242 IOPS, 20.60 秒)		4.9 MB/s (1203 IOPS, 21.27 秒)
 100MB-1M块		301 MB/s (286 IOPS, 0.35 秒)		708 MB/s (675 IOPS, 0.15 秒)
 1000MB-4K块		5.4 MB/s (1323 IOPS, 193.41 秒)		5.5 MB/s (1336 IOPS, 191.49 秒)
 1000MB-1M块		1.1 GB/s (1068 IOPS, 0.94 秒)		1.1 GB/s (1062 IOPS, 0.94 秒)

-> Speedtest.net 网速测试

 距离最近测速点		1.22 MB/s	7.04 MB/s	6.992 ms
 M测试节点		 MB/s	 MB/s	Failed ms
 东北-吉林联通		 MB/s	 MB/s	No ms
 华北-山东联通		 MB/s	 MB/s	No ms
 华中-杭州电信		0.91 MB/s	0.91 MB/s	251.696 ms
 华东-上海联通		0.25 MB/s	1.12 MB/s	139.581 ms
 华南-广东电信		1.14 MB/s	1.33 MB/s	262.701 ms
 华南-杭州移动		 MB/s	 MB/s	No ms
 西南-重庆联通		1.00 MB/s	1.97 MB/s	129.14 ms
 西南-南宁移动		 MB/s	 MB/s	No ms
 西北-兰州电信		1.02 MB/s	0.68 MB/s	322.19 ms

 -> 路由追踪测试 (IPV4)


路由追踪到 北京联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 123.125.99.1 (123.125.99.1), 30 hops max, 60 byte packets
 1  103.212.69.66  0.87 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  103.106.248.17  7.37 ms  *  马来西亚 1maxhosting.com
 4  59.43.250.85  6.74 ms  AS4809  新加坡 电信
 5  59.43.188.233  83.10 ms  AS4809  中国 电信
 6  *
 7  202.97.53.217  240.60 ms  AS4134  中国 北京 电信
 8  *
 9  *
10  *
11  219.158.4.157  96.73 ms  AS4837  中国 北京 联通
12  202.96.12.94  89.82 ms  AS4808  中国 北京 联通
13  *
14  61.148.158.102  89.15 ms  AS4808  中国 北京 联通
15  61.135.113.158  90.42 ms  AS4808  中国 北京 联通
16  *
17  *
18  123.125.99.1  94.06 ms  AS4808  中国 北京 联通


路由追踪到 北京电信 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 180.149.128.1 (180.149.128.1), 30 hops max, 60 byte packets
 1  103.212.69.66  0.74 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  103.106.248.17  8.44 ms  *  马来西亚 1maxhosting.com
 4  59.43.186.137  8.10 ms  AS4809  新加坡 电信
 5  59.43.246.229  80.62 ms  AS4809  中国 北京 电信
 6  *
 7  202.97.58.121  218.04 ms  AS4134  中国 北京 电信
 8  202.97.94.181  228.95 ms  AS4134  中国 北京 电信
 9  *
10  180.149.128.1  229.37 ms  AS23724  中国 北京 电信


路由追踪到 北京移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.136.88.117 (211.136.88.117), 30 hops max, 60 byte packets
 1  103.212.69.66  0.57 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.83 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.85 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  9.78 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.41 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  8.62 ms  AS24218  新加坡 globaltransit.net
 8  58453.sgw.equinix.com (27.111.228.221)  12.30 ms  AS7713,AS18403,AS64050  新加坡 equinix.com
 9  *
10  *
11  *
12  *
13  *
14  *
15  *
16  *
17  *
18  *
19  211.136.88.117  76.33 ms  AS56048  中国 北京 移动


路由追踪到 上海联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 58.247.0.2 (58.247.0.2), 30 hops max, 60 byte packets
 1  103.212.69.66  1.72 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  73.92 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-6.r21.sngpsi07.sg.bb.gin.ntt.net (129.250.3.51)  98.98 ms  AS2914  新加坡 ntt.com
 5  ae-7.r20.sngpsi07.sg.bb.gin.ntt.net (129.250.3.74)  73.35 ms  AS2914  新加坡 ntt.com
 6  ae-1.r25.osakjp02.jp.bb.gin.ntt.net (129.250.2.67)  79.22 ms  AS2914  日本 大阪府 大阪 ntt.com
 7  ae-2.r02.osakjp02.jp.bb.gin.ntt.net (129.250.2.128)  76.29 ms  AS2914  日本 大阪府 大阪 ntt.com
 8  *
 9  219.158.113.118  129.62 ms  AS4837  中国 上海 联通
10  219.158.113.113  133.52 ms  AS4837  中国 上海 联通
11  139.226.225.186  135.11 ms  AS17621  中国 上海 联通
12  112.64.249.158  126.53 ms  AS17621  中国 上海 联通
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


路由追踪到 上海电信 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 180.153.28.1 (180.153.28.1), 30 hops max, 60 byte packets
 1  103.212.69.66  0.78 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  103.106.248.17  7.40 ms  *  马来西亚 1maxhosting.com
 4  59.43.250.85  7.65 ms  AS4809  新加坡 电信
 5  59.43.189.201  49.69 ms  AS4809  中国 广东 广州 电信
 6  *
 7  *
 8  *
 9  202.97.94.129  199.25 ms  AS4134  中国 广东 广州 电信
10  101.95.207.14  506.80 ms  AS4812  中国 上海 电信
11  124.74.166.14  229.96 ms  AS4812  中国 上海 电信
12  124.74.232.54  213.39 ms  AS4812  中国 上海 电信
13  101.227.255.38  207.02 ms  AS4812  中国 上海 电信
14  *
15  180.153.28.1  251.27 ms  AS4812  中国 上海 电信


路由追踪到 上海移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.136.97.65 (211.136.97.65), 30 hops max, 60 byte packets
 1  103.212.69.66  1.05 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.95 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.47 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  9.13 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.80 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  8.79 ms  AS24218  新加坡 globaltransit.net
 8  58453.sgw.equinix.com (27.111.228.221)  8.73 ms  AS7713,AS18403,AS64050  新加坡 equinix.com
 9  223.118.3.117  42.32 ms  AS58453  中国 香港 移动
10  *
11  *
12  221.183.25.193  80.56 ms  AS9808  中国 上海 移动
13  221.176.17.177  75.44 ms  AS9808  中国 上海 移动
14  221.183.26.82  112.49 ms  AS9808  中国 上海 移动
15  211.136.190.194  111.52 ms  AS24400  中国 上海 移动
16  211.136.97.65  109.75 ms  AS24400  中国 上海 移动


路由追踪到 广州联通 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.21.4.130 (210.21.4.130), 30 hops max, 60 byte packets
 1  103.212.69.66  0.94 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.09 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  73.44 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  85.87 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-9.r26.tokyjp05.jp.bb.gin.ntt.net (129.250.2.10)  83.80 ms  AS2914  日本 东京都 东京 ntt.com
 7  219.158.42.5  142.15 ms  AS4837  中国 广东 广州 联通
 8  219.158.103.37  156.24 ms  AS4837  中国 广东 广州 联通
 9  219.158.8.117  156.13 ms  AS4837  中国 广东 广州 联通
10  120.86.0.182  124.22 ms  AS17816  中国 广东 广州 联通
11  120.80.175.78  151.19 ms  AS17622  中国 广东 广州 联通
12  gz1-dns.gdgz.cncnet.net (210.21.4.130)  156.10 ms  AS17622  中国 广东 广州 联通


路由追踪到 广州电信 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 121.14.50.65 (121.14.50.65), 30 hops max, 60 byte packets
 1  103.212.69.66  1.29 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  103.106.248.17  7.92 ms  *  马来西亚 1maxhosting.com
 4  59.43.186.137  14.37 ms  AS4809  新加坡 电信
 5  59.43.189.205  48.19 ms  AS4809  中国 广东 广州 电信
 6  *
 7  *
 8  202.97.94.125  205.57 ms  AS4134  中国 广东 广州 电信
 9  113.96.0.101  205.68 ms  AS58466  中国 广东 广州 电信
10  121.14.50.65  193.14 ms  AS58466  中国 广东 广州 电信


路由追踪到 广州移动 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.139.129.5 (211.139.129.5), 30 hops max, 60 byte packets
 1  103.212.69.66  2.31 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.37 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.65 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  13.03 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.15 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  10.30 ms  AS24218  新加坡 globaltransit.net
 8  58453.sgw.equinix.com (27.111.228.221)  10.37 ms  AS7713,AS18403,AS64050  新加坡 equinix.com
 9  *
10  *
11  *
12  221.183.55.90  43.56 ms  AS9808  中国 广东 广州 移动
13  221.176.24.141  43.58 ms  AS9808  中国 广东 广州 移动
14  221.176.24.5  46.07 ms  AS9808  中国 广东 广州 移动
15  *
16  120.198.206.198  48.30 ms  AS56040  中国 广东 广州 移动
17  211.139.129.5  66.85 ms  AS56040  中国 广东 广州 移动


路由追踪到 美国洛杉矶-Cloudcone [MultaCom机房] (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 173.82.149.19 (173.82.149.19), 30 hops max, 60 byte packets
 1  103.212.69.66  0.51 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.72 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  72.91 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  71.58 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-0.r31.tokyjp05.jp.bb.gin.ntt.net (129.250.5.22)  85.05 ms  AS2914  日本 东京都 东京 ntt.com
 7  ae-4.r23.lsanca07.us.bb.gin.ntt.net (129.250.3.193)  180.83 ms  AS2914  美国 加利福尼亚州 洛杉矶 ntt.com
 8  ae-2.r00.lsanca07.us.bb.gin.ntt.net (129.250.3.238)  186.14 ms  AS2914  美国 加利福尼亚州 洛杉矶 ntt.com
 9  ae-0.a00.lsanca07.us.bb.gin.ntt.net (129.250.2.104)  183.26 ms  AS2914  美国 加利福尼亚州 洛杉矶 ntt.com
10  ae-0.multacom.lsanca07.us.bb.gin.ntt.net (129.250.205.122)  195.14 ms  AS2914  美国 加利福尼亚州 洛杉矶 ntt.com
11  be3-1.cr3.lax.multacom.com (208.64.231.5)  214.81 ms  AS35916  美国 加利福尼亚州 洛杉矶 multacom.com
12  18-149-82-173-dedicated.multacom.com (173.82.149.18)  197.28 ms  AS35916  美国 加利福尼亚州 洛杉矶 multacom.com
13  19-149-82-173-dedicated.multacom.com (173.82.149.19)  188.41 ms  AS35916  美国 加利福尼亚州 洛杉矶 multacom.com


路由追踪到 美国达拉斯-SubnetLabs [Incero机房] (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 162.212.59.219 (162.212.59.219), 30 hops max, 60 byte packets
 1  103.212.69.66  0.60 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.90 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.63 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  11.78 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  9.31 ms  AS24218  新加坡 globaltransit.net
 7  ae-12.br-gw-1-sin-pip.sg.globaltransit.net (124.158.225.14)  9.11 ms  AS24218  新加坡 globaltransit.net
 8  v1005.core1.sin1.he.net (74.82.49.13)  8.29 ms  AS6939  新加坡 he.net
 9  100ge16-2.core1.tyo1.he.net (184.105.64.254)  74.89 ms  AS6939  日本 东京都 东京 he.net
10  100ge8-2.core1.lax2.he.net (184.105.65.9)  184.36 ms  AS6939  美国 加利福尼亚州 洛杉矶 he.net
11  100ge4-1.core1.phx2.he.net (184.105.81.178)  190.03 ms  AS6939  美国 亚利桑那州 凤凰城 he.net
12  100ge10-1.core1.dal1.he.net (184.105.81.174)  208.78 ms  AS6939  美国 德克萨斯州 达拉斯 he.net
13  *
14  *
15  Dallas-TX.r10.Public.Pwr-1xPDU-1xATS-2xUPS.incero.com (144.168.34.46)  210.29 ms  AS54540  美国 德克萨斯州 达拉斯 incero.com
16  incero.com (162.212.59.219)  209.29 ms  AS54540  美国 德克萨斯州 达拉斯 incero.com


路由追踪到 美国洛杉矶-QuadraNet [QuadraNet机房] (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 198.55.111.55 (198.55.111.55), 30 hops max, 60 byte packets
 1  103.212.69.66  0.38 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.11 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.61 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  12.39 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.78 ms  AS24218  新加坡 globaltransit.net
 7  ae-12.br-gw-1-sin-pip.sg.globaltransit.net (124.158.225.14)  8.99 ms  AS24218  新加坡 globaltransit.net
 8  v1005.core1.sin1.he.net (74.82.49.13)  8.18 ms  AS6939  新加坡 he.net
 9  100ge16-2.core1.tyo1.he.net (184.105.64.254)  74.69 ms  AS6939  日本 东京都 东京 he.net
10  100ge8-2.core1.lax2.he.net (184.105.65.9)  183.88 ms  AS6939  美国 加利福尼亚州 洛杉矶 he.net
11  100ge2-2.core1.lax1.he.net (72.52.92.121)  181.98 ms  AS6939  美国 加利福尼亚州 洛杉矶 he.net
12  *
13  colo-lax8.as8100.net (96.44.180.42)  184.31 ms  AS8100  美国 加利福尼亚州 洛杉矶 quadranet.com
14  *
15  www.quadranet.com (198.55.111.55)  181.95 ms  AS8100  美国 加利福尼亚州 洛杉矶 quadranet.com


路由追踪到 美国新泽西-ColoCrossing [ColoCrossing机房] (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 23.95.99.2 (23.95.99.2), 30 hops max, 60 byte packets
 1  103.212.69.66  0.39 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.28 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  79.54 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  85.31 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-3.r22.sttlwa01.us.bb.gin.ntt.net (129.250.4.142)  189.55 ms  AS2914  美国 华盛顿州 西雅图 ntt.com
 7  ae-0.r24.nycmny01.us.bb.gin.ntt.net (129.250.4.14)  231.86 ms  AS2914  美国 纽约州 纽约 ntt.com
 8  ae-1.r08.nycmny01.us.bb.gin.ntt.net (129.250.5.62)  241.05 ms  AS2914  美国 纽约州 纽约 ntt.com
 9  ae-0.a02.nycmny01.us.bb.gin.ntt.net (129.250.6.51)  229.94 ms  AS2914  美国 纽约州 纽约 ntt.com
10  ae-0.choopa.nycmny01.us.bb.gin.ntt.net (128.241.2.202)  220.57 ms  AS2914  美国 纽约州 纽约 ntt.com
11  *
12  *
13  *
14  host.colocrossing.com (23.95.99.2)  231.18 ms  AS36352  美国 新泽西州 皮斯卡特维 colocrossing.com


路由追踪到 美国俄勒冈-MivoCloud (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 94.158.244.1 (94.158.244.1), 30 hops max, 60 byte packets
 1  103.212.69.66  0.37 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.18 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  93.11 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  73.40 ms  AS2914  日本 东京都 东京 ntt.com
 6  *
 7  ae-28.r05.sttlwa01.us.bb.gin.ntt.net (129.250.2.45)  194.68 ms  AS2914  美国 华盛顿州 西雅图 ntt.com
 8  ge-100-0-0-6.r05.sttlwa01.us.ce.gin.ntt.net (129.250.193.130)  159.57 ms  AS2914  美国 华盛顿州 西雅图 ntt.com
 9  ge-5-0-0.c1.bend1.or.bendtel.net (66.39.191.9)  167.91 ms  AS27008  美国 俄勒冈州 本德 bendtel.com
10  ge-1-1-9.car1.bend.cascadedivide.net (66.39.167.30)  164.03 ms  AS27008  美国 俄勒冈州 本德 bendtel.com
11  v150.cr2.bend.us.mivocloud.com (94.158.244.1)  176.97 ms  AS39798  美国 俄勒冈州 本德 mivocloud.com


路由追踪到 美国拉斯维加斯-BuyVM [Cogentco机房] (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 209.141.32.12 (209.141.32.12), 30 hops max, 60 byte packets
 1  103.212.69.66  0.95 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.21 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  9.45 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  13.04 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.92 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  8.46 ms  AS24218  新加坡 globaltransit.net
 8  *
 9  100ge16-2.core1.tyo1.he.net (184.105.64.254)  74.47 ms  AS6939  日本 东京都 东京 he.net
10  100ge8-2.core1.lax2.he.net (184.105.65.9)  206.21 ms  AS6939  美国 加利福尼亚州 洛杉矶 he.net
11  ve990.core2.las1.he.net (184.105.222.162)  190.40 ms  AS6939  美国 内华达州 拉斯维加斯 he.net
12  *
13  209.141.32.12  182.63 ms  AS53667  美国 内华达州 拉斯维加斯 buyvm.net


路由追踪到 美国达拉斯-LetBox [GTT机房] (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 185.215.227.2 (185.215.227.2), 30 hops max, 60 byte packets
 1  103.212.69.66  1.41 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.35 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  72.71 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  73.36 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-4.r23.snjsca04.us.bb.gin.ntt.net (129.250.5.78)  200.10 ms  AS2914  美国 加利福尼亚州 圣何塞 ntt.com
 7  ae-7.r23.dllstx09.us.bb.gin.ntt.net (129.250.4.155)  236.10 ms  AS2914  美国 德克萨斯州 达拉斯 ntt.com
 8  ae-6.r10.dllstx09.us.bb.gin.ntt.net (129.250.5.4)  225.37 ms  AS2914  美国 德克萨斯州 达拉斯 ntt.com
 9  ce-0-17-0-2.r10.dllstx09.us.ce.gin.ntt.net (128.241.2.198)  211.69 ms  AS2914  美国 德克萨斯州 达拉斯 ntt.com
10  *
11  dl02.letbox.net (185.215.227.2)  205.68 ms  AS40676  美国 德克萨斯州 达拉斯 letbox.com


路由追踪到 美国旧金山-DigitalOcean SFO2 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to speedtest-sfo2.digitalocean.com (165.227.29.84), 30 hops max, 60 byte packets
 1  103.212.69.66  0.40 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  73.96 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  75.95 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  85.13 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-4.r23.snjsca04.us.bb.gin.ntt.net (129.250.5.78)  188.28 ms  AS2914  美国 加利福尼亚州 圣何塞 ntt.com
 7  ae-45.r01.snjsca04.us.bb.gin.ntt.net (129.250.3.175)  178.01 ms  AS2914  美国 加利福尼亚州 圣何塞 ntt.com
 8  ae-4.r05.plalca01.us.bb.gin.ntt.net (129.250.5.32)  180.10 ms  AS2914  美国 加利福尼亚州 帕洛阿尔托 ntt.com
 9  *
10  *
11  *
12  165.227.29.84  173.03 ms  AS14061  美国 加利福尼亚州 旧金山 digitalocean.com


路由追踪到 美国洛杉矶-Vultr (TCP 模式, 最大 30 跃点)
============================================================
traceroute to lax-ca-us-ping.vultr.com (108.61.219.200), 30 hops max, 60 byte packets
 1  103.212.69.66  0.89 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  7.21 ms  AS4637,AS10026  新加坡 telstra.com
 4  202.84.219.182  7.62 ms  AS4637,AS10026  TELSTRA.COM 骨干网 telstra.com
 5  ae1-105.cr0-sin1.ip4.gtt.net (183.182.80.169)  7.54 ms  AS3257,AS8928  新加坡 gtt.net
 6  89.149.129.234  187.17 ms  AS3257,AS8928  美国 加利福尼亚州 洛杉矶 gtt.net
 7  as20473-gw.lax20.ip4.gtt.net (173.205.58.194)  174.45 ms  AS3257,AS8928  美国 加利福尼亚州 洛杉矶 gtt.net
 8  *
 9  *
10  108.61.219.200.vultr.com (108.61.219.200)  174.13 ms  AS20473  美国 加利福尼亚州 洛杉矶 choopa.com


路由追踪到 美国新泽西-Vultr (TCP 模式, 最大 30 跃点)
============================================================
traceroute to nj-us-ping.vultr.com (108.61.149.182), 30 hops max, 60 byte packets
 1  103.212.69.66  0.45 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  8.33 ms  AS4637,AS10026  新加坡 telstra.com
 4  202.84.219.182  7.42 ms  AS4637,AS10026  TELSTRA.COM 骨干网 telstra.com
 5  ae1-105.cr0-sin1.ip4.gtt.net (183.182.80.169)  6.62 ms  AS3257,AS8928  新加坡 gtt.net
 6  et-1-0-31.cr2-nyc4.ip4.gtt.net (213.200.114.150)  233.30 ms  AS3257,AS8928  美国 纽约州 纽约 gtt.net
 7  ip4.gtt.net (173.205.45.234)  218.59 ms  AS3257,AS8928  美国 gtt.net
 8  *
 9  *
10  *
11  108.61.149.182.vultr.com (108.61.149.182)  216.94 ms  AS20473  美国 新泽西州 皮斯卡特维 choopa.com


路由追踪到 美国洛杉矶-CeraNetworks (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 23.224.2.1 (23.224.2.1), 30 hops max, 60 byte packets
 1  103.212.69.66  1.12 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.70 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.85 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  10.57 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.12 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  8.40 ms  AS24218  新加坡 globaltransit.net
 8  *
 9  100ge16-2.core1.tyo1.he.net (184.105.64.254)  75.59 ms  AS6939  日本 东京都 东京 he.net
10  100ge8-2.core1.lax2.he.net (184.105.65.9)  181.51 ms  AS6939  美国 加利福尼亚州 洛杉矶 he.net
11  23.225.225.182  181.55 ms  AS40065  美国 加利福尼亚州 洛杉矶 cloudradium.com
12  23.225.225.221  181.11 ms  AS40065  美国 加利福尼亚州 洛杉矶 cloudradium.com
13  *
14  23.225.225.194  174.99 ms  AS40065  美国 加利福尼亚州 洛杉矶 cloudradium.com
15  23.224.2.1  181.93 ms  AS40065  美国 加利福尼亚州 洛杉矶 cloudradium.com


路由追踪到 德国法兰克福-acclerated.de (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 84.200.17.68 (84.200.17.68), 30 hops max, 60 byte packets
 1  103.212.69.66  1.53 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.60 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.58 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  11.67 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.87 ms  AS24218  新加坡 globaltransit.net
 7  ae-12.br-gw-1-sin-pip.sg.globaltransit.net (124.158.225.14)  9.42 ms  AS24218  新加坡 globaltransit.net
 8  v1005.core1.sin1.he.net (74.82.49.13)  8.15 ms  AS6939  新加坡 he.net
 9  100ge11-1.core1.mrs1.he.net (184.105.65.14)  145.19 ms  AS6939  法国 普罗旺斯－阿尔卑斯－蓝色海岸大区 马赛 he.net
10  100ge6-1.core1.mil2.he.net (184.105.80.13)  152.90 ms  AS6939  意大利 伦巴第大区 米兰广域市 he.net
11  100ge5-2.core1.zrh2.he.net (184.105.65.33)  155.36 ms  AS6939  瑞士 苏黎世州 苏黎世 he.net
12  100ge15-1.core1.fra1.he.net (184.105.65.30)  160.55 ms  AS6939  德国 黑森州 法兰克福 he.net
13  *
14  decix.accelerated.de (84.200.230.1)  161.11 ms  AS31400  德国 黑森州 法兰克福 accelerated.de
15  84.200.230.85  161.14 ms  AS31400  德国 黑森州 法兰克福 accelerated.de
16  84.200.17.68  161.48 ms  AS31400  德国 黑森州 法兰克福 accelerated.de


路由追踪到 德国法兰克福-DigitalOcean FRA1 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to speedtest-fra1.digitalocean.com (46.101.218.147), 30 hops max, 60 byte packets
 1  103.212.69.66  1.31 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  80.24 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-8.r21.sngpsi07.sg.bb.gin.ntt.net (129.250.2.168)  75.08 ms  AS2914  新加坡 ntt.com
 5  ae-7.r20.sngpsi07.sg.bb.gin.ntt.net (129.250.3.74)  73.23 ms  AS2914  新加坡 ntt.com
 6  ae-4.r24.frnkge08.de.bb.gin.ntt.net (129.250.7.62)  251.93 ms  AS2914  德国 黑森州 法兰克福 ntt.com
 7  ae-1.r04.frnkge08.de.bb.gin.ntt.net (129.250.3.218)  265.22 ms  AS2914  德国 黑森州 法兰克福 ntt.com
 8  ce-0-7-0-3.r04.frnkge08.de.ce.gin.ntt.net (168.143.229.54)  182.87 ms  AS2914  德国 黑森州 法兰克福 ntt.com
 9  *
10  46.101.218.147  175.56 ms  AS14061  德国 黑森州 法兰克福 digitalocean.com


路由追踪到 德国法兰克福-Hetzener (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 195.201.65.92 (195.201.65.92), 30 hops max, 60 byte packets
 1  103.212.69.66  1.89 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.81 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-8.r21.sngpsi07.sg.bb.gin.ntt.net (129.250.2.168)  74.85 ms  AS2914  新加坡 ntt.com
 5  ae-7.r20.sngpsi07.sg.bb.gin.ntt.net (129.250.3.74)  73.29 ms  AS2914  新加坡 ntt.com
 6  ae-4.r24.frnkge08.de.bb.gin.ntt.net (129.250.7.62)  253.91 ms  AS2914  德国 黑森州 法兰克福 ntt.com
 7  ae-13.r03.frnkge03.de.bb.gin.ntt.net (129.250.6.207)  254.49 ms  AS2914  德国 黑森州 法兰克福 ntt.com
 8  213.198.82.130  180.81 ms  AS2914  德国 黑森州 法兰克福 ntt.com
 9  core11.nbg1.hetzner.com (213.239.252.22)  181.83 ms  AS24940  德国 巴伐利亚州 纽伦堡 hetzner.de
10  spine2.cloud1.nbg1.hetzner.com (85.10.250.214)  206.52 ms  AS24940  德国 巴伐利亚州 纽伦堡 hetzner.de
11  *
12  10801.your-cloud.host (195.201.65.92)  190.36 ms  AS24940  德国 巴伐利亚州 纽伦堡 hetzner.de


路由追踪到 法国-OVH (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 149.202.203.96 (149.202.203.96), 30 hops max, 60 byte packets
 1  103.212.69.66  0.94 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  7.47 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-93.sgpl-core02.telstraglobal.net (202.84.224.189)  10.61 ms  AS4637  新加坡 telstra.com
 5  i-15150.sgcn-core01.telstraglobal.net (202.84.140.165)  8.15 ms  AS4637  新加坡 telstra.com
 6  i-10851.eqnx-core02.telstraglobal.net (202.84.136.2)  179.16 ms  AS4637  美国 加利福尼亚州 圣何塞 telstra.com
 7  i-0-0-0-1.paix-core02.telstraglobal.net (202.84.143.210)  178.64 ms  AS4637,AS10026  美国 加利福尼亚州 帕洛阿尔托 telstra.com
 8  be100-104.pao-sv8-bb1-a9.ca.us (178.32.135.150)  174.56 ms  AS16276  美国 加利福尼亚州 帕洛阿尔托 ovh.com
 9  chi-5-a9.il.us (198.27.73.227)  220.10 ms  AS16276  美国 伊利诺伊州 芝加哥 ovh.com
10  be100-1320.bhs-g1-nc5.qc.ca (198.27.73.206)  237.97 ms  AS16276  加拿大 魁北克省 博阿努瓦 ovh.com
11  *
12  *
13  sbg-d1-a75.fr.eu (213.251.130.60)  255.63 ms  AS16276  法国 大东部大区 斯特拉斯堡 ovh.com
14  vl1251.sbg-g2-a75.fr.eu (37.187.232.29)  267.56 ms  AS16276  法国 大东部大区 斯特拉斯堡 ovh.com
15  8.esxi65.sbg2.nexis.it (149.202.203.96)  267.34 ms  AS16276  法国 大东部大区 斯特拉斯堡 ovh.com


路由追踪到 捷克-FinalTek (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 77.78.107.117 (77.78.107.117), 30 hops max, 60 byte packets
 1  103.212.69.66  0.94 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.57 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.25 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  14.84 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  10.56 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  9.93 ms  AS24218  新加坡 globaltransit.net
 8  *
 9  100ge11-1.core1.mrs1.he.net (184.105.65.14)  144.84 ms  AS6939  法国 普罗旺斯－阿尔卑斯－蓝色海岸大区 马赛 he.net
10  100ge6-1.core1.mil2.he.net (184.105.80.13)  160.73 ms  AS6939  意大利 伦巴第大区 米兰广域市 he.net
11  100ge10-2.core1.vie1.he.net (184.105.65.57)  162.72 ms  AS6939  奥地利 维也纳州 维也纳 he.net
12  100ge14-2.core1.prg1.he.net (72.52.92.185)  169.11 ms  AS6939  捷克 布拉格 he.net
13  216.66.84.27  169.47 ms  AS6939  捷克 布拉格 he.net
14  gw2-gransy.cas.ip-anywhere.net (81.0.255.106)  169.14 ms  AS15685  捷克 casablanca.cz
15  www.finaltek.com (77.78.107.117)  169.09 ms  AS15685  捷克 casablanca.cz


路由追踪到 波兰华沙-Nazwa.pl (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 77.55.224.12 (77.55.224.12), 30 hops max, 60 byte packets
 1  103.212.69.66  1.65 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.00 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  9.28 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  12.16 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.43 ms  AS24218  新加坡 globaltransit.net
 7  ae-12.br-gw-1-sin-pip.sg.globaltransit.net (124.158.225.14)  8.63 ms  AS24218  新加坡 globaltransit.net
 8  v1005.core1.sin1.he.net (74.82.49.13)  8.23 ms  AS6939  新加坡 he.net
 9  100ge11-1.core1.mrs1.he.net (184.105.65.14)  146.04 ms  AS6939  法国 普罗旺斯－阿尔卑斯－蓝色海岸大区 马赛 he.net
10  *
11  fra1-rr1.net.nazwa.pl (85.128.133.165)  171.46 ms  AS15967  德国 黑森州 法兰克福 nazwa.pl
12  krk1-rr1.net.nazwa.pl (85.128.133.209)  181.77 ms  AS15967  波兰 小波兰省 克拉科夫 nazwa.pl
13  waw1-rr1.net.nazwa.pl (85.128.133.241)  183.34 ms  AS15967  波兰 马佐夫舍省 华沙 nazwa.pl
14  waw1-fw1a.net.nazwa.pl (85.128.133.104)  182.15 ms  AS15967  波兰 马佐夫舍省 华沙 nazwa.pl
15  dedicated-aiq12.rev.nazwa.pl (77.55.224.12)  184.62 ms  AS15967  波兰 马佐夫舍省 华沙 nazwa.pl


路由追踪到 日本东京-IDCF (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.140.10.1 (210.140.10.1), 30 hops max, 60 byte packets
 1  103.212.69.66  1.48 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  10.32 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-91.sgcn-core01.telstraglobal.net (202.84.224.198)  10.54 ms  AS4637  新加坡 telstra.com
 5  i-15150.sgcn-core01.telstraglobal.net (202.84.140.165)  9.38 ms  AS4637  新加坡 telstra.com
 6  i-0-7-0-7.siko11.telstraglobal.net (202.47.216.250)  79.68 ms  AS4637,AS10026  日本 东京都 东京 telstra.com
 7  i-0-7-0-7.siko11.telstraglobal.net (202.47.216.250)  80.28 ms  AS4637,AS10026  日本 东京都 东京 telstra.com
 8  *
 9  101.110.27.190  82.13 ms  AS17676  日本 bbtec.net
10  *
11  *
12  *
13  158.205.188.253  82.55 ms  AS4694  日本 东京都 东京 idcf.jp
14  158.205.188.253  85.96 ms  AS4694  日本 东京都 东京 idcf.jp
15  158.205.188.174  82.29 ms  AS4694  日本 东京都 东京 idcf.jp
16  210.140.10.1  83.21 ms  AS4694  日本 东京都 idcf.jp


路由追踪到 日本大阪-BBTEC (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 203.76.245.2 (203.76.245.2), 30 hops max, 60 byte packets
 1  103.212.69.66  1.12 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  8.02 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-93.sgpl-core02.telstraglobal.net (202.84.224.189)  11.45 ms  AS4637  新加坡 telstra.com
 5  i-15150.sgcn-core01.telstraglobal.net (202.84.140.165)  8.71 ms  AS4637  新加坡 telstra.com
 6  i-0-7-0-7.siko11.telstraglobal.net (202.47.216.250)  80.56 ms  AS4637,AS10026  日本 东京都 东京 telstra.com
 7  134.159.160.178  81.25 ms  AS4637  日本 东京都 东京 telstra.com
 8  134.159.160.178  80.94 ms  AS4637  日本 东京都 东京 telstra.com
 9  27.85.136.117  82.27 ms  AS2516  日本 东京都 东京 kddi.com
10  27.85.229.41  84.50 ms  AS2516  日本 东京都 东京 kddi.com
11  111.87.11.34  86.96 ms  AS2516  日本 大阪府 大阪 kddi.com
12  111.87.11.34  88.03 ms  AS2516  日本 大阪府 大阪 kddi.com
13  *
14  *
15  203.76.245.2  87.81 ms  AS134835  日本 大阪府 大阪 tinmok.com


路由追踪到 日本大阪-XTOM (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 202.5.222.221 (202.5.222.221), 30 hops max, 60 byte packets
 1  103.212.69.66  1.17 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.31 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  72.53 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  76.55 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-2.r03.tokyjp05.jp.bb.gin.ntt.net (129.250.3.33)  86.31 ms  AS2914  日本 东京都 东京 ntt.com
 7  ae-0.a02.tokyjp05.jp.bb.gin.ntt.net (129.250.6.183)  85.86 ms  AS2914  日本 东京都 东京 ntt.com
 8  ae-0.yahoobb-tyo.tokyjp05.jp.bb.gin.ntt.net (203.105.72.82)  85.01 ms  AS2914  日本 东京都 东京 ntt.com
 9  *
10  211.15.42.254  80.25 ms  AS17676  日本 大阪府 大阪 bbtec.net
11  103.88.45.252  92.05 ms  AS23748  日本 大阪府 大阪 xtom.com
12  202.5.222.221  93.09 ms  AS4785  日本 大阪府 大阪 xtom.com


路由追踪到 日本东京-Vultr (TCP 模式, 最大 30 跃点)
============================================================
traceroute to hnd-jp-ping.vultr.com (108.61.201.151), 30 hops max, 60 byte packets
 1  103.212.69.66  1.04 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  7.92 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-93.sgpl-core02.telstraglobal.net (202.84.224.189)  8.90 ms  AS4637  新加坡 telstra.com
 5  i-10851.eqnx-core02.telstraglobal.net (202.84.136.2)  176.97 ms  AS4637  美国 加利福尼亚州 圣何塞 telstra.com
 6  i-92.eqnx03.telstraglobal.net (202.84.247.17)  177.66 ms  AS4637  美国 加利福尼亚州 圣何塞 telstra.com
 7  sjo-b21-link.telia.net (80.239.128.76)  183.88 ms  AS1299  美国 加利福尼亚州 圣何塞 telia.com
 8  ntt-ic-323771-sjo-b21.c.telia.net (62.115.12.53)  176.78 ms  AS1299  美国 加利福尼亚州 圣何塞 telia.com
 9  ntt-ic-323771-sjo-b21.c.telia.net (62.115.12.53)  176.82 ms  AS1299  美国 加利福尼亚州 圣何塞 telia.com
10  ae-21.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.5.77)  179.03 ms  AS2914  日本 东京都 东京 ntt.com
11  ae-21.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.5.77)  177.16 ms  AS2914  日本 东京都 东京 ntt.com
12  ae-2.r02.tokyjp05.jp.bb.gin.ntt.net (129.250.3.22)  178.14 ms  AS2914  日本 东京都 东京 ntt.com
13  *
14  *
15  vl516-ds1-b5-r2605.tyo1.choopa.net (43.224.32.210)  178.63 ms  AS20473  日本 东京都 东京 choopa.com
16  108.61.201.151.vultr.com (108.61.201.151)  178.96 ms  AS20473  日本 东京都 东京 choopa.com


路由追踪到 韩国首尔KT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 168.126.64.220 (168.126.64.220), 30 hops max, 60 byte packets
 1  103.212.69.66  1.56 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  72.14 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-1.r20.kslrml02.my.bb.gin.ntt.net (129.250.7.42)  72.39 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 5  ae-11.r30.tokyjp05.jp.bb.gin.ntt.net (129.250.2.25)  72.41 ms  AS2914  日本 东京都 东京 ntt.com
 6  ae-9.r26.tokyjp05.jp.bb.gin.ntt.net (129.250.2.10)  71.59 ms  AS2914  日本 东京都 东京 ntt.com
 7  xe-4.koreatelecom.tokyjp05.jp.bb.gin.ntt.net (129.250.9.230)  106.05 ms  AS2914  日本 东京都 东京 ntt.com
 8  112.174.84.137  107.79 ms  AS4766  韩国 首尔 kt.com
 9  *
10  112.174.18.126  91.12 ms  AS4766  韩国 首尔 kt.com
11  *
12  112.188.8.206  98.95 ms  AS4766  韩国 首尔 kt.com
13  61.72.11.6  93.16 ms  AS4766  韩国 首尔 kt.com
14  168.126.64.220  103.09 ms  AS4766  韩国 首尔 kt.com


路由追踪到 韩国首尔SKBroadBand (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 58.120.138.116 (58.120.138.116), 30 hops max, 60 byte packets
 1  103.212.69.66  1.13 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  7.97 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-93.sgpl-core02.telstraglobal.net (202.84.224.189)  9.82 ms  AS4637  新加坡 telstra.com
 5  202.84.141.110  38.25 ms  AS4637  TELSTRA.COM 骨干网 telstra.com
 6  202.84.153.26  37.20 ms  AS4637  中国 香港 telstra.com
 7  *
 8  58.229.92.242  82.68 ms  AS9318  韩国 skbroadband.com
 9  118.221.7.45  76.71 ms  AS9318  韩国 skbroadband.com
10  10.222.7.143  72.38 ms  *  局域网
11  10.63.252.109  73.82 ms  *  局域网
12  100.70.69.246  75.51 ms  *  共享地址
13  *
14  58.120.138.116  72.68 ms  AS9318  韩国 首尔 skbroadband.com


路由追踪到 韩国首尔LG (TCP 模式, 最大 30 跃点)
============================================================
traceroute to uplus.co.kr (210.124.165.161), 30 hops max, 60 byte packets
 1  103.212.69.66  0.36 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  8.34 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-91.sgcn-core01.telstraglobal.net (202.84.224.198)  8.87 ms  AS4637  新加坡 telstra.com
 5  202.84.141.110  38.62 ms  AS4637  TELSTRA.COM 骨干网 telstra.com
 6  202.84.141.46  73.16 ms  AS4637  TELSTRA.COM 骨干网 telstra.com
 7  202.84.141.46  74.94 ms  AS4637  TELSTRA.COM 骨干网 telstra.com
 8  210.108.16.149  71.26 ms  AS3786  韩国 uplus.co.kr
 9  1.208.107.33  173.58 ms  AS3786  韩国 首尔 uplus.co.kr
10  210.120.105.118  71.15 ms  AS3786  韩国 uplus.co.kr
11  1.208.107.121  71.83 ms  AS3786  韩国 uplus.co.kr
12  *
13  1.213.8.250  72.76 ms  AS3786  韩国 uplus.co.kr
14  1.213.8.246  73.09 ms  AS3786  韩国 uplus.co.kr
15  172.30.252.9  73.68 ms  *  局域网
16  172.30.252.20  75.10 ms  *  局域网
17  lgtairline.lgtelecom.com (210.124.165.161)  79.06 ms  AS3786  韩国 uplus.co.kr


路由追踪到 香港HKT-42段 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 42.200.128.126 (42.200.128.126), 30 hops max, 60 byte packets
 1  103.212.69.66  0.71 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.93 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  42.13 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  45.55 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  42.67 ms  AS24218  新加坡 globaltransit.net
 7  ae-10.cr-gw-1-sin-pip.sg.globaltransit.net (124.158.224.61)  41.78 ms  AS24218  新加坡 globaltransit.net
 8  xe-0-0-0-0.pp-gw-1-hkg-pip.hk.globaltransit.net (124.158.224.22)  41.61 ms  AS24218  中国 香港 globaltransit.net
 9  ims6-lacp-10g.hkix.net (123.255.91.25)  42.66 ms  AS7713,AS58879,AS64050  中国 香港 hkix.net
10  tswc9253.netvigator.com (203.198.19.253)  65.40 ms  AS4760  中国 香港 pccw.com
11  *
12  42-200-128-126.static.imsbiz.com (42.200.128.126)  45.54 ms  AS4760  中国 香港 pccw.com


路由追踪到 香港HKT-58段 (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 58.152.66.77 (58.152.66.77), 30 hops max, 60 byte packets
 1  103.212.69.66  2.05 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.56 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  41.85 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  43.15 ms  AS24218  新加坡 globaltransit.net
 6  61.11.210.97  41.27 ms  AS24218  GLOBALTRANSIT.NET 骨干网 globaltransit.net
 7  ae-2.cr-gw-1-sin-pip.sg.globaltransit.net (61.11.210.106)  42.23 ms  AS24218  新加坡 globaltransit.net
 8  xe-0-0-0-0.pp-gw-1-hkg-pip.hk.globaltransit.net (124.158.224.22)  41.70 ms  AS24218  中国 香港 globaltransit.net
 9  ims6-lacp-10g.hkix.net (123.255.91.25)  42.76 ms  AS7713,AS58879,AS64050  中国 香港 hkix.net
10  wtsc3a065.netvigator.com (218.102.40.65)  43.41 ms  AS4760  中国 香港 pccw.com
11  tswc6a228.netvigator.com (219.76.7.228)  43.37 ms  AS4760  中国 香港 pccw.com
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


路由追踪到 香港HKBN (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 61.238.140.253 (61.238.140.253), 30 hops max, 60 byte packets
 1  103.212.69.66  0.43 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.77 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  42.56 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  41.56 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  42.38 ms  AS24218  新加坡 globaltransit.net
 7  ae-10.cr-gw-1-sin-pip.sg.globaltransit.net (124.158.224.61)  41.37 ms  AS24218  新加坡 globaltransit.net
 8  xe-0-0-0-0.pp-gw-1-hkg-pip.hk.globaltransit.net (124.158.224.22)  41.37 ms  AS24218  中国 香港 globaltransit.net
 9  cti2-lacp-10g.hkix.net (123.255.90.113)  42.20 ms  AS7713,AS58879,AS64050  中国 香港 hkix.net
10  *
11  061238147140.ctinets.com (61.238.147.140)  42.68 ms  AS10103  中国 香港 hkbn.com.hk
12  061238140253.ctinets.com (61.238.140.253)  42.45 ms  AS10103  中国 香港 hkbn.com.hk


路由追踪到 香港HGC (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 118.140.65.194 (118.140.65.194), 30 hops max, 60 byte packets
 1  103.212.69.66  0.89 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  unknown.telstraglobal.net (202.127.73.209)  7.74 ms  AS4637,AS10026  新加坡 telstra.com
 4  i-91.sgcn-core01.telstraglobal.net (202.84.224.198)  12.32 ms  AS4637  新加坡 telstra.com
 5  i-15150.sgcn-core01.telstraglobal.net (202.84.140.165)  8.89 ms  AS4637  新加坡 telstra.com
 6  202.84.153.38  38.50 ms  AS4637  中国 香港 telstra.com
 7  peer.hgc.com.hk (218.189.96.53)  80.97 ms  AS9304  中国 香港 hgc.com.hk
 8  peer.hgc.com.hk (218.189.96.206)  40.55 ms  AS9304  中国 香港 hgc.com.hk
 9  218.188.28.74  62.84 ms  AS9304  中国 香港 hgc.com.hk
10  10.28.21.26  50.68 ms  *  局域网
11  10.30.28.82  47.93 ms  *  局域网
12  *
13  118.140.65.194  42.99 ms  AS9304  中国 香港 hgc.com.hk


路由追踪到 香港WTT (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 116.92.192.14 (116.92.192.14), 30 hops max, 60 byte packets
 1  103.212.69.66  1.19 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.13 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  8.35 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  10.81 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  8.66 ms  AS24218  新加坡 globaltransit.net
 7  124.158.225.22  8.66 ms  AS24218  新加坡 globaltransit.net
 8  *
 9  115.160.187.115  43.24 ms  AS9381  中国 香港 wtthk.com
10  *
11  116.92.192.13  45.82 ms  AS9381  中国 香港 wtthk.com
12  116.92.192.14  46.78 ms  AS9381  中国 香港 wtthk.com


路由追踪到 台湾HiNet (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 211.22.184.1 (211.22.184.1), 30 hops max, 60 byte packets
 1  103.212.69.66  1.06 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  94.09 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-6.r21.sngpsi07.sg.bb.gin.ntt.net (129.250.3.51)  75.70 ms  AS2914  新加坡 ntt.com
 5  ae-7.r20.sngpsi07.sg.bb.gin.ntt.net (129.250.3.74)  75.14 ms  AS2914  新加坡 ntt.com
 6  ae-9.r24.tkokhk01.hk.bb.gin.ntt.net (129.250.7.67)  78.69 ms  AS2914  中国 香港 ntt.com
 7  ae-1.r02.tkokhk01.hk.bb.gin.ntt.net (129.250.6.92)  78.49 ms  AS2914  中国 香港 ntt.com
 8  r4003-s2.tp.hinet.net (211.72.233.94)  64.51 ms  AS3462  中国 台湾 台北市 cht.com.tw
 9  r4103-s2.tp.hinet.net (220.128.3.146)  64.44 ms  AS3462  中国 台湾 台北市 cht.com.tw
10  tpdb-3021.hinet.net (220.128.1.42)  64.42 ms  AS3462  中国 台湾 台北市 cht.com.tw
11  tchn-3022.hinet.net (220.128.17.61)  69.11 ms  AS3462  中国 台湾 台中市 cht.com.tw
12  tchn-3311.hinet.net (220.128.16.117)  68.62 ms  AS3462  中国 台湾 台中市 cht.com.tw
13  h149.s210.ts.hinet.net (168.95.210.149)  69.32 ms  AS3462  中国 台湾 台中市 cht.com.tw
14  211-22-184-1.HINET-IP.hinet.net (211.22.184.1)  70.18 ms  AS3462  中国 台湾 台中市 cht.com.tw


路由追踪到 台湾APTG (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 210.203.22.27 (210.203.22.27), 30 hops max, 60 byte packets
 1  103.212.69.66  0.43 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  1.66 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  42.46 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  45.91 ms  AS24218  新加坡 globaltransit.net
 6  ae-2.cr-gw-2-sin-pip.sg.globaltransit.net (61.11.212.58)  41.93 ms  AS24218  新加坡 globaltransit.net
 7  ae-10.cr-gw-1-sin-pip.sg.globaltransit.net (124.158.224.61)  40.67 ms  AS24218  新加坡 globaltransit.net
 8  xe-0-0-0-0.pp-gw-1-hkg-pip.hk.globaltransit.net (124.158.224.22)  41.39 ms  AS24218  中国 香港 globaltransit.net
 9  17709.hkg.equinix.com (36.255.56.153)  42.32 ms  AS4323,AS7713,AS18403,AS58879  中国 香港 equinix.com
10  43.240.106.36  69.51 ms  AS17709  中国 台湾 aptg.com.tw
11  211.76.96.76  68.46 ms  AS17709  中国 台湾 台北市 aptg.com.tw
12  210-203-22-27.static.apol.com.tw (210.203.22.27)  74.62 ms  AS17709  中国 台湾 台北市 aptg.com.tw


路由追踪到 台湾TWMBroadBand (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 175.98.130.15 (175.98.130.15), 30 hops max, 60 byte packets
 1  103.212.69.66  0.39 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  ae-2-58.r21.kslrml02.my.bb.gin.ntt.net (203.78.193.109)  87.39 ms  AS2914  马来西亚 吉隆坡联邦直辖区 ntt.com
 4  ae-6.r21.sngpsi07.sg.bb.gin.ntt.net (129.250.3.51)  75.57 ms  AS2914  新加坡 ntt.com
 5  ae-7.r20.sngpsi07.sg.bb.gin.ntt.net (129.250.3.74)  73.46 ms  AS2914  新加坡 ntt.com
 6  ae-9.r24.tkokhk01.hk.bb.gin.ntt.net (129.250.7.67)  78.83 ms  AS2914  中国 香港 ntt.com
 7  ae-0.r21.taiptw01.tw.bb.gin.ntt.net (129.250.2.181)  84.07 ms  AS2914  中国 台湾 台北市 ntt.com
 8  ae-1.r02.taiptw01.tw.bb.gin.ntt.net (129.250.2.83)  80.34 ms  AS2914  中国 台湾 台北市 ntt.com
 9  xe-0-6-0-2-6.r02.taiptw01.tw.ce.gin.ntt.net (61.58.33.10)  88.65 ms  AS2914  中国 台湾 台北市 ntt.com
10  60-199-16-202.static.tfn.net.tw (60.199.16.202)  82.01 ms  AS9924  中国 台湾 台北市 twmbroadband.com
11  60-199-4-198.static.tfn.net.tw (60.199.4.198)  91.87 ms  AS9924  中国 台湾 台北市 twmbroadband.com
12  60-199-4-198.static.tfn.net.tw (60.199.4.198)  79.77 ms  AS9924  中国 台湾 台北市 twmbroadband.com
13  squid.au.edu.tw (175.98.130.15)  86.63 ms  AS9924  中国 台湾 台北市 twmbroadband.com


路由追踪到 台湾Chief (TCP 模式, 最大 30 跃点)
============================================================
traceroute to 103.51.140.34 (103.51.140.34), 30 hops max, 60 byte packets
 1  103.212.69.66  0.75 ms  AS55720  马来西亚 吉隆坡联邦直辖区 thegigabit.com
 2  *
 3  124.158.233.57  0.56 ms  AS24218  马来西亚 globaltransit.net
 4  61.11.212.25  42.08 ms  AS24218  新加坡 globaltransit.net
 5  61.11.210.101  42.64 ms  AS24218  新加坡 globaltransit.net
 6  61.11.210.97  41.45 ms  AS24218  GLOBALTRANSIT.NET 骨干网 globaltransit.net
 7  ae-2.cr-gw-1-sin-pip.sg.globaltransit.net (61.11.210.106)  42.80 ms  AS24218  新加坡 globaltransit.net
 8  xe-0-0-0-0.pp-gw-1-hkg-pip.hk.globaltransit.net (124.158.224.22)  42.69 ms  AS24218  中国 香港 globaltransit.net
 9  17408.hkg.equinix.com (36.255.56.175)  71.74 ms  AS4323,AS7713,AS18403,AS58879  中国 香港 equinix.com
10  *
11  103-51-140-1.RDNS.serverfield.com.tw (103.51.140.1)  72.13 ms  AS134094  中国 台湾 台北市 serverfield.co.uk
12  103.51.140.34  71.95 ms  AS134094  中国 台湾 台北市 serverfield.co.uk


 -> Spoofer测试


 Spoofer测试结果：https://spoofer.caida.org/report.php?sessionkey=88gbwk28j2m9pf
