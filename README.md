# BBJ Arch Repository

Personal Arch Linux package repository with custom builds.

## Packages

- **flameshot-wayland-fix** - Flameshot with QPainter Wayland crash fix

## Usage

Add to `/etc/pacman.conf`:

```ini
[bbj-repo]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/benignobjunior/arch-repo/main/x86_64
```

Then:
```bash
sudo pacman -Sy flameshot-wayland-fix
```

## Note

This is a private repository. Access requires GitHub authentication.
