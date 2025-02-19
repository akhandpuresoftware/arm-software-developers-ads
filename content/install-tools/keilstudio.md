---
title: "Arm Keil Studio (VS Code Extension)"

tool_install: true              # DO NOT MODIFY. Always true for tool installs
layout: "installtoolsall"       # DO NOT MODIFY. Always true for the main page of tool installs
---
[Arm Keil Studio](https://keil.arm.com/) is the next generation software development environment for Arm Cortex-M based microcontroller devices. The desktop version is available as a set of [VS Code](https://code.visualstudio.com/) extensions that offer the same functionality as the cloud-native version. It supports all silicon vendors with more than 9,500 devices and is easy to learn and use.

## Pre-requisites

- Install a compiler toolchain. Install the [Arm Compiler for Embedded toolchain](https://developer.arm.com/Tools%20and%20Software/Arm%20Compiler%20for%20Embedded) or the [Arm GNU toolchain](https://developer.arm.com/Tools%20and%20Software/GNU%20Toolchain) (includes the GNU Compiler - GCC), or both.
- Install [CMake](https://cmake.org/) and [Ninja](https://ninja-build.org/).
- Install [CMSIS-Toolbox](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/releases).
- Initialize or update the catalog of public CMSIS-Pack versions (using [cpackget](https://github.com/Open-CMSIS-Pack/devtools/blob/main/tools/cpackget/docs/cpackget.md)).


## Install the extensions

1. In VS Code, go to the **Extensions** view.

1. Search for **Keil Studio Pack**.

1. Click the **Install** button for the extension pack.

    Visual Studio Code installs the extensions. All recommended extensions are now available in the **Extensions** view.

## Get started

In the **Extensions** view, select the **Keil Studio Pack** extension and follow the **Tutorial** to verify everything is installed correctly.