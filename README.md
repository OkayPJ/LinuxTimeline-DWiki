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

Original source: http://futurist.se/gldt/

Current source: https://github.com/FabioLolix/LinuxTimeline

### 参与贡献

参见 [CONTRIBUTING](https://gitee.com/OkayPJ/LinuxTimeline-DWikiBranch/blob/master/CONTRIBUTING)

### 生成

如果您想要生成您自己的 SVG 图像，请先确保您以经安装了 gnuclad。

若要安装 gnuclad，可以到一下位置下载源码：
* https://launchpad.net/gnuclad
* https://github.com/FabioLolix/gnuclad

Arch Linux 用户可以使用 AUR：https://aur.archlinux.org/packages/gnuclad

在 gunclad 安装完成后，使用如下命令生成 SVG 图像。

    gnuclad ldt.csv SVG ldt.conf

