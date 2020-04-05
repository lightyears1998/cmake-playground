# Readme

## Build

Install CMake first.

```powershell
mkdir _builds # Stores CMake generated native tool files

cmake --help # Take a look at "GENERATORS" section

# Run the following batch file from cmd to setup complier for VS2017
# "C:\Program Files (x86)\Microsoft Visual Studio\2017\BuildTools\VC\Auxiliary\Build\vcvars64.bat"

cmake -S . -B _builds -G "Visual Studio 15 2017 Win64"
cmake --build _builds
```
