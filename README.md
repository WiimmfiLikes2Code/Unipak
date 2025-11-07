# Unipak

**Unipak** is a universal package manager for Ubuntu that can install software from multiple sources: `apt`, `snap`, `flatpak`, and AppImages. It provides a single interface to search, install, and uninstall packages across these platforms.

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
sudo apt-get install -f   # fix any missing dependencies
