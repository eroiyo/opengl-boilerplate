# OpenGL Cross Platform
## WELCOME TO MODERN OPENGL CROSS PLATFORMS
### In this github repository you can easily setup OpenGL on diffrent Operating Systems like
### Windows,MacOS and Linux so feel free to use it and build it quickly on Your OS.
#### it includes specific libraries like glfw,glad,imgui,stb_image,glm and assimp.
# 1. Setup on Windows

### You should have this things
1. MinGW Compiler https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/8.1.0/
2. Cmake https://cmake.org


### Download github repo or clone it
### Open Terminal in the project
### Then type 
$`cmake -S . -B ./build/ -G "MinGW Makefiles" -D GLFW_BUILD_DOCS=OFF`
### Then goto the built dir
$`cd ./build/`
### Then type
$`make` or `mingw32-make` or `cmake --build .`
### Wait until every thing is done
$`./OpenGL`

# 2. Setup on Linux 

$`sudo apt-get update`
### You should already have this things

1- $`sudo apt install gcc`
2- $`sudo apt install cmake`

### download x11 ,libxrandr ,libxinerama ,libxcursor and libxi.
$`sudo apt-get install libx11-dev`
$`sudo apt-get install -y libxrandr-dev`
$`sudo apt-get install libxinerama-dev`
$`sudo apt-get install libxcursor-dev`
$`sudo apt-get install libxi-dev`

### Update
$`sudo apt-get update`

### Then Download glfw
$`sudo apt-get install libglfw3 libglfw3-dev`

### Download github repo or clone it
$`git clone https://github.com/glULTRA/OpenGL-Cross-Platform.git`

### Open Terminal in the project
$`cd OpenGL-Cross-Platform/`
### Then type 
$`cmake -S . -B ./build/ -G "Unix Makefiles" -D GLFW_BUILD_DOCS=OFF`
### Then goto the built dir
$`cd ./build/`
### Then type
$`make` or `cmake --build .`
### Wait until every thing is done
$`./OpenGL`


# 3. Setup on MacOS 
### You should already have this things

1- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)`
2- `brew install gcc`
3- `brew install cmake`

### First download glfw
$`brew install glfw`
### Download github repo or clone it
### Open Terminal in the project
### Then type 
`cmake -S . -B ./build/ -G "Unix Makefiles" -D GLFW_BUILD_DOCS=OFF`
### Then goto the built dir
`cd ./build/`
### Then type
`make` or `cmake --build .`
### Wait until every thing is done
`./OpenGL`
