# Omarchy Teal Theme

A dark, minimalist, and elegant theme created specifically for the Omarchy distribution. It is focused on productivity and visual comfort, featuring subtle teal accents.

![https://i.ibb.co/HpDyR36P/screenshot-2026-04-16-10-42-43.png](https://i.ibb.co/HpDyR36P/screenshot-2026-04-16-10-42-43.png)

## Color Palette

The theme was designed to be easy on the eyes during long working sessions, optimized for Hyprland and Wayland environments:

| Element | Color (Hex) |
|---------|-------------|
| **Background** | `#101315` |
| **Foreground** | `#cacccc` |
| **Accent (Teal)** | `#80b5b4` |
| **Muted/Borders**| `#a3a6a7` |

## Background

![https://i.ibb.co/1JpN7gqb/01-232-A2-E.png](https://i.ibb.co/1JpN7gqb/01-232-A2-E.png)

## Supported Applications

This theme provides complete and harmonious customization across the entire Omarchy ecosystem:
- **Hyprland**: Active and inactive border colors.
- **Waybar & Walker**: Top bar and application launcher styling with blur effects and visual accents.
- **Alacritty / Kitty / Ghostty**: Terminal emulator color schemes.
- **GTK 3/4**: System windows, dialogs, and buttons.
- **Btop & Cava**: System monitoring and audio visualizers.
- **Mako**: Notification daemon styling.
- **Chromium**: Browser theme integration.
- **Neovim**: Editor integration using the Ashen colorscheme.
- **Hyprlock**: Lock screen customization.

## Installation

To get the exact look from the screenshots, we recommend installing the specific GTK and Icon themes first, and then applying the Omarchy theme.

### Step 1: Install Recommended GTK & Icon Themes

Open your terminal and run the following commands to install the [Colloid Themes (by Vince)](https://github.com/vinceliuice) with the matching Teal accents.

**GTK Theme ([Colloid Dark Nord Teal](https://github.com/vinceliuice/Colloid-gtk-theme)):**

```bash
git clone https://github.com/vinceliuice/Colloid-gtk-theme.git
cd Colloid-gtk-theme
./install -t teal -c dark -s standard --tweaks nord black rimless normal
```

**Icon Theme ([Colloid Nord Teal](https://github.com/vinceliuice/Colloid-icon-theme)):**

```bash
git clone https://github.com/vinceliuice/Colloid-icon-theme.git
cd Colloid-icon-theme
./install -s nord -t teal -b
```

### Step 2: Install the Omarchy Theme

You can install the main Omarchy theme using two methods:

#### Method A: Via Terminal (Fastest)
Run the following command:

```bash
omarchy-theme-install https://github.com/marcosaugustoldo/omarchy-teal-theme
```

#### Method B: Via Omarchy Menu (GUI)
1. Press `Super + Alt + Space` to open the Omarchy control menu.
2. Navigate to `Install > Style > Theme`.
3. Paste the URL of this repository: `https://github.com/marcosaugustoldo/omarchy-teal-theme`.

## How to Apply the Theme

Once installed, you can activate the theme and its components:

1. **Apply the Omarchy Theme**: Hop directly to the theme selector using `Super + Ctrl + Shift + Space`. Select **Teal** (or the respective repository name) from the list.
2. **Apply GTK and Icons**: Use a tool like `nwg-look` (if available on your system) to set the GTK theme to **Colloid-Teal-Dark** and the Icon theme to **Colloid-teal-nord-dark**.
3. *Note for Obsidian users:* For Obsidian, you must manually select the Omarchy theme via Appearance > Themes inside the app.

## How to Uninstall

If you wish to remove the Omarchy theme from your system:
1. Open the Omarchy menu (`Super + Alt + Space`).
2. Navigate to `Remove > Style > Theme`.
3. Select the theme from the list to remove it.
