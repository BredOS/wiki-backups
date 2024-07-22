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

1. [安裝教學](#安裝教學)
   - [下載 BredOS](#下載-bredos)

   - [製作安裝媒介](#製作安裝媒介)

   - [使用安裝媒介開機](#使用安裝媒介開機)

   - [安裝 BredOS](#安裝-bredos)

## 安裝教學

### 下載 BredOS

從[官方網站](https://bredos.org/download.html)下載裝置對應的最新 BredOS 映像

### 製作安裝媒介

1. 將 microSD 插入您的電腦
2. 使用 `balenaEtcher`, `dd` 或 `Raspberry Pi Imager` 工具將 BredOS 映像寫入 microSD

### 從安裝媒介開機

1. 將 microSD 插入您的 ARM 單板電腦
2. 將必要的裝置 (鍵盤, 滑鼠, 螢幕) 接上並啟動電腦
3. 裝置將從 microSD 開機並載入 BredOS 安裝程式

### 安裝 BredOS

1. 依照畫面上的指示完成安裝
2. 選取您偏好的語言, 鍵盤配置及時區
3. 設定使用者帳戶及密碼
4. 完成安裝並重新啟動電腦

## 初次開機及設定

第一次啟動時, 您可能需要完成一些初始的設定

- 調整網路設定
- 使用軟體包管理器更新系統
- 安裝需要的其他軟體
