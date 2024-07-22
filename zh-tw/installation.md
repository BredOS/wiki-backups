---
title: Installation guide for BredOS
description: null
published: true
date: 2024-07-19T00:43:06.679Z
tags: null
editor: markdown
dateCreated: 2024-07-19T00:42:37.505Z
---

# Header

## Table of contents

1. [Installation Guide](#installation-guide)
   - [下載 BredOS](#下載-bredos)

   - [製作安裝媒介](#製作安裝媒介)

   - [使用安裝媒介開機](#使用安裝媒介開機)

   - [安裝 BredOS](#安裝-bredos)

## Installation Guide

### Downloading BredOS

從[官方網站](https://bredos.org/download.html)下載裝置對應的最新 BredOS 映像

### Creating the Installation Media

1. Insert your microSD card into your computer.
2. Use a tool like `balenaEtcher`, `dd`, or `Raspberry Pi Imager` to write the BredOS image to the microSD card.

### Booting from the Installation Media

1. Insert the microSD card into your ARM-based single board computer.
2. 將必要的裝置 (鍵盤, 滑鼠, 螢幕) 接上並啟動電腦
3. The device should boot from the microSD card and load the BredOS installer.

### Installing BredOS

1. 依照畫面上的指示完成安裝
2. 選取您偏好的語言, 鍵盤配置及時區
3. 設定使用者帳戶及密碼
4. 完成安裝並重新啟動電腦

## 初次開機及設定

第一次啟動時, 您可能需要完成一些初始的設定

- Configure network settings
- 使用包裝管理器更新系統
- 安裝需要的其他軟體
