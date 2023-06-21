# 面试要点记录
> 主要涉及到嵌入式软件开发、嵌入式驱动开发、IOT 开发、git 等知识点。
> 最新的请参考[wiki](https://github.com/xiaowenxia/embedded-notes/wiki)和我的[个人博客](https://xiaowenxia.github.io/embedded-notes/)
---
### 要点
- [x] c 基础知识
- [x] 数据结构（链表 hash 表 排序算法 设计模式等）
- [x] 外设（串口 网口 i2s i2c spi sdio 等）
- [x] ARM cortex-m0 m3 m4 A8 等芯片架构
- [ ] 操作系统（内存管理 进程管理 实时性要求 任务间通讯等）
- [x] tcpip 协议栈（tcpip 模型 分层结构 ip tcp udp icmp igmp tftp http ftp 等协议）
- [x] linux 多线程 多进程通讯 linux 系统任务调度和中断
- [ ] bash 命令 shell makefile python github go javascript
- [ ] linux 启动过程
- [ ] git 命令
---
#目录
* [c 语言基础](./c 基础.md)
    * [c 基础](./c 基础.md#c 基础)
        * [数据类型说明](./c 基础.md#数据类型说明)
        * [volatile](./c 基础.md#volatile)
        * [指针](./c 基础.md#函数指针)
        * [const](./c 基础.md#const)
        * [main 函数的返回值](./c 基础.md#main 函数的返回值)
        * [浮点数存储方式](./c 基础.md#浮点数存储方式)
    * [c 题目](./c 基础.md#c 题目)
        * [printf 返回值](./c 基础.md#printf 返回值)
        * [enum 枚举类型](./c 基础.md#enum 枚举类型)
        * [可变参数函数](./c 基础.md#可变参数函数)
    * [链表](./c 基础.md#链表)
    * [排序算法](./c 基础.md#排序算法)
        * [选择排序](./c 基础.md#选择排序)
        * [插入排序](./c 基础.md#插入排序)
        * [希尔排序](./c 基础.md#希尔排序)
        * [冒泡排序](./c 基础.md#冒泡排序)
        * [快速排序](./c 基础.md#快速排序)
* [linux 知识点](./linux.md)
    * [关键命令说明](./linux.md#关键命令说明)
        * [系统关机命令](./linux.md#系统关机命令)
        * [linux 查看文本的指令](./linux.md#linux 查看文本的指令)
        * [mount](./linux.md#mount 指令)
        * [dmesg](./linux.md#dmesg)
        * [grep](./linux.md#grep)
        * [find](./linux.md#find)
        * [lsusb](./linux.md#lsusb)
        * [lsof](./linux.md#lsof)
    * [linux 软件开发知识点](./linux.md#linux 软件开发知识点)
        * [linux 进程间通讯方式](./linux.md#linux 进程间通讯方式)
        * [内存申请函数](./linux.md#内存申请函数)
        * [gcc 编译过程](./linux.md#gcc 编译过程)
        * [文件系统](./linux.md#文件系统)
        * [硬链接和软连接](./linux.md#硬链接和软连接)
        * [linux 内核子系统](./linux.md#linux 内核子系统)
        * [进程几种状态](./linux.md#进程几种状态)
        * [文件系统组成](./linux.md#文件系统组成)
        * [linux 文件类型](./linux.md#linux 文件类型)
        * [linux 常用的系统调用函数](./linux.md#linux 常用的系统调用函数)
        * [fork 函数](./linux.md#fork 函数)
        * [僵尸进程](./linux.md#僵尸进程)
        * [常见文件说明](./linux.md#常见文件说明)
        * [proc 目录说明](./linux.md#proc 目录说明)
        * [fopen 参数说明](./linux.md#fopen 参数说明)
    * [linux 驱动开发知识点](./linux.md#linux 驱动开发知识点)
    * [makefile](./linux.md#makefile)
    * [shell](./linux.md#shell)
* [freertos 源码详解](./freertos-inside.md)
    * [协程--croutine.c](./freertos-inside.md#协程--croutine.c)
* [tcpip 协议栈知识点](./tcpip 协议栈.md)
    * [tcpip 模型](./tcpip 协议栈.md#tcpip 模型)
    * [以太网协议](./tcpip 协议栈.md#以太网协议)
    * [ARP 协议](./tcpip 协议栈.md#ARP 协议)
    * [TCP 协议](./tcpip 协议栈.md#TCP 协议)
* [git 使用说明](./git.md)
    * [git cheatsheet](./git.md#git-cheatsheet)
* [git 底层技术](./git-inside.md)