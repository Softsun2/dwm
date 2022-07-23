# My wip build of dwm

Some features rely on scripts that live ![here](https://github.com/Softsun2/dotfiles-NixOS/tree/main/bin).

I use the windows key as the mod key.


## Todo
* Autostart or initial theme loading
* bar only redraws on active monitor


## Tweaks

* bottom bar/dmenu
* middle section of bar on selected monitor uses the normal scheme rather than the selected scheme
* theme loading, uses ![this script](https://github.com/Softsun2/dotfiles-NixOS/blob/main/bin/themecontrol).


## ![Patches](patches)

* xrdb - runtime colors
* actualfullscreen - better fullscreen
* pertag - pertag layouts

## New binds

```
mod + shift + m     : mute audio
mod + shift + up    : increase audio
mod + shift + down  : decrease audio
mod + shift + right : increase brightness
mod + shift + left  : decrease brightness
mod + F5            : load current theme
mod + shift + f     : toggle application fullscreen
```