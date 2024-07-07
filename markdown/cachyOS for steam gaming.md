---
tag: 'markdown'
date: '2024/7/4'
---

# win11 上安装 cachyOS 双系统配置

[cachyOS 官网](https://cachyos.org/)

我的方案是 "单硬盘双系统", 考虑到可能会被 hwid ban, 记录一下安装历程方便转世

1. 压缩卷, 把我的硬盘 2/3 留给 windows, 1/3 压缩出来不要分配盘
2. 下个 rufus 或类似软件, 写入 cachyOS 镜像
3. bios 启动 u 盘, 安装到开始分区
4. 分区1 - 逻辑分区 500m 留给 efi
5. 分区2 - 主分区 ext4 日志文件系统