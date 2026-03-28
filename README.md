# Tutorial/Sandbox for using SDL

## Relevant Links
- [Compiling SDL using CMake](https://github.com/libsdl-org/SDL/blob/main/docs/INTRO-cmake.md)
- [List of basic SDL Examples](https://examples.libsdl.org/SDL3/renderer/05-rectangles/)
- [Making Games with SDL](https://www.noelberry.ca/posts/making_games_in_2025/)

## Settings up
Requirements:
- CMake
- SDL3

## Commands
Compile (executable will appear in ./build):

`cmake -S . -B build ; make -C build`

Run:

`./build/hello`