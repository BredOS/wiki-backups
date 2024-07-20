---
title: 如何在方舟上安装Steam
description: null
published: true
date: 2024-07-20T08:56:15.971Z
tags: null
editor: markdown
dateCreated: 2024-07-20T07:04:41.476Z
---

# 在 BredOS 上安装 Steam (ARM)

本指南将带着您在 BredOS 上安装 Steam 包括添加BredOS mullib 版本库的必要步骤，并安装`box86-rk3xxx` 和 `box64-rk3xxx` 以实现与Arm的兼容性。

## 目录

1. [更新你的系统](#第-1-步-更新你的系统)
2. [添加 BredOS Multilib 仓库](#步骤-2-添加-bredos-multilib-存储库)
3. [更新Pacman 数据库](#第-3-步-更新pacman-数据库)
4. [安装 Box86 和 Box64](#第-4-步-安装-box86-和-box64)
5. [安装 Steam](#步骤-5-安装-steam)
6. [运行 Steam](#步骤6-运行-steam)

## 第 1 步：更新您的系统

在您开始之前，请确保您的系统是最新的。

```bash
sudo pacman -Syu
```

## 步骤 2：添加 BredOS multilib 存储库

要安装 Steam 和必要的翻译层，您需要添加 BredOS multilib 存储库。 在 root 权限的文本编辑器中打开您的 `/etc/pacman.conf` 文件。

```sh
sudo nano /etc/pacman.conf
```

并在文件末尾添加以下行：

```ini
[BredOS-multilib]
Include = /etc/pacman.d/bredos-mirrorlist
```

保存文件并退出文本编辑器 (<kbd>Ctrl</kbd> + <kbd>X</kbd>, 然后 <kbd>Ctrl</kbd> + <kbd>Y</kbd>, 然后 <kbd>输入</kbd>)。

## 第 3 步：更新Pacman 数据库

添加多lib 仓库后，更新数据包以包含新的存储库。

```bash
sudo pacman -Syy
```

## 第 4 步：安装 Box86 和 Box64

因为Steam和它的许多游戏是为x86建筑构造的， 您需要安装 box86-rk3xxx 和 box64-rk3xxx 才能在您的 ARM 设备上运行。

```bash
sudo pacman -S box86-rk3xxx box64-rk3xxx
```

## 步骤5：安装 Steam

现在，您可以从 multilib 仓库安装 Steam

```bash
sudo pacman -S steam
```

## 步骤6：运行 Steam

通过安装一切，您现在可以运行 Steam。 只需从应用程序启动器打开蒸汽，或在您的终端中输入以下命令：

```bash
steam
```
