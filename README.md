# procedural-wallpaper-renderer
WIP! This is a Wayland procedural wallpaper renderer supporting OpenGL.

## Supported Compositors

The renderer supports all compositors implementing the wlr-layer-shell-unstable-v1 protocol.
These include:
- All compositors based on wlroots, such as Sway, Hyprland, Wayfire, River, and Labwc.
- All compositors based on Smithay, such as Niri and Cosmic (Pop!_OS).
- All other compositors independently implementing wlr-layer-shell-unstable-v1.

This list may contain errors.
If this doesn't work on one of the listed compositors,
or a working compositor is not listed, please open a PR or an issue
and I will change the list to be more specific.
