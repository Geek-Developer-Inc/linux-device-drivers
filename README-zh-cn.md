[![](https://img.shields.io/badge/language-English-blue.svg?style=flat-square)](./README.md)


# Linux 设备驱动程序开发


## Linux 设备驱动简介

设备驱动程序的作用：计算机系统的运行都是由系统中的软硬件共同作用的结果，硬件是底层基础，是所有软件运行的平台，而驱动程序向下驱动硬件工作，向上提供接口。在 Linux 内核中，设备驱动程序是连接硬件和内核的桥梁。设备驱动的作用是驱使硬件设备行动，驱动与底层硬件直接打交道，驱动程序可以看成是应用程序和实际设备间的一个软件层，Linux 内核支持模块的动态扩展，即在系统运行时给内核增加新的功能模块，使得驱动程序可以独立于内核其它部分而建立，可以在运行时加载或者卸载该驱动模块。

驱动程序的典型特征：同时支持同步和异步操作；驱动程序能够被多次打开；充分利用硬件特性；以及不具备用来 “简化任务” 的或提供与策略相关的软件层等。不带策略是软件设计者的一个共同目标。

Linux 内核功能划分：进程管理；内存管理；文件系统；设备控制；网络功能。

Linux 设备和模块的分类：字符设备；块设备；网络接口。


## Linux 版本编号

Linux kernel release 4.4.16


## 文档

Linux 内核在线文档：https://www.kernel.org/doc/html/v4.16/index.html

Linux 内核开发在线文档：https://www.kernel.org/doc/html/v4.16/process/howto.html

Linux 设备驱动程序：https://lwn.net/Kernel/LDD3/

Linux 设备驱动开发详解：http://bbs.hqyj.com/thread-313-1-1.html


## 克隆仓库
```bash

$ git clone https://github.com/Geek-Developer-Inc/linux-device-drivers.git

```