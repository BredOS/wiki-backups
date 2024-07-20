---
title: BredOS 主頁
description: null
published: true
date: 2024-07-20T07:12:44.807Z
tags: null
editor: markdown
dateCreated: 2024-07-19T14:36:23.702Z
---

# BredOS 維基

## 概述

歡迎來到 BredOS 文檔！ BredOS 是一個基於 Arch 的用戶友好型 Linux 發行版，專門為基於 ARM 的單板計算機（SBC）設計。 本文檔將指導您完成 BredOS 的安裝、配置和使用。

## 目錄

1. [簡介](#簡介)
2. [功能](#功能)
3. [系統要求](#系統要求)
4. [安裝](/installation)
5. [軟件包管理](#軟件包管理)
6. [故障排除](#故障排除)
7. [常見問題](#常見問題)
8. [社區與支持](#社區與支持)
9. [貢獻](#貢獻)

## 簡介

BredOS 旨在為基於 ARM 的單板計算機用戶提供無縫且用戶友好的體驗。 通過利用 Arch Linux 的強大功能和靈活性，BredOS 提供了一個可以根據廣泛用例進行自定義的強大平台。

## 功能

- **用戶友好界面**：簡化且直觀的用戶界面，便於導航和使用。
- **基於 Arch**：建立在 Arch Linux 之上，確保訪問到大量的軟件包和滾動更新模型。
- **ARM 支持**：針對基於 ARM 的單板計算機進行了優化，非常適合 Rock 5B 等設備。
- **輕量級**：最小化冗餘，確保系統輕量且響應迅速。

## 系統要求

- **支持設備**：Radxa Rock 5 A/B/C、Orange Pi 5/5+、Khadas Edge 2、Khadas VIM 4、Cool Pi 4B
- **最低內存**：2 GB
- **存儲**：16 GB 或更大的 microSD 卡
- **網絡**：可選

## 安裝

請參閱我們的 [安裝指南](/installation) 頁面以獲取更多信息。

## 軟件包管理

BredOS 使用 `pacman`，這是來自 Arch Linux 的軟件包管理器。 以下是一些常用命令：

- 更新軟件包列表：`sudo pacman -Syu`
- 安裝軟件包：`sudo pacman -S [package_name]`
- 移除軟件包：`sudo pacman -R [package_name]`
- 搜索軟件包：`pacman -Ss [package_name]`

## 故障排除

如果您遇到 BredOS 的問題，歡迎加入我們的 [Discord](https://discord.gg/jwhxuyKXaa) 進行咨詢。

## 常見問題

### 問：BredOS 支持哪些設備？

答：BredOS 支持各種基於 ARM 的單板計算機，包括 Radxa Rock 5A/B/C、Orange Pi 5/5+ 等。

### 問：如何更新 BredOS？

答：您可以使用 `pacman` 軟件包管理器通過命令 `sudo pacman -Syu` 更新 BredOS。

### 問：在哪裡可以找到更多的軟件包？

答：您可以在 Arch 用戶倉庫（AUR）中找到額外的軟件包，並使用 `yay` 或 `paru` 安裝它們。

## 社區與支持

加入 BredOS 社區，獲取支持、分享想法並為項目做出貢獻：

- [Telegram](https://t.me/bredoslinux)
- [Discord](https://discord.gg/jwhxuyKXaa)
- [GitHub](http://github.com/BredOS)

## 貢獻

BredOS 是一個開源項目，歡迎貢獻 您可以通過以下方式進行貢獻：

- 報告錯誤和問題
- 提交補丁和改進
- 編寫和改進文檔
- 在社區論壇和聊天中幫助其他用戶

For more information on contributing, visit our [GitHub](http://github.com/BredOS) or you can message us on [Discord](https://discord.gg/jwhxuyKXaa) or join our [Telegram](https://t.me/bredoslinux).
