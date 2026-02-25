# LW-ESC-Bootloader

## Overview

Bootloader for LW-ESC.

## Supported Platforms

- STM32L431

## Firmware Development Environment Setup

### IDE

The firmware is developed as a CMake project using [STM32Cube for Visual Studio Code](https://www.st.com/content/st_com/ja/stm32-mcu-developer-zone/software-development-tools/stm32cubevscode.html).

- [Visual Studio Code](https://code.visualstudio.com/)
- [STM32CubeCLT](https://www.st.com/ja/development-tools/stm32cubeclt.html?icmp=tt38569_gl_lnkon_apr2024)
- [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)

### Version control system

- [Git](https://git-scm.com/)

### Debugger

- [STLINK-V3](https://www.st.com/ja/development-tools/stlink-v3set.html)
- [STLINK-V3MINI](https://www.st.com/ja/development-tools/stlink-v3mini.html)
- [Segger J-Link](https://www.segger.com/downloads/jlink/)
- [Segger Ozone](https://www.segger.com/products/development-tools/ozone-j-link-debugger/)

## About Git Management

### Git Commit - Commit Prefix

Add a prefix to git commit messages. And add as needed.

- **feat:** A new feature or addition.
- **fix:** A bug fix.
- **docs:** Changes to documentation only.
- **update:** Modifying existing code.
- **remove:** Deleting anything.
- **chore:** Maintenance, build tasks, or library updates.

**Example:**
```git
fix: wrong date parsing
docs: update API usage in README
update: improve loading performance
remove: unused helper functions
```

### Git Branching - Branch Management

We use gitflow for git branch management.

- [Gitflow Workflow: ATLASSIAN](https://www.atlassian.com/ja/git/tutorials/comparing-workflows/gitflow-workflow)
