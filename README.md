[![](https://img.shields.io/badge/language-简体中文-red.svg?style=flat-square)](./README-zh-cn.md)


# Linux device drivers development


## An Introduction to Device Drivers

The role of device drivers: the operation of computer systems are the result of the combination of hardware and software in the system, hardware is the underlying foundation, is the platform for all software operation, and the driver drives the hardware down to work, providing interfaces up. In the Linux kernel, device drivers are the bridge between the hardware and the kernel. The role of device-driven is to drive hardware device action, drive directly with the underlying hardware, the driver can be seen as a software layer between the application and the actual device, the Linux kernel supports the dynamic expansion of the module, that is, the system runtime to add new functional modules to the kernel, so that the driver can be built independently of the rest of the kernel, can be loaded or unloaded at runtime the driver module.

Typical characteristics of drivers: support both synchronization and asynchronous operation; Without policies is a common goal of software designers.

Splitting the Kernel: Process management, Memory management, Filesystems, Device control, Networking.

Classes of Devices and Modules: Character devices, Block devices, Network interfaces.


## Version Numbering

Linux kernel release 4.4.16


## Documentation

The Linux Kernel documentation：https://www.kernel.org/doc/html/v4.16/index.html

Linux Kernel Development documentation：https://www.kernel.org/doc/html/v4.16/process/howto.html

Linux Device Drivers documentation：https://lwn.net/Kernel/LDD3/

Linux Device Drivers Program Development Details：http://bbs.hqyj.com/thread-313-1-1.html


## Cloning the repo
```bash

$ git clone https://github.com/Geek-Developer-Inc/linux-device-drivers.git

```