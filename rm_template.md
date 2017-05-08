# myproject

Insert short tagline or description here.

## Description

This is myproject.

Planned features include:
- Improved features
- Extra features
- More features

### License

myproject source code, which is located in the `src/` directory,
is proudly licensed under the 
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
A copy of this license is available in the `LICENSE` file located in the
root of this repository.

Files found outside the `src/` repository, including but not limited to those
located in the `cmake/` directory, may be subject to different licensing
terms. Please see individual files for details.

## Building & Running

myproject uses [CMake](https://cmake.org/) for build configurations.

### Dependencies

myproject requires the following libraries to be built correctly.

- [OpenGL](https://www.opengl.org/) or [Vulkan](https://www.khronos.org/vulkan/)
  for rendering
- [SDL2](https://www.libsdl.org/) or [GLFW](http://www.glfw.org/)
  for windowing and event handling
- [Lua](http://www.lua.org/)
  for scripting
- [libsoundio](http://libsound.io)
  for sound
- [Boost](http://www.boost.org/)
  for all-around usefulness
- [Bullet Physics](http://bulletphysics.org/)
  for 3D collision resolution, 3D physics
- [JsonCpp](https://github.com/open-source-parsers/jsoncpp/)
  for serialization, config files
- [stb](https://github.com/nothings/stb)
  for image loading

*Each library listed above is the copyright of its respective author(s). Please
see individual library homepages for more accurate licensing information.*

### Runtime Environment

By default, myproject expects its runtime environment to be set up such that:
- `<home>/user/` contains all player-specific data
- `<home>/user/addons/` contains all addons that can be loaded
- `<home>/resources/` contains all essential engine resources

`<home>` is by default `../`.

## Miscellaneous

### Utilities

In the `tool/` directory are Python scripts that you may find useful:
- `GenerateEngineSrcList.py` populates the cmake file 
  `cmake/EngineSrcList.cmake` from the contents of the `src/` directory.
- `SyncEngineCodelite.py` populates a [Codelite](https://codelite.org/)
  project file (by default, `ide/Codelite/Codelite.project`).
- `RefactorHeaderIncludes.py` was used to refactor older source and header
  files to use the new source folder format.

