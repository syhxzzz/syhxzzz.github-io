---
layout: 1
title: 起源
date: 2022-9-4 20:30:45
tags:
---

受到某位信安同学影响，加上自己学习CS相关和Unity和策划一直少有笔记与总结，故搭建博客以记录学习所得。

## Archlinux 
### Archlinux 使用时遇到的问题
#### 清空下载缓存
目前在学校里只能使用最多两个设备的校园网，而电脑的Windows系统与Linux系统被视作两个系统，加上偶尔需要用到的平板，有时候需要进行验证才能上网。在没有验证的情况下进行每日的更新操作时，会导致无法下载，并且正常上网时也不能下载。此时需要对缓存区进行清理，输入  `rm -f /var/lib/pacman/sync/* ` 即可。