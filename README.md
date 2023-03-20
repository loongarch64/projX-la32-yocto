# projX-la32-yocto

## 项目名称

支持32位LoongArch(LA32)的yocto系统

## 支持单位

龙芯中科技术股份有限公司、中国科学院计算技术研究所

## 项目描述

[yocto](https://yoctoproject.org)是一个支持定制Linux发行版的工具平台，被很多厂商采用。LoongArch是龙芯公司推出的国产指令集体系结构，它包括全功能的64位版本LA64和32位子集LA32。本项目的目标是使用yocto构建一个LA32的Linux发行版，主要工作包括完善LA32工具链，向yocto框架和相关开源软件添加LA32支持等等。目前已有LA64版本的yocto可供参考。

## 所属赛道

2023全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2023全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

* 张福新 
    - github github.com/foxsen
    - Email  fxzhang @ ict.ac.cn

## 难度

中-高

# License

GPL V3.0.

## 预期目标

* 完善LA32编译环境。目前Binutils/GCC/GDB/Glibc均已官方支持LoongArch64，绝大部分yocto采纳的开源软件包也支持LoongArch64。但LA32的支持尚有待完善。
* 移植和完善yocto最小系统。
* 在模拟器和真机运行yocto LA32系统。

## 参考资源

* [QEMU模拟器](https://qemu.org)。官方qemu 7.2以后的版本支持LoongArch。
* [yocto for Loongson](https://github.com/loongarch64/meta-loongson)。Yocto的LA64实现。
* [LoongArch docs](https://github.com/loongson/LoongArch-Documentation)。LoongArch相关文档，包括架构手册，ABI, 3A5000 CPU和7A1000桥片手册等。

## 备注

龙芯可免费提供所需要的龙芯开发设备资源。
