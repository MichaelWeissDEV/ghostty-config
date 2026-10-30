# Ghostty configuration

GPU-Terminal mit Catppuccin Mocha, transparenter Darstellung und Zsh.

**[Vollständige Dokumentation](https://ghostty-config.readthedocs.io/en/latest/)** ·
[Arch-Paket](https://ghostty-config.readthedocs.io/en/latest/packages/) ·
[Dotfiles-Handbuch](https://arch-dotfiles.readthedocs.io/en/latest/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- ghostty
```

Paket: `arch-dotfiles-ghostty`. Einstellungen: `~/.config/ghostty/config`.
Konfiguration, Tastenkombinationen und Standalone-Installation stehen im Handbuch.
Entwicklung erfolgt in diesem eigenständigen Repository; Pushes auf `main` werden
von der Registry geprüft und gebaut. Updates: `sudo pacman -Syu`.
Lokale Builds: [PACKAGING.md](PACKAGING.md).

[![Package safety](https://github.com/MichaelWeissDEV/ghostty-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/ghostty-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
