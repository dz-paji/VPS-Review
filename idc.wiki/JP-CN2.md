# idc.wiki 日本主机评测

## 基础配置

### 硬件配置

| 配置项       | 详情                                 |
|--------------|--------------------------------------|
| CPU 型号     | Intel Xeon Processor (Skylake, IBRS) |
| CPU 核心数   | 1                                    |
| CPU 主频     | 2592.570 MHz                         |
| 总硬盘大小   | 20.0 GB (1.5 GB Used)                |
| 总内存大小   | 1998 MB (54 MB Used)                 |
| 总 Swap 大小 | 511 MB (0 MB Used)                   |


### IO

| 测试项      | 写入                            | 读取                            |
|-------------|---------------------------------|---------------------------------|
| 10MB-4K块   | 23.3 MB/s (5678 IOPS, 0.45 秒)  | 27.5 MB/s (6710 IOPS, 0.38 秒)  |
| 10MB-1M块   | 536 MB/s (511 IOPS, 0.02 秒)    | 727 MB/s (693 IOPS, 0.01 秒)    |
| 100MB-4K块  | 22.9 MB/s (5588 IOPS, 4.58 秒)  | 28.0 MB/s (6824 IOPS, 3.75 秒)  |
| 100MB-1M块  | 698 MB/s (665 IOPS, 0.15 秒)    | 901 MB/s (859 IOPS, 0.12 秒)    |
| 1000MB-4K块 | 23.0 MB/s (5626 IOPS, 45.50 秒) | 28.7 MB/s (7012 IOPS, 36.51 秒) |
| 1000MB-1M块 | 857 MB/s (817 IOPS, 1.22 秒)    | 928 MB/s (885 IOPS, 1.13 秒)    |

### 内存性能

| 测试项            | 结果                    |
|-------------------|-------------------------|
| 1 线程测试-顺序读 | 36.49K ops (33.99 MB/s) |
| 1 线程测试-顺序写 | 37.07K ops (34.53 MB/s) |
| 1 线程测试-随机读 | 35.85K ops (33.39 MB/s) |
| 1 线程测试-随机写 | 35.92K ops (33.45 MB/s) |

### UnixBench

#### 单核心

## 网络

### 海外 wget sudu

| 节点名称                 | 下载速度 |
|--------------------------|----------|
| CacheFly                 | 5.82MB/s |
| Linode, Tokyo, JP        | 5.77MB/s |
| Linode, Singapore, SG    | 5.70MB/s |
| Linode, London, UK       | 5.45MB/s |
| Linode, Frankfurt, DE    | 5.35MB/s |
| Linode, Fremont, CA      | 5.64MB/s |
| Softlayer, Dallas, TX    | 5.55MB/s |
| Softlayer, Seattle, WA   | 5.67MB/s |
| Softlayer, Frankfurt, DE | 5.30MB/s |
| Softlayer, Singapore, SG | 5.71MB/s |
| Softlayer, HongKong, CN  | 5.75MB/s |
