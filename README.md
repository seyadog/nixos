# nixos
Este repositorio contiene los archivos de configuración de mi sistema NixOS ubicados en /etc/nixos. Aquí gestiono todo mi entorno de sistema, desde el hardware hasta los paquetes instalados, usuarios, servicios, y opciones del sistema operativo, utilizando el poder declarativo de Nix.


# 🐧 Configuración de mi sistema NixOS

Este repositorio contiene mi configuración declarativa para NixOS, ubicada en `/etc/nixos`. Utilizo Nix para mantener un sistema limpio, reproducible y modular, gestionado completamente con archivos `.nix`.

## ⚙️ Características principales

- 🧠 Sistema inicializado con **systemd**
- 🖥️ Entornos de escritorio y window managers:
  - **GNOME** (principal)
  - **Hyprland** (Wayland tiling WM)
  - **Qtile** (X11 tiling WM, en pruebas)

## 🛠️ Software incluido

### 🧑‍💻 Herramientas de desarrollo
- **Vim**
- **Visual Studio Code**
- Soporte general para programación en C, Python, Bash, entre otros

### 🎧 Infoentretenimiento
- **Spotify** (versión empaquetada en Nix)
- Utilidades adicionales para multimedia

### 🧩 Otras herramientas
- Gestores de red, terminales y herramientas esenciales para el día a día
- Soporte para Flatpak y otros entornos si es necesario

## 📁 Estructura
Organizo la configuración en archivos `.nix` separados para mejorar la legibilidad y facilitar la modificación de módulos específicos del sistema.

## 📜 Licencia

Este proyecto se distribuye bajo la **MIT License**. Puedes ver el archivo `LICENSE` para más información.

> Este repo también sirve como respaldo y documentación de mi sistema actual. Siéntete libre de explorar, aprender o adaptar partes a tu propio sistema.

---

### 🐚 ¡Bienvenido a mi mundo Nix!
