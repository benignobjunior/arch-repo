# BBJ Arch Repository

Personal Arch Linux package repository with custom builds.

## Packages

| Package | Version | Description |
|---------|---------|-------------|
| flameshot | 13.3.0-2 | With Wayland QPainter crash fix (PR #4496) |

## Usage

Add to `/etc/pacman.conf` (before other repos):

```ini
[bbj-repo]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/benignobjunior/arch-repo/main/x86_64
```

Then:
```bash
sudo pacman -Sy flameshot
```
