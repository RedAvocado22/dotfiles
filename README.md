# dotfiles

My personal dotfiles for Hyprland on Fedora 44.

## Setup

| Component | Detail |
|---|---|
| OS | Fedora 44 |
| WM | Hyprland |
| Shell | Caelestia (Quickshell) |
| Terminal | Kitty |
| Font | CaskaydiaCove NF / JetBrains Mono / Rubik |
| Audio | PipeWire + EasyEffects |

## Structure

```
dotfiles/
├── hypr/          # Hyprland config (keybinds, monitors, autostart)
├── caelestia/     # Caelestia shell config (theme, wallpaper, GIFs)
└── wireplumber/   # WirePlumber audio rules (Bluetooth volume fix)
```

## Notes

- Caelestia shell requires building from source: [caelestia-dots/shell](https://github.com/caelestia-dots/shell)
- Monitors: Xiaomi 24" HDMI @ 100Hz + Laptop eDP @ 240Hz
- Bluetooth audio fix: sets M106BT volume to 100% on connect
