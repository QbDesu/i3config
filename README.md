# Qb's Sway Config

## Required Dependencies

* sway - obviously
* ulauncher - as the application launcher
* PulseAudio / Pipewire-Pulse - for volume/mute media keys to function (using pactl)
* brightnessctl - for brightness up/down media keys to function
* playerctl - for play/pause/stop media keys to function
* systemd - for sleep/standby to function
* systemd-logind xss-lock swaylock - for screen locking to function
* xdg-desktop-portal and xdg-desktop-portal-wlr - for screensharing

## Under Consideration

* dex - for autostarting of .desktop files

## Keyboard Layout

* the keyboard layout is set externally using the `XKB_DEFAULT_LAYOUT` environment variable, as well as the `XKB_DEFAULT_MODEL`, `XKB_DEFAULT_VARIANT`, and `XKB_DEFAULT_OPTIONS` environment variables.
