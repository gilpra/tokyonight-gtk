# Tokyonight GTK

A minimal GTK theme based on the [Tokyo Night](https://github.com/folke/tokyonight.nvim) **Night** color palette, designed for tiling window managers.

---

## Compatibility

- GTK 3.0
- GTK 4.0

Designed for use with window managers (Sway, Hyprland, i3, etc.).

---

## Dependencies

The `index.theme` references these companion themes. Install them for the full look:

- **Icon theme** - [Tela Circle Dark](https://github.com/vinceliuice/Tela-circle-icon-theme)
- **Cursor theme** - [Bibata Modern Ice](https://github.com/ful1e5/Bibata_Cursor)

---

## Installation

### Import

```bash
# System-wide (requires root)
sudo cp -r tokyonight-night-gtk /usr/share/themes/

# Per-user (recommended)
cp -r tokyonight-night-gtk ~/.local/share/themes/
```

### Apply the theme

**Using `gsettings`:**

```bash
gsettings set org.gnome.desktop.interface gtk-theme "Tokyonight-Night"
```

**Using `nwg-look` (recommended for Wayland/WMs):**

```
nwg-look
```

Select **Tokyonight-Night** from the theme list and apply.

**Manual config (`~/.config/gtk-3.0/settings.ini`):**

```ini
[Settings]
gtk-theme-name=Tokyonight-Night
gtk-icon-theme-name=Tela-circle-Dark
gtk-cursor-theme-name=Bibata-Modern-Ice
gtk-font-name=0xProto Nerd Font 11
```

**For GTK 4 (`~/.config/gtk-4.0/settings.ini`):**

```ini
[Settings]
gtk-theme-name=Tokyonight-Night
gtk-icon-theme-name=Tela-circle-Dark
gtk-cursor-theme-name=Bibata-Modern-Ice
```

---

## License

This project is open source. Feel free to fork, modify, and use it in your own setup.

