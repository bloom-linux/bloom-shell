# bloom-shell

The Bloom Linux desktop shell — dynamic island topbar, EWW widgets, and theme generation tools.

Includes:
- **bloom-island** — Starts the EWW island/topbar overlay
- **bloom-generate-colors** — Generates accent color tokens from wallpaper
- **bloom-generate-icons** — Generates app icon cache for the island
- **bloom-generate-cursors** — Applies cursor theme
- **bloom-get-icon** — Resolves app icon paths
- **eww/** — EWW widget config (island layout, topbar, media, notifications)

## Install

```
pacman -S bloom-shell
```

## Dependencies

`eww` `hyprland` `playerctl` `jq` `imagemagick` `swaync`
