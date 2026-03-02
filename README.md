**TESTED IN A VM***

# Linux Gamer Life Fedora KDE Bootstrap with CachyOS Kernel and Addons (TTY Friendly)

# AMD Only at the moment - Select no at AMD section if not on AMD [UNTESTED]
# DISABLE SECURE BOOT IN THE BIOS

This repository contains a one-shot bootstrap script that converts a fresh Fedora Everything Minimal install into a complete KDE Plasma desktop with the CachyOS Kernel and kernel addons. Includes gaming, multimedia, Flatpak, virtualization, and development tooling.

Install Fedora Everything and select minimal install.
Run script once from TTY. Reboot. Done.

---

# Quick Start

Download and run scipt locally:

```bash
sudo dnf install wget
wget https://tinyurl.com/lgl-fedora-cachyos
chmod +x lgl-fedora-bootstrap.sh
sudo ./lgl-fedora-bootstrap.sh
```

Reboot when complete:

```bash
reboot
```

---

# Overview

This script installs and configures the following components.

KDE Plasma desktop  
SDDM display manager enabled  

RPM Fusion repositories  
Cisco OpenH264 repository  

Python tooling  
python3  
pipx  
tldr  
yt-dlp  

Multimedia stack  
ffmpeg  
GStreamer plugins  
OpenH264  
VA-API support  
VLC  

Gaming tools  
Steam  
OBS Studio  
Lutris  
MangoHud  

Flatpak and applications  
Flatpak  
Flathub  
Flatseal  
ProtonUp-Qt  
ProtonPlus  
Heroic Games Launcher  
LibreOffice  

Virtualization  
virt-manager  
libvirt  
qemu-kvm  
OVMF  
swtpm  

Kernel  
CachyOS kernel
CachyOS Addons
scxctl scheduler interface  

System tweaks  
Disables NetworkManager-wait-online  
Sets graphical target  

Cleanup  
Removes unused dependencies  
Cleans package cache  

---

# Requirements

Fedora Everything Minimal  
Internet connection  
User with sudo privileges  
Run from TTY  

---

# Notes

This script is provided as-is and Linux Gamer Life accepts no risk if you break your system using it.
