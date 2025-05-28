--# 🐧 nixos-config

This repository contains the configuration files of my **NixOS** system, located under `/etc/nixos`. It uses the declarative and reproducible infrastructure provided by the **Nix package manager** and **NixOS module system** to manage the entire system — from hardware and users to desktops and developer tools.

---

## ✨ Why NixOS

**NixOS** is a Linux distribution built on the [Nix package manager](https://nixos.org/), designed with reproducibility, atomic upgrades, and declarative configuration in mind.

Key benefits include:

- Atomic and reliable system upgrades and rollbacks
- Isolated and reproducible development environments
- Full control over packages, services, and system behavior
- Clean modular configuration
- Scalable setup for both desktop and server environments

> This setup is crafted for long-term maintainability, automation, and portability across machines.

---

## ⚙️ System Overview

- Bootloader: `systemd-boot` (EFI)
- Networking: `NetworkManager`
- Timezone: `America/Guayaquil`
- Locale: `en_US.UTF-8` with support for `es_EC.UTF-8`
- Keyboard layout: `us`
- Non-free software: enabled
- Modular configuration based on the `nixos-25.05` channel

---

## 🖥️ Desktop Environments & Window Managers

- **GNOME** – main desktop environment (stable, fully featured)
- **Hyprland** – Wayland tiling compositor
- **Qtile** – X11 tiling window manager (under evaluation)
- Flatpak support and `xdg-desktop-portal` integration
- Audio stack with `PipeWire` and `RTKit` for real-time capabilities

---

## 🛠️ Development Tools

- Editors: `vim`, `Visual Studio Code`
- Terminals: `alacritty`, `kitty`
- Languages: C, Python, Bash, Arduino, and more
- Version control: `git`, `gh`
- Default shell: `bash`

---

## 🎧 Multimedia & Communication

- Applications: `Spotify`, `Telegram Desktop`, `Discord`, `VLC`
- Productivity: `OBS Studio`, `Obsidian`

---

## 🔧 System Utilities

- Remote access: `Remmina`
- Monitoring tools: `htop`, `btop`, `neofetch`
- Network and CLI tools: `wget`, `curl`, and others

---

## 🌈 Hyprland Setup (Wayland)

- Status bar: `waybar`
- Wallpapers: `hyprpaper`
- Notifications: `dunst`
- App launcher: `rofi-wayland`
- Custom theming: in progress

---

## 👤 User Configuration

- Main user: `seya`
  - Member of `wheel` group (sudo privileges)
  - Full access to networking and system management

---

## 📁 Configuration Structure

All configuration is centralized under:


> I’m working on migrating this setup to **flakes** for better reproducibility and dependency control.

---

## 🧠 Future Plans

- Full migration to Nix flakes
- Integration with containerized environments and DevShells
- Secrets management with `sops-nix`
- System hardening using custom `nixpkgs` overlays

---

## 📜 License

This repository is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for more information.

> This project serves as a personal backup, reference, and starting point for future NixOS setups. Feel free to explore or adapt it for your own configuration.

