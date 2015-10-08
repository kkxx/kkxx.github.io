---
published: true
layout: post
title:  "Atom Guide"
date:   2015-10-08 22:06:13
categories: Blog
description: Atom使用总结
---

  最近工作需要阅读redis的代码，一直找不到一个顺手的代码阅读器，尝试过很多工具后最终停留在Atom，在此将Atom使用总结在此，后续将不断完善使用中的一些技巧。
  Atom经过多个版本，当前使用的版本速度已经相当不错啦

  [<img class="center" src="/images/atom_01.png" width="100%" />](/images/atom_01.png)

## Atom配置

* 主题选择，`UI Theme`和`Syntax Theme`都选择默认的`One Dark`,这种配色看着非常舒服。

  [<img class="center" src="/images/atom_02.png" width="100%" />](/images/atom_02.png)

  [<img class="center" src="/images/atom_03.png" width="100%" />](/images/atom_03.png)


## Atom常用快捷键

> mac中的cmd对应windows中的Ctrl键

* 文件跳转

  浏览代码常见的就是文件跳转，当前工程中查找某个文件，atom中`cmd-t`模糊查找某个文件

  [<img class="center" src="/images/atom_04.png" width="100%" />](/images/atom_04.png)

* 符号跳转

  阅读代码时常常需要查询某个符号并进行跳转，atom中通过快捷键`cmd-r`和`cmd-shift-r`,前者是在当前文件中符号跳转，后者是整个项目中跳转

> 使用符号跳转需要安装`Atom Ctags Package`插件，并且在当前项目中生成tags文件，默认情况下在打开某个文件使用过`cmd-r`来查询过符号会自动生成当前文件的
> 所有tags; 另外可以通过安装ctags通过为整个项目生成tags文件

  [<img class="center" src="/images/atom_05.png" width="100%" />](/images/atom_05.png)

* 书签跳转

  在阅读代码经常需要做一些标记，加快跳转速度，此时可以通过atom的书签功能，快捷键`cmd-F2`,通过`F2`和`shift-F2`可以顺序的在书签列表中跳转，查看当前
  项目中所有的书签列表通过`ctrl-F2`

  [<img class="center" src="/images/atom_06.png" width="100%" />](/images/atom_06.png)

* 代码行跳转

  在代码中跳转到某一行使用`ctrl-g`同时用`row:column`,column可以不输入，默认行首

  [<img class="center" src="/images/atom_07.png" width="100%" />](/images/atom_07.png)
