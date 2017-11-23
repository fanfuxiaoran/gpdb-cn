<!-- --- title: GPDB 高可用-->

[[_TOC_|level = 3]]

# 0. 概述

> 只有同时启用了master和segment的镜像功能, 才能保证GPDB的高可用

硬件RAID:

    硬件级别的组建RAID, 从性能和安全性两方面考虑
    

数据存储校验和

    GPDB使用校验和来检查从磁盘加载到内存中的数据.
    
    GPDB有2种用户数据: heap表和append-optimized表
