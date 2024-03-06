# GLSL-Dynamic-Grain
GLSL Shader for Dynamic Grain


This is a dynamic and subtle colored grain, the color is based from the video where the grain will be added.

This is primarly made for MPV.

# Installation
**Put it in `shaders` folder in MPV**

You can also use it in Plex, place it in the sahder folder located in `%localappdata%\Plex`.

To load it automatically with mpv, edit mpv.conf and add

`glsl-shaders="~~/shaders/filmgrain.glsl"`

You can also add a key shortcut in input.conf, eg:

`CTRL+4 no-osd change-list glsl-shaders set "~~/shaders/filmgrain.glsl"; show-text "Dynamic Grain Activated"`
