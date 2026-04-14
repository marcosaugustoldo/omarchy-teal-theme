# Teal for Omarchy

> Aesthetics are not just a superficial detail; they are fundamental. A beautiful system is a motivating system, and productivity has always been downstream from motivation.

**Teal** is a unified, monochromatic theme built for the [Omarchy](https://github.com/basecamp/omarchy) distribution. It was designed under a relentless philosophy of noise reduction. While traditional systems use a rainbow of colors that often distract, Teal operates with surgical precision, highlighting only what truly requires your attention and interaction.

## The Palette

The palette is lean, intentional, and focused on visual comfort for long development sessions.

* **Void (`#101315`):** The absolute background. A secure darkness that anchors the entire interface without straining the eyes.
* **Dust (`#cacccc`):** The primary text and foreground. High contrast against the background, perfect for reading code and documentation.
* **Whisper (`#a3a6a7`):** Borders, dividers, secondary text, and code comments. It subtly absorbs the background using modern CSS `color-mix` transparencies.
* **Focus (`#80b5b4`):** Our signature Teal. The system's only real color, used for links, cursors, selections, syntax keywords, and interactive elements.

## Supported Ecosystem

Teal is more than just a terminal color scheme; it is a visual injection across the entire OS stack and user-space.

### Terminals & TUI
* **Alacritty:** The default Omarchy terminal, optimized for speed.
* **Kitty & Ghostty:** Modern alternatives with GPU acceleration supported by Omarchy.
* **Btop:** System monitor with custom gradients.
* **Cava:** TUI audio visualizer.

### Editors & Productivity
* **Obsidian:** Custom theme with softened borders and semantic markdown styling.
* **Sublime Text 4:** Native `.sublime-color-scheme` focused on dual-color hierarchy.
* **Neovim:** Implicit support mapped through the *Ashen* base theme.

### System & Interfaces (Wayland/Hyprland)
* **GTK 3/4:** Native windows, dialog popups, and file choosers.
* **SwayOSD:** Volume and brightness indicators.
* **Hyprland Ecosystem:** Global variables propagated via `colors.toml`.

### Third-Party Apps
* **Discord / Vencord:** CSS injection via base variables.
* **Steam:** RGB variable injection bypassing default themes.

## Installation

Omarchy makes it easy to install and manage extra themes. To apply the Teal theme to your system, run the following command in your terminal:

```bash
omarchy-theme-install https://github.com/marcosaugustoldo/omarchy-teal-theme.git
```

### Activation
1.  Open the Omarchy Menu with `Super + Alt + Space`.
2.  Navigate to **Style > Theme**.
3.  Select **Teal** from the list.
4.  *Optional:* To cycle through theme-specific backgrounds, use `Super + Ctrl + Space`.

*Built for those who take their craft seriously.*
