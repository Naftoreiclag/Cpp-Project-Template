# C++ Project Template

This is my personal template for new C++ projects.

## Description

This is my personal template for creating new C++ projects. Included are my
collection of CMake modules and Python scripts that I use to automate source
code maintenance and building. Go ahead and use this template if you like it,
although I find that possibility unlikely.

## Miscellaneous

The `rm_template.md` is my template for making README files.

### Utilities

In the `tool/` directory are Python scripts that you may find useful:
- `GenerateSrcLists.py` populates the cmake files 
  `cmake/MainSrcList.cmake` and `cmake/TestSrcList.cmake` from the contents 
  of the `src/` directory.
- `SyncEngineCodelite.py` populates a [Codelite](https://codelite.org/)
  project file (by default, `ide/Codelite/Codelite.project`).
- `RefactorHeaderIncludes.py` was used to refactor older source and header
  files to use the new source folder format.

### License

Source code files in this repository for which I, James Fong, am the copyright 
holder are distributed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
A copy of this license is available in the `LICENSE` file located in the
root of this repository.

Included in this repository may be source code for other open-source projects
that are embedded in this project. This source code for such third-party
projects is available in the `src/thirdparty` subdirectory. 
Such projects may be subject to different licensing terms. Please see 
individual files for details.

Files found outside the `src/` repository, including but not limited to those
located in the `cmake/` directory, may also be subject to different licensing
terms. See individual files for details.
