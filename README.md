# STM32CommandLine

___

## 1、DEMO
### 1.1、 Check this demo(using Xshell for terminal, you can also choose SecureCRT if you like):
<img src="./Doc/demo.gif" width = "851" height = "576" alt="demo.gif" align=center />

___

## 2、介绍（[English](#2-introduction)）
- **0x00** 一个**命令行**运行在stm32上，只需要提供一个串口即可实现。
- **0x01** 配合队列处理串口数据，快速响应并退出中断。
- **0x02** 可以移植到任意嵌入式系统，甚至51、AVR、PIC、stm8s等。
- **0x03** 命令支持后续扩展，**支持多种颜色**的log输出到终端，方便调试。

___

## 2 Introduction

- **0x00** : This project is a shell, a CLI(command line interface) like linux shell, demo project is based on STM32(a serial com port is needed).
- **0x01** A fifo queue added for faster IRQ handler.
- **0x02** : You can port this shell into an embeded system, even 51, AVR, PIC, stm8s and so on..
- **0x03** : You can also add your own commands, it is helpful for programmers to debug, also support **colorful debug fonts**.
