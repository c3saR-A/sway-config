# *sway-config*

Config files for Sway a tiling Wayland compositor & Niri a scrollable tiling Wayland compositor.

### Why I Do This

Currently, as I write this, I am a relatively new user of the Free Open-Source world and GNU/Linux.
I started with Ubuntu 25.10 on a Desktop PC, then on a laptop from 2015-2016 with MX Linux.
Since then, I have learned and understood many things, and I wanted to try a Wayland Window Managers (WM) like:
- `Sway`
- `Niri`
- `MangoWC`
- `Hyprland`
- More...

This is a personal project, and I hope if anyone reads this, it will be useful and give you new ideas, like me when I looked up for many things. Thanks.

## What's install?

| Component | Purpose |
| --------- |-------- |
| `sway` | A tiling Wayland compositor |
| `swayidle` | Idle daemon |
| `swaybg` | Wallpaper/Background |
| `waybar` | Customizable Wayland bar |
| `greetd` | Login manager daemon |
| `gtkgreeter` | A gtk based greeter for greetd |
| `gtklock` | Lock screen |
| `wofi` | Launcher / more function coming soon |
| `wezterm`, `foot` | Terminals (wezterm main, foot lightweight/default in sway) |
| `nala` |  Command line frontend for the APT package manager| 
| `thunar` | A file manager |
| `yazi` | A terminal file manager |
| `pipewire` | Audio and video processing engine |
| `brightnessctl`  | Brightness controler |
| `cliphist` + `wl-clipboard` | Clipboard history |
| `helvum` | GTK patchbay for pipewire |
| `pavucontrol` | Based volume control tool |
| `grim` + `slurp` | Screenshot tools |
| `swappy` | A Wayland native snapshot and editor tool |
| `nwg-look` | GTK3 settings editor for wlroots environments |
| `loupe` | A image viewer|
| `gnome-text-editor` | A text editor|
| `mpv` | Video player |
| `tlp` | Optimize laptop battery life |
| `xdg-desktop-portal/-wlr/-gtk`| Wayland portals for sway|
| `nmtui` | TUI for controlling NetworkManager |
| `bluetoothctl` | Bluetooth Control Command Line Tool (rarely used, there are better opt)|

## Keybinding

| Key Combo | Action |
|-----------|--------|
| `Super + t` | Launch terminal |
| `Super + q` | Close focused window |
| `Super + Space` | App launcher |
| `Super + e` | Launch file manager |
| `Super + Shift + r` | Reload Sway config |
| `Super + Shift + w` | Reload waybar |
| `Super + Shift + q` | Exit Sway |
| `Super + h/j/k/l` or `Super + arrows` | Move the focus in windows |
| `Super + Shift + h/j/k/l` or `Super + Shift + arrows` | Move the focus windows |
| `Super + 1-9/0` | Switch to workspace 1-10 |
| `Super + Shift + 1-9/0` | Move focus windows to workspace 1-10 |
| `Super + b` | Split vertical |
| `Super + v` | Split horizontal |
| `Super + w` | Toggle split |
| `Super + f` | Fullscreen |
| `Super + Shift + space` | Floating toggle |
| `Super + a` | Focus all windows |
| `Super + Shift+minus` | move to scratchpad |
| `Super + minus` | scratchpad show |
| `Super + r` | "resize" mode |
| `Return` or `Escape` | On "resize" mode return to "default" mode |
| `Print` | Take full screenshot |
| `Super + Print` | Take screenshot of selected area |
| `Super + Shift + Print` | Take screenshot of focus window |
| `Ctrl + Print` | Take full screenshot and copy to clipboard |
| `Ctrl + Super + Print` | Take screenshot of selected area and copy to clipboard |
| `Ctrl + Alt + Print` | Take screenshot of focus window and copy to clipboard |
| `Super + Shift + s` | Open Swappy with the screenshot on the clipboard |

## To Do

- [x] Update keybind table
- [ ] Config greeetd & gtkgreet
- [ ] Config gtklock
- [ ] Config change background with wofi + swaybg
- [ ] Config history with cliphist + wofi
- [ ] Install some notification daemon
- [ ] Explain `nl` command, use and relation with nwg-display and 30-outputs.conf

## Soon or Later

I have many things to add and do like improving and add the missings things in this repo, also in mi systems I have a greeter and lock screen, but it doesn't have a style just default and more missings tools, but step-by-step I will keep going, **see you soon.**

### Thanks To
by now this is a secret ;]
