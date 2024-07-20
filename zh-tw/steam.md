---
title: How to install steam on ARM
description: null
published: true
date: 2024-07-20T07:04:41.476Z
tags: null
editor: markdown
dateCreated: 2024-07-20T07:04:41.476Z
---

# Installing Steam on BredOS (ARM)

This guide will walk you through the process of installing Steam on BredOS, including the necessary steps to add the BredOS multilib repository and install `box86-rk3xxx` and `box64-rk3xxx` for compatibility with arm.

## 目錄

1. [Update Your System](#step-1-update-your-system)
2. [Add the BredOS Multilib Repository](#step-2-add-the-bredos-multilib-repository)
3. [Update the Pacman Database](#step-3-update-the-pacman-database)
4. [Install Box86 and Box64](#step-5-install-box86-and-box64)
5. [Install Steam](#step-4-install-steam)
6. [Running Steam](#step-6-running-steam)
7. [故障排除](#故障排除)

## Step 1: Update Your System

Before you start, make sure your system is up-to-date.

```bash
sudo pacman -Syu
```

## Step 2: Add the BredOS Multilib Repository

To install Steam and the necessary translation layers, you need to add the BredOS multilib repository. Open your `/etc/pacman.conf` file in a text editor with root permissions.

```sh
sudo nano /etc/pacman.conf
```

And add the following lines to the end of the file:

```ini
[BredOS-multilib]
Include = /etc/pacman.d/bredos-mirrorlist
```

Save the file and exit the text editor (<kbd>Ctrl</kbd> + <kbd>X</kbd>, then <kbd>Ctrl</kbd> + <kbd>Y</kbd>, then <kbd>Enter</kbd> ).

## Step 3: Update the Pacman Database

After adding the multilib repository, update the pacman database to include the new repository.

```bash
sudo pacman -Syy
```

## Step 4: Install Box86 and Box64

Since Steam and many of its games are built for x86 architecture, you need to install box86-rk3xxx and box64-rk3xxx to run them on your ARM device.

```bash
sudo pacman -S box86-rk3xxx box64-rk3xxx
```

## Step 5: Install Steam

Now, you can install Steam from the multilib repository.

```bash
sudo pacman -S steam
```

## Step 6: Running Steam

With everything installed, you can now run Steam. Simply open steam from the application launcher or type the following command in your terminal:

```bash
steam
```
