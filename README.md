# Hyprland Dotfiles

Personal configuration files for my Hyprland-based Linux desktop.

The goal of this repository is to keep my desktop environment reproducible, organized, and easy to maintain while using a minimal Wayland workflow.

## Overview

This repository contains configuration for a Hyprland setup focused on:

- Wayland-first desktop configuration
- Keyboard-driven workflow
- Lightweight and modular components
- Consistent GTK and Qt theming
- Custom scripts and keybindings
- Practical defaults for daily development and system administration

## Components

The configuration is built around Hyprland and complementary Wayland tools such as:

- **Hyprland** — Wayland compositor
- **Waybar** — status bar
- **Rofi** — application launcher
- **SwayNC** — notification daemon
- **Alacritty** — terminal emulator
- **Thunar** — file manager
- **Brave** — web browser
- **Obsidian** — notes and knowledge management
- **NetworkManager Applet** — network management

The exact set of components may change as the configuration evolves.

## Configuration Structure

The repository is organized around the configuration files used by the desktop session. Hyprland configuration is split into smaller modules where practical, making individual components easier to understand and modify.

Typical areas include:

```text
hyprland_dotfiles/
├── hyprland/       # Hyprland configuration
├── waybar/         # Status bar configuration
├── rofi/            # Application launcher configuration
├── swaync/          # Notification configuration
├── alacritty/       # Terminal configuration
└── scripts/         # Utility scripts
```

> The directory structure above represents the intended organization. Check the repository contents for the current implementation.

## Installation

These dotfiles are primarily intended for my own system. Do not copy the configuration blindly onto another machine.

Clone the repository:

```bash
git clone https://github.com/csouzape/hyprland_dotfiles.git
cd hyprland_dotfiles
```

Back up your existing configuration before installing or replacing files.

For a manual installation, copy only the components you need into the corresponding directories under `~/.config/`.

## Requirements

A functional Hyprland environment is required. Depending on which parts of the configuration are used, you may also need:

- Hyprland
- Waybar
- Rofi
- SwayNC
- Alacritty
- Thunar
- NetworkManager
- GTK/Qt theme configuration tools
- Nerd Font-compatible fonts

Package names and availability depend on the Linux distribution.

## Customization

This repository is continuously adjusted to match my workflow. Paths, applications, keybindings, themes, environment variables, and scripts may be specific to my hardware and software stack.

Before using the configuration on another system, review:

- Monitor configuration
- Keyboard and mouse settings
- Application paths
- Environment variables
- Keybindings
- Autostart entries
- Theme and font settings

## Philosophy

The configuration follows a simple principle: keep the desktop lightweight, predictable, keyboard-oriented, and under version control.

Hyprland is used as the compositor rather than as a complete desktop environment. Individual tools are selected according to their specific purpose, allowing each component to remain replaceable.

## License

This project is distributed under the license included in the repository.

## Author

**Carlos Souza**

GitHub: [@csouzape](https://github.com/csouzape)
