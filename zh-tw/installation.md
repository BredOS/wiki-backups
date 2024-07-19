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
   - [Downloading BredOS](#downloading-bredos)

   - [Creating the Installation Media](#creating-the-installation-media)

   - [Booting from the Installation Media](#booting-from-the-installation-media)

   - [Installing BredOS](#installing-bredos)

## Installation Guide

### Downloading BredOS

Download the latest BredOS image for your device from the [official website](https://bredos.org/download.html).

### Creating the Installation Media

1. Insert your microSD card into your computer.
2. Use a tool like `balenaEtcher`, `dd`, or `Raspberry Pi Imager` to write the BredOS image to the microSD card.

### Booting from the Installation Media

1. Insert the microSD card into your ARM-based single board computer.
2. Connect the necessary peripherals (keyboard, mouse, monitor) and power on the device.
3. The device should boot from the microSD card and load the BredOS installer.

### Installing BredOS

1. Follow the on-screen instructions to complete the installation process.
2. Select your preferred language, keyboard layout, and time zone.
3. Set up a user account and password.
4. Complete the installation and reboot the device.

## First Boot and Configuration

On the first boot, you may need to complete some initial setup tasks:

- Configure network settings
- Update the system using the package manager
- Install additional software packages as needed
