# 🐧 nixos-config

Este repositorio contiene los archivos de configuración de mi sistema **NixOS**, ubicado en `/etc/nixos`. Aquí gestiono todo el entorno del sistema: desde hardware, usuarios, y servicios, hasta entornos gráficos y aplicaciones, utilizando el enfoque declarativo y reproducible que ofrece **Nix**.

---

## ⚙️ Características principales

- 🚀 Arranque con **systemd-boot** (modo EFI)
- 🌐 Red gestionada con **NetworkManager**
- 🌍 Zona horaria: `America/Guayaquil`
- 🗣️ Localización en **inglés (en_US.UTF-8)** con soporte para español de Ecuador
- ⌨️ Teclado con layout `us`
- 🔐 Soporte para software no libre habilitado
- 🎛️ Configuración modular y actualizada a `nixos-25.05`

---

## 🖥️ Entornos gráficos y gestores de ventanas

- 🧩 **GNOME** (principal - completo, estable)
- 🌈 **Hyprland** (Wayland tiling compositor)
- 🧱 **Qtile** (X11 tiling WM - en pruebas)
- 📦 Soporte para **Flatpak** y portales XDG
- 🧠 Integración completa con **Pipewire** para audio y **RTKit** para tiempo real

---

## 🛠️ Software incluido

### 👨‍💻 Desarrollo
- `vim`, `git`, `gh`
- **Visual Studio Code** (`vscode`)
- **Alacritty**, **Kitty**
- Soporte para C, Python, Bash, Arduino, etc.

### 🎧 Multimedia y comunicación
- **Spotify**, **Telegram Desktop**, **Discord**, **VLC**
- **OBS Studio**, **Obsidian** y más

### 🧰 Utilidades
- `wget`, `curl`, `htop`, `neofetch`, `btop`
- **Remmina** (escritorio remoto)
- `bash` como shell principal

---

## 🧩 Wayland + Hyprland (extra)

- 🧱 `waybar` como barra de estado
- 🌈 `hyprpaper` para wallpapers
- 🔔 `dunst` para notificaciones
- 🔍 `rofi-wayland` para lanzador de apps
- 🎨 Tema personalizado en progreso

---

## 👤 Usuarios

- Usuario principal: `seya`
  - Grupo: `wheel` (sudo)
  - Permisos para NetworkManager

---

## 📁 Estructura

Toda la configuración está centralizada en:

/etc/nixos


Planeo modularizar esta configuración para facilitar mantenimiento, compartir partes y escalar mejor.

---

## 📜 Licencia

Este proyecto está bajo la **MIT License**. Puedes consultar el archivo `LICENSE` para más detalles.

> Este repositorio sirve como respaldo, referencia y punto de partida para futuras instalaciones de NixOS.

---


Siéntete libre de usarlo como inspiración o adaptarlo para tu propio setup.
