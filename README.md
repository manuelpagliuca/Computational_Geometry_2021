# Project for Computational Geometry course, @UNIMI AY 2020/2021 
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/manuelpagliuca/Computational_Geometry_2021/blob/main/LICENSE)
![APM](https://img.shields.io/appveyor/build/gruntjs/grunt)
![APM](https://img.shields.io/powershellgallery/p/DNS.1.1.1.1)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](mailto:pagliuca.manuel@gmail.com)

## Scope
This project was developed with the intent of study different techniques for the triangulations and tessellations of geometric shapes using OpenGL.

## Dependencies
- GLFW
- GLEW

Both of these libraries are integrated with CONAN, you must have installed [CMake](https://cmake.org/download/) and [CONAN](https://conan.io/downloads.html), then follow the installation instructions.

## Install

1. Access by terminal to the folder *'Computational_Geometry'*.
2. Then run this command:

>```cmake src -DCMAKE_BUILD_TYPE=Release -B ../build/```

3. Once the process is over move to the folder *'../build'*, and run this command:

>```make```

4. Once the building is over, copy the executable file *'/bin/Application'* inside the folder  *'Computational_Geometry_2021/Computational_Geometry/'*.

5. Move to the folder where it is the executable now, in *'Computational_Geometry_2021/Computational_Geometry/'*.

6. Run the command:

>```./bin/Application```
