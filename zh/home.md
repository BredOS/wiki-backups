---
title: 目录
description: 
published: true
date: 2024-07-20T08:16:35.319Z
tags: 
editor: markdown
dateCreated: 2024-07-19T14:28:40.812Z
---

# BredOS Wiki

## 概述

BredOS 主页 欢迎来到 BredOS 文档！BredOS 是一个基于 Arch 的用户友好型 Linux 发行版，专门为基于 ARM 的单板计算机（SBC）设计。本文档将指导您完成 BredOS 的安装、配置和使用。 此文档将引导您安装、配置和使用 BredOS 。

## 目录

1. [简介](#简介)
2. [功能](#功能)
3. [系统要求](#系统要求)
4. [安装](/installation)
5. [软件包管理](#软件包管理)
6. [故障排除](#故障排除)
7. [常见问题](#常见问题)
8. [社区与支持](#社区与支持)
9. [贡献](#贡献)

## 简介

BredOS 旨在为基于 ARM 的单板计算机用户提供无缝且用户友好的体验。通过利用 Arch Linux 的强大功能和灵活性，BredOS 提供了一个可以根据广泛用例进行自定义的强大平台。 通过利用 Arch Linux 的强大功能和灵活性，BredOS 提供了一个可以根据广泛用例进行自定义的强大平台。

## 功能

- **用户友好界面**：简化且直观的用户界面，便于导航和使用。
- **基于 Arch**：建立在 Arch Linux 之上，确保访问到大量的软件包和滚动更新模型。
- **ARM 支持**：针对基于 ARM 的单板计算机进行了优化，非常适合 Rock 5B 等设备。
- **轻量级**：最小化冗余，确保系统轻量且响应迅速。

## 系统要求

- **支持设备**：Radxa Rock 5 A/B/C、Orange Pi 5/5+、Khadas Edge 2、Khadas VIM 4、Cool Pi 4B
- **最低内存**：2 GB
- **存储**：16 GB 或更大的 microSD 卡
- **网络**：可选

## 安装

请参阅我们的 [安装指南](/installation) 页面以获取更多信息。

## 软件包管理

BredOS 使用 `pacman`，这是来自 Arch Linux 的软件包管理器。以下是一些常用命令： 以下是一些常见的命令：

- 更新软件包列表：`sudo pacman -Syu`
- 安装软件包：`sudo pacman -S [package_name]`
- 移除软件包：`sudo pacman -R [package_name]`
- 搜索软件包：`pacman -Ss [package_name]`

## 故障排除

如果您遇到 BredOS 的问题，欢迎加入我们的 [Discord](https://discord.gg/jwhxuyKXaa) 进行咨询。

## 常见问题

### 问：BredOS 支持哪些设备？

答：BredOS 支持各种基于 ARM 的单板计算机，包括 Radxa Rock 5A/B/C、Orange Pi 5/5+ 等。

### 问：如何更新 BredOS？

答：您可以使用 `pacman` 软件包管理器通过命令 `sudo pacman -Syu` 更新 BredOS。

### 问：在哪里可以找到更多的软件包？

答：您可以在 Arch 用户仓库（AUR）中找到额外的软件包，并使用 `yay` 或 `paru` 安装它们。

## 社区与支持

加入 BredOS 社区，获取支持、分享想法并为项目做出贡献：

- [Discord](https://discord.gg/jwhuyKXaa)
- [GitHub](http://github.com/BredOS)

## 贡献

BredOS 是一个开源项目，欢迎贡献！您可以通过以下方式进行贡献： 您可以通过以下方式做出贡献：

- 报告错误和问题
- 提交补丁和改进
- 编写和改进文档
- 在社区论坛和聊天中帮助其他用户

有关更多贡献信息，请访问我们的 [GitHub](http://github.com/BredOS) 或通过 [Discord](https://discord.gg/jwhxuyKXaa) 与我们联系。
