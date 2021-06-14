# TCC

This is an OpenGL examples project, you can cycle through many different examples and change settings to see how it affects the scene.

RoadMap:

- General
  - [x] Imgui integration
  - [x] Different files per scene
  - [x] Makefile
  - [ ] CMake/Premake files to create VS slns and Code Blocks Projects

---

- Demos
  - [x] Bezier Lines
  - [ ] Culling demo
  - [x] Matrix operations
  - [ ] Texture mapping
  - [x] Different shading techniques (Gourad, Phong, Flat)
  - [ ] Frustrum demo
  - [x] Lighting
  - [ ] Camera movement
  - [ ] 2D transformations
  - [ ] Normal mapping
  - [ ] Raycasting
  - [ ] Portals
  - [ ] Geometric Shaders
  - [ ] Simple 3D Modeling
  - [ ] Colliders

# Build

# Pre Requisites

- Download GLFW3 pre-compiled binaries ([here](https://www.glfw.org/download.html)) for the **same** version as your MinGW/VS version and put it at /lib.
- No specific IDE is necessary, you use either with makefile or Visual Studio / Code Blocks (projects solutions provided)

## Windows

Use VS to build for Windows (VS solution pending) or use [GNUWin Make](http://gnuwin32.sourceforge.net/packages/make.htm) and run `make`

## Linux

### Debian

In Debian run `sudo apt-get install libglfw3-dev` and then run `make`

### Arch

In Arch Linux run `yay -S glfw-x11` and run while in `bin` folder and then run `make`
