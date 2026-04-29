# CppAD Windows Build Guide

- remove PkgConfig dependency when checking Eigen
- add `/MDd` option in cxx_flag in bin/build.bat (the default value in a new cmake/vs project)
- change `check` to `install`
- in x64 Native Tools Command Prompt for VS, cd into this directory and run
  ```
  cmd /c bin\build.bat
  ```
- just copy the installed folder to your project folder and add include/library as usual
- make sure that Eigen is in your project's include directory
