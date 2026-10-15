# GNOME Resources 1.10.2 for Debian 13 ARM64

A Debian 13 ARM64 build of [Resources](https://gitlab.gnome.org/GNOME/Incubator/resources), the GNOME system monitor.

This build is based on **Resources 1.10.2** and is adapted to work with **libadwaita 1.7**, as included with Debian 13.

A native DEB uses the libraries already provided by Debian, avoiding the additional Flatpak runtime or Snap infrastructure. This can reduce disk usage and overhead, which is particularly useful on Raspberry Pi systems.

<img alt="image" src="https://github.com/user-attachments/assets/95df6a8e-bf23-4f2e-b543-22c404bc0acd" />

I mainly made this package for my own Raspberry Pi / GNOME setup, but it may also be useful for other Debian 13 ARM64 users.

## Install

Download the `.deb` package and install it with:

```bash
wget -O install-resources.deb 'https://github.com/wobbo/gnome-resources/releases/download/v1.10/resources_1.10.2-1.deb13_arm64.deb'
sudo apt install ./install-resources.deb
```

After installation, open **Resources** from the GNOME application menu or run:

```bash
resources
```

## Credits

Resources is created and maintained by the original Resources developers.

Upstream project:

https://gitlab.gnome.org/GNOME/Incubator/resources

This repository only provides an unofficial Debian 13 ARM64 build/backport. I do not claim ownership of the Resources application itself.
