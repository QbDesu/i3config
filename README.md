# Qb's ~~Sway~~ I3WM Config

## Required Dependencies

* ~~sway~~ i3-gaps - obviously
* ~~wofi~~ rofi - as the application launcher
* PulseAudio / Pipewire-Pulse - for volume/mute media keys to function (using pactl)
* brightnessctl - for brightness up/down media keys to function
* playerctl - for play/pause/stop media keys to function
* systemd - for sleep/standby to function
* systemd-logind xss-lock ~~swaylock-effects~~betterlockscreen - for screen locking to function
* xdg-desktop-portal and xdg-desktop-portal-~~wlr~~gtk - for ~~screensharing~~xdg-portal-stuff
* ~~grimshot~~Spectacle - for screenshots
* ~~pasystray-wayland - for audio control tray icon~~ for preventing remembering the default audio devices
* network-manager-applet - for network control tray icon
* udiskie - for removable drive control tray icon
* 

## Under Consideration

* dex - for autostarting of .desktop files

## Keyboard Layout

* the keyboard layout is set externally using the `XKB_DEFAULT_LAYOUT` environment variable, as well as the `XKB_DEFAULT_MODEL`, `XKB_DEFAULT_VARIANT`, and `XKB_DEFAULT_OPTIONS` environment variables.
