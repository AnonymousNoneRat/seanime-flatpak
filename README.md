# Seanime Flatpak

Unofficial Flatpak packaging of [Seanime](https://seanime.app) - a self-hosted anime and manga media server with a desktop app.

## Installation

Download the latest `Seanime.flatpak` from [Releases](https://github.com/AnonymousNoneRat/seanime-flatpak/releases) and install:

```bash
flatpak install --user ~/Downloads/Seanime.flatpak
```

Or run directly:

```bash
flatpak run io.github.seanime.Seanime
```

## Features

- ✅ Automatic updates via built-in updater (disabled - use `flatpak update` instead)
- ✅ Wayland and X11 support
- ✅ Sandboxed with tight permissions
- ✅ Auto-builds when new Seanime versions release

## Permissions

- Network access
- Home directory access (for media libraries)
- Notifications
- GPU acceleration

## Updating

This Flatpak auto-updates daily. To manually check for updates:

```bash
flatpak update
```

## Disclaimer

This is an **unofficial** community package. Seanime is developed by [5rahim](https://github.com/5rahim/sean)
