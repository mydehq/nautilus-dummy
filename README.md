<div align="center">
  <img src="icon.svg" height="75" alt="MyCTL Logo">
  <h1>nautilus-dummy</h1>
  <p><b>Dummy package to satisfy nautilus dependency</b></p>

This is a dummy package to satisfy nautilus dependency of many gnome components such as `xdg-desktop-portal-gnome`.

</div>

> [!WARNING]
> This package doesn't install the actual file manager. Must install any other file manager you want.  
> If intended for satisfying `xdg-desktop-portal-gnome` deps, please install `xdg-desktop-portal-gnome` too.  
> Then add [this](./portals.conf) to `.config/xdg-desktop-portal-gnome/portals.conf`.

---

## Installation

### Arch Linux

The package is available on the AUR:

#### 1. Using AUR Helper

```bash
# Using an AUR helper (e.g., yay, paru)
yay -S nautilus-dummy
# or
paru -S nautilus-dummy
```

#### 2. Manually

```bash
# Clone repo & cd into it
git clone https://aur.archlinux.org/nautilus-dummy && cd nautilus-dummy

# Build package
makepkg

# Install the package
sudo pacman -U nautilus-dummy-*.pkg.tar.zst
```

## Related Resources

- **Main Repository**: [mydehq/MyDE](https://github.com/mydehq/myde)
- **MyCTL Repository**: [mydehq/MyCTL](https://github.com/mydehq/myctl)
- **Wiki Repository**: [mydehq/MyWiki](https://github.com/mydehq/mydehq.github.io)

---

<div align="center">

**Made with ❤️ by the MyDE Team**

</div>
