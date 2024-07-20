---
title: BredOS 安装指南
description: null
published: true
date: 2024-07-19T00：43：06.679Z
tags: null
editor: markdown
dateCreated: 2024-07-19T00:42:37.505Z
---

# 标题

## 目录

1. [安装指南](#installation-guide)
   - [正在下载 BredOS](#downloading-breddos)

   - [创建安装媒体](#creating-the-installation-media)

   - [从安装媒体启动](#启动-从安装媒体启动)

   - [安装 BredOS](#installing-bredos)

## 安装指南

### 正在下载 BredOS

从 [官方网站](https://bredos.org/download.html)下载最新的 BredOS 图像。

### 创建安装媒体

1. 将您的microSD卡插入您的计算机。
2. 使用 `balenaEtcher`, `dd`, 或 `Raspberry Pi Imager` 等工具将BredOS 图像写入microSD卡。

### 从安装媒体启动

1. 将microSD卡插入基于ARM的单个板电脑。
2. 连接设备上的必要外观(键盘、鼠标、显示器)和电源。
3. 设备应从microSD 卡启动并加载 BredOS 安装程序。

### 正在安装 BredOS

1. 按照屏幕指示完成安装过程。
2. 选择您首选的语言、键盘布局和时区。
3. 设置用户帐户和密码。
4. 完成安装并重启设备。

## 首次启动和配置

在第一次启动时，您可能需要完成一些初始设置任务：

- 配置网络设置
- 使用软件包管理器更新系统
- 根据需要安装额外的软件包
