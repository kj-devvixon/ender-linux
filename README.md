# Ender Linux

A simple, Arch-based Linux distribution focused on clean installation experience.

## Features
- Based on Arch Linux — follow the Arch wiki for everything
- KDE Plasma, XFCE, LXQt, Hyprland and more available via archinstall
- ZRAM pre-configured for better RAM performance
- Firewalld pre-enabled for security
- Ananicy-cpp for automatic process priority
- Reflector for automatic mirror optimization
- Rolling release via Arch repos

## Building the ISO
```bash
git clone https://github.com/kj-devvixon/ender-linux
cd ender-linux
sudo mkarchiso -v .
```

## Installation
Boot the ISO and type:
```bash
archinstall
```

## Credits
Built with archiso by kj-devvixon
Arch linux distribution for base (ily arch)
