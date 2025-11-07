# Unipak

**Unipak** is a universal package manager for Ubuntu that can install software from multiple sources: apt, snap, flatpak, and AppImages. It provides a single CLI to search, install, and uninstall packages across these platforms.

---

## Features

- Install packages from **APT**, **Snap**, **Flatpak**, and **AppImages**.
- Search for packages across multiple package managers.
- Simple command-line interface.
- Lightweight and easy to use.

---

## Installation

```bash
sudo dpkg -i unipak-[version]-[channel].deb
sudo apt install -f   # fix any missing dependencies

```
---
## Releases/Channels

 The **Beta** channel has upcoming versions that need to be debugged/tested before release
 The **Stable** channel has stable versions that have been debugged/tested

To uninstall any release, just type:
```bash
sudo apt remove unipak

```

-All releases have been tested on Ubuntu 25.10.

-Before updating versions, uninstall the previous version before installing a new one.

## Notes

Hi, Wiimmfi here! This is my first ever project on GitHub. I built **Unipak** to explore Python programming and make managing packages on Ubuntu easier. I’m really excited to share it with the community! As a first project, it might have some quirks, so any feedback, ideas, or contributions would be amazing. Thanks for taking a look, and I hope you find Unipak useful! 
