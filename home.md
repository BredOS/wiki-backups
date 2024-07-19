---
title: Homepage
description: 
published: true
date: 2024-07-19T14:23:43.515Z
tags: 
editor: markdown
dateCreated: 2022-08-24T12:37:36.410Z
---

# The BredOS Wiki

## Overview
Welcome to the BredOS documentation! BredOS is a user-friendly Arch-based Linux distribution specifically designed for ARM-based single board computers (SBCs). This documentation will guide you through the installation, configuration, and usage of BredOS.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [System Requirements](#system-requirements)
4. [Installation](/installation)
6. [Package Management](#package-management)
7. [Troubleshooting](#troubleshooting)
8. [FAQ](#faq)
9. [Community and Support](#community-and-support)
10. [Contributing](#contributing)

## Introduction
BredOS aims to provide a seamless and user-friendly experience for users of ARM-based single board computers. By leveraging the power and flexibility of Arch Linux, BredOS offers a robust platform that can be customized to fit a wide range of use cases.

## Features
- **User-Friendly Interface**: A simplified and intuitive user interface for easy navigation and use.
- **Arch-Based**: Built on top of Arch Linux, ensuring access to a vast repository of packages and a rolling release model.
- **ARM Support**: Optimized for ARM-based single board computers, making it ideal for devices like the Rock 5B, and more.
- **Lightweight**: Minimal bloat, ensuring a lightweight and responsive system.

## System Requirements
- **Supported Devices**: Radxa Rock 5 A/B/C, Orange Pi 5/5+, Khadas Edge 2, Khadas VIM 4, Cool Pi 4B
- **Minimum RAM**: 2 GB
- **Storage**: 16 GB microSD card or larger
- **Network**: Optional

## Installation
Read more on our [Installation guide](/installation) page.


## Package Management
BredOS uses `pacman`, the package manager from Arch Linux. Here are some common commands:
- Update package list: `sudo pacman -Syu`
- Install a package: `sudo pacman -S [package_name]`
- Remove a package: `sudo pacman -R [package_name]`
- Search for a package: `pacman -Ss [package_name]`

## Troubleshooting
If you encounter issues with BredOS, you are welcome to join our [discord](https://discord.gg/jwhxuyKXaa).

## FAQ
### Q: What devices are supported by BredOS?
A: BredOS supports a variety of ARM-based single board computers, including .

### Q: How do I update BredOS?
A: You can update BredOS using the `pacman` package manager with the command `sudo pacman -Syu`.

### Q: Where can I find additional software packages?
A: You can find additional software packages in the Arch User Repository (AUR) and install them using `yay` or `paru`.

## Community and Support
Join the BredOS community to get support, share ideas, and contribute to the project:
- [Discord](https://discord.gg/jwhxuyKXaa)
- [GitHub](http://github.com/BredOS)

## Contributing
BredOS is an open-source project, and contributions are welcome! You can contribute in the following ways:
- Report bugs and issues
- Submit patches and improvements
- Write and improve documentation
- Help other users in the community forums and chat

For more information on contributing, visit our [GitHub](http://github.com/BredOS) or you can message us on [Discord](https://discord.gg/jwhxuyKXaa). 
