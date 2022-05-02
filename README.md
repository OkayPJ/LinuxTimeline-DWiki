Linux Distribution Timeline DistroWiki Version| README
------------------------------------

* Copyright (C) 2010-2012 Andreas Lundqvist, Donjan Rodic, Mohammed A. Mustafa
* Copyright (C) 2016 Muhammad Herdiansyah
* Copyright (C) 2016-2021 Fabio Loli
* Copyright (C) 2021 OkayPJ

Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3 or
any later version published by the Free Software Foundation; with no
Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.

原始项目：http://futurist.se/gldt/

当前项目：https://github.com/FabioLolix/LinuxTimeline

当前项目 Gitee 镜像：https://gitee.com/mirrors_FabioLolix/LinuxTimeline

本分支：https://gitee.com/OkayPJ/LinuxTimeline-DWiki

### 关于该项目

LinuxTimeline 是由原 Andreas Lundqvist 等人，现 Fabio Loli 维护的 Linux 发行版时间线。

#### 关于该分支

该分支计划成为 [DistroWiki](http://distrowiki-cn.wikidot.com/) 的子项目。原 LinuxTimeline 对整理的发行版有诸多限制，如必须发行满两年等。该分支没有这些限制，因此可能会变得混乱。如果需要更严谨的时间线，还请使用[原项目](https://github.com/FabioLolix/LinuxTimeline)。

### 参与贡献

参见 [CONTRIBUTING](https://gitee.com/OkayPJ/LinuxTimeline-DWiki/blob/master/CONTRIBUTING)，需注意这是原项目的指南，部分不适用于此分支。

### 生成

如果您想要生成您自己的 SVG 图像，请先确保您以经安装了 gnuclad。

若要安装 gnuclad，可以到以下位置下载源码：
* https://launchpad.net/gnuclad
* https://github.com/FabioLolix/gnuclad

Arch Linux 用户可以使用 AUR：https://aur.archlinux.org/packages/gnuclad

在 gunclad 安装完成后，使用如下命令生成 SVG 图像。

    gnuclad ldt.csv SVG ldt.conf

