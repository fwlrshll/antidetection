# HostDare 1C-1.5G-10G-1T@200Mbps 洛杉矶 年付10.4美元性能测试报告

## 配置升级与性价比分析

相较于此前的1核1G配置，HostDare最新套餐升级为1核1.5G内存，硬盘容量10G，流量1T，带宽高达200Mbps，年付仅需10.4美元。性价比有所提升，尤其适合轻量级应用场景。从测试数据来看，IO性能表现不错，平均读写速度达774.3 MB/s，非低速硬盘，采用QN机房部署。不过，到国内的网络速度表现一般，部分线路延迟较高，适合对延迟要求不高的用户。

👉 [HostDare优惠码和2025年促销活动整理(洛杉矶CN2 GIA/CN2 GT/日本软银)](https://bit.ly/hostdare)

## 优惠信息概览

当前可用的优惠码为：**6OU19PTR6P**，享受4折折扣。这使得原本就具备价格优势的套餐更具吸引力，适合预算有限但追求稳定性能的用户。

## 硬件与系统基本信息

以下是测试中获取的核心硬件和系统参数：

- **CPU型号**：QEMU Virtual CPU version 2.5+，1核，主频2.59GHz
- **内存**：981.2 MB（已用422.5 MB）
- **硬盘**：9.8 GB（已用6.7 GB）
- **Swap**：255.0 MB（已用44.8 MB）
- **操作系统**：Ubuntu 20.04 LTS
- **虚拟化技术**：KVM
- **运行时间**：6天16小时54分钟
- **网络**：IPv4支持，IPv6未启用
- **位置**：美国加利福尼亚州洛杉矶，QN机房（AS8100 QuadraNet Enterprises LLC）

## 磁盘IO性能测试

通过三次测试，磁盘IO速度表现稳定，具体结果如下：

- **第一次**：646 MB/s
- **第二次**：838 MB/s
- **第三次**：839 MB/s
- **平均值**：774.3 MB/s

这样的IO性能在同价位产品中表现良好，适合文件存储或轻量级网站托管需求。

## 网络速度与延迟测试

以下为全球部分节点的网络性能测试结果，涵盖上传速度、下载速度和延迟：

| 节点            | 上传速度   | 下载速度   | 延迟     |
|-----------------|------------|------------|----------|
| Speedtest.net   | 810.38 Mbps| 762.01 Mbps| 0.51 ms  |
| 洛杉矶，美国    | 813.17 Mbps| 838.98 Mbps| 0.84 ms  |
| 达拉斯，美国    | 552.37 Mbps| 793.90 Mbps| 28.96 ms |
| 上海，中国      | 49.03 Mbps | 395.01 Mbps| 282.29 ms|
| 香港，中国      | 5.17 Mbps  | 0.33 Mbps  | 153.54 ms|
| 东京，日本      | 167.68 Mbps| 417.72 Mbps| 154.99 ms|

从数据来看，洛杉矶本地网络表现优异，延迟低、速度快。然而，到国内线路（如上海、香港）的速度和稳定性下降，延迟普遍较高，可能受到跨国网络路由影响。

👉 [HostDare优惠码和2025年促销活动整理(洛杉矶CN2 GIA/CN2 GT/日本软银)](https://bit.ly/hostdare)

## Geekbench 5 性能跑分

Geekbench 5测试结果显示，该配置的单核性能表现一般，受限于虚拟化CPU的单核架构：

- **操作系统**：Ubuntu 20.04 LTS
- **内核**：Linux 5.4.0-29-generic x86_64
- **CPU**：QEMU Virtual CPU version 2.5+，1核，2.59GHz
- **缓存**：L1 32KB，L2 4MB，L3 16MB
- **内存**：981 MB

由于测试未提供具体得分，单核性能预计适合基础任务，如轻量级Web服务或小型脚本运行。

## 国内三网路由跟踪

以下为部分国内主要城市的路由测试结果，反映到电信、联通、移动三大运营商的网络表现：

### 北京电信 (163 AS4134)
- **延迟**：约233.40 ms
- **路由**：经由PCCW骨干网，从洛杉矶到广州再到北京，线路较长

### 上海电信 (CN2 AS4809)
- **延迟**：约133.30 ms
- **路由**：走CN2线路，延迟较低，表现优于普通163线路

### 北京联通 (169 AS4837)
- **延迟**：约223.34 ms
- **路由**：通过Arelion网络中转，路径复杂，延迟较高

### 上海移动 (骨干网 AS9808)
- **延迟**：约215.37 ms
- **路由**：经CMI网络直连上海，稳定性尚可

测试表明，CN2线路在延迟和稳定性上更有优势，而普通163和移动线路到国内表现一般。

## 流媒体解锁情况

以下为部分主流流媒体平台的解锁测试结果：

- **Netflix**：仅支持原创内容
- **YouTube Premium**：支持（美国区）
- **Amazon Prime Video**：支持（美国区）
- **Disney+**：不支持
- **TikTok**：支持（美国区）

对于追求流媒体服务的用户，该服务器在部分平台上表现出色，但并非全能解锁。

## 总结与适用场景

HostDare这款年付10.4美元的洛杉矶服务器在性价比上具有一定优势，IO性能和本地网络速度表现亮眼，适合预算有限的个人用户或小型项目。国内网络表现因线路限制较为一般，更推荐用于面向海外用户的轻量级网站托管、文件存储或学习测试环境。若需更优的国内访问速度，可考虑CN2 GIA线路的套餐。