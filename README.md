# sigil-arx-270326
Arcanorum | [Arch@KDE]$> eDEX-UI; UFW + DNS/TLS; | I5-12400f; GTX 1080; 24GB | MMXXVI


Dotfiles from the Arch build of 27 March 2026.

## Contains

- **Shell:** bash
- **Editor:** VS Code (Flatpak)
- **Terminal:** eDEX-UI, Kitty, Konsole
- **Desktop:** KDE Plasma, Hyprland
- **Security:** UFW, DNS-over-TLS, Bitwarden
- **Gaming:** Steam, Lutris, Wine, PrismLauncher

## Rebuild

```bash
# Install explicit packages
sudo pacman -S --needed - < pkglist.txt

# Install AUR packages
yay -S --needed - < pkglist-aur.txt

# Install Flatpaks
flatpak install $(cat flatpaks.txt)
```
