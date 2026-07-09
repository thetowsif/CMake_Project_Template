# CMake Project Template

This repository is a starter template for a simple C++ project built with CMake.

## Getting Started

If you want to begin from a completely clean state, remove any generated build files from a previous run first:

```bash
rm -rf build CMakeCache.txt CMakeFiles cmake_install.cmake Makefile
```

Then configure and build the project from the repository root:

```bash
cmake -S . -B build
cmake --build build
```

## Run

After a successful build, run the executable from the build directory:

```bash
./build/MyApp
```

## Use This Template

1. Replace the project name in `CMakeLists.txt` with your own name if needed.
2. Add new source files under `src/`.
3. Add public headers under `include/`.
4. Re-run `cmake -S . -B build` whenever you change the CMake configuration or add/remove source files.
5. Build again with `cmake --build build`.

## Clean Rebuild

If the build becomes inconsistent, delete the generated files and configure again:

```bash
rm -rf build CMakeCache.txt CMakeFiles cmake_install.cmake Makefile
cmake -S . -B build
cmake --build build
```