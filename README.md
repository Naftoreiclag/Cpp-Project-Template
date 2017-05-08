# C++ Project Template

Insert short tagline or description here.

## Description

This is my personal template for creating new C++ projects. Included are my
collection of CMake modules and Python scripts that I use to automate source
code maintenance and building. Go ahead and use this template if you like it,
although I find that possibility unlikely.

### License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
A copy of this license is available in the `LICENSE` file located in the
root of this repository.

## Building & Running

myproject uses [CMake](https://cmake.org/) for build configurations.

### Dependencies

myproject requires the following libraries to be built correctly.

- [Example](http://www.example.org/)
  for something
- [AnotherExample](http://www.example.org/)
  for something else

*Each library listed above is the copyright of its respective author(s). Please
see individual library homepages for more accurate licensing information.*

### Runtime Environment

By default, myproject expects its runtime environment to be set up such that:
- `<home>/user/` contains all player-specific data
- `<home>/user/addons/` contains all addons that can be loaded
- `<home>/resources/` contains all essential engine resources

`<home>` is by default `../`.

## Miscellaneous

The `rm_template.md` is my template for making README files.

### Utilities

In the `tool/` directory are Python scripts that you may find useful:
- `GenerateEngineSrcList.py` populates the cmake file 
  `cmake/EngineSrcList.cmake` from the contents of the `src/` directory.
- `SyncEngineCodelite.py` populates a [Codelite](https://codelite.org/)
  project file (by default, `ide/Codelite/Codelite.project`).
- `RefactorHeaderIncludes.py` was used to refactor older source and header
  files to use the new source folder format.



