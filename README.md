# Waybar Configuration
## Features

- **Hyprland Workspaces**: Elastic pill animations with numbered icons
- **Calendar tooltip**: The calendar can be viewed from the time module's tooltip
- **NetworkManager connectivity**

## Installation

1. Clone configuration files to `~/.config/waybar/`
2. Restart waybar: `pkill waybar && waybar &`

- For omrachy users, simply `Super + Shift + Space` to restart waybar

## Configuration

- `config.jsonc`: Main module configuration and settings
- `style.css`: Visual styling and animations
- Theme integration via `../omarchy/current/theme/waybar.css`

## Dependencies

- Hyprland window manager
- Nerd Font icons (CaskaydiaMono Nerd Font), though you could any nerd font
- PulseAudio for audio control
- NetworkManager for network status
