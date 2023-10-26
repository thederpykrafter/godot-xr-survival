# Godot XR Survival

![GitHub forks](https://img.shields.io/github/forks/thederpykrafter/godot-xr-survival?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/thederpykrafter/godot-xr-survival?style=plastic)
![GitHub contributors](https://img.shields.io/github/contributors/thederpykrafter/godot-xr-survival?style=plastic)
![GitHub](https://img.shields.io/github/license/thederpykrafter/godot-xr-survival?style=plastic)

This repository is meant to serve as a learning experience for me using Godot for building a simple VR game.
## Versions

Official releases are tagged and can be found [here](https://github.com/thederpykrafter/godot-xr-survival/releases).

The following branches are in active development:
|  Branch  |  Description                  |  Godot version  |
|----------|-------------------------------|-----------------|
|   main   | Current stable branch    |  Godot 4.2 Beta 1     |
|    dev   | Current development branch  |  Godot 4.2 Beta 1     |

After cloning this repository you will need to install the OpenXR plugin for it to work. The OpenXR plugin is not included within this repository.
You can obtain the OpenXR plugin [here](https://github.com/GodotVR/godot_openxr/releases) or download it from the asset library within Godot.

### XR Tools library

To obtain just the XR Tools library for your own project, please check [releases](https://github.com/GodotVR/godot-xr-tools/releases) or download it from the asset library within Godot.

### Preventing hickups

As many of the functions in this module will hide objects that are later shown as the user performs actions, the user will experience a hickup as Godot compiles the shader used to draw the object on screen. 
To combat this you will find a scene in this module called `misc/VR_Common_Shader_Cache.tscn`.
Add this scene as a child node to your ARVRCamera. This will trigger the required shaders being
compiled the first time your main scene loads.

## Licensing

Code in this repository is licensed under the MIT license.
Images are licensed under CC0 unless otherwise specified.

See the full license inside of the addons folder.

## About this repository

This repository was created from th XR Tools Demo by Bastiaan Olij a.k.a. Mux213

It is primarily maintained by:
- [Bastiaan Olij](https://github.com/BastiaanOlij/)
- [Malcolm Nixon](https://github.com/Malcolmnixon/)

For further contributors please see `CONTRIBUTORS.md`

Further resources:
- [Bastiaan Olij on Twitter](https://twitter.com/mux213) for regular updates
- [Bastiaan Olij on Youtube](https://www.youtube.com/BastiaanOlij) for tutorials
- [Malcolm Nixon on Youtube](https://www.youtube.com/user/MalcolmANixon) for demonstrations of Godot XR Tools.
