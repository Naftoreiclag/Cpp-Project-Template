# C++ Project Template

This is my personal template for new C++ projects.

## Description

This is my personal template for creating new C++ projects. Included are my
collection of CMake modules and Python scripts that I use to automate source
code maintenance and building. Go ahead and use this template if you like it,
although I find that possibility unlikely.

### License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
A copy of this license is available in the `LICENSE` file located in the
root of this repository.

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



