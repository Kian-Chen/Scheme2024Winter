#   CMake

CMake is a cross-platform build system generator. It is used to build, test, and package software. It is widely used in the open-source community and is used in many popular projects such as OpenCV, VTK, and ITK.

## Installing CMake

To install CMake, you can download the installer from the official website: https://cmake.org/download/.

## Using CMake

To use CMake, you need to create a `CMakeLists.txt` file in the root directory of your project. This file contains all the instructions for building your project.

Here is a basic example of a `CMakeLists.txt` file:

```
cmake_minimum_required(VERSION 3.10)

project(MyProject)

set(CMAKE_CXX_STANDARD 11)

add_executable(MyProject main.cpp)
```

In this example, we set the minimum required version of CMake to 3.10, set the project name to "MyProject", set the C++ standard to 11, and add an executable target called "MyProject" that compiles the "main.cpp" file.

To build the project, you can run the following command in the terminal:

```
cmake .
```

This will generate the necessary build files for your project in a directory called "build". You can then run the build process by running:

```
cmake --build .
```

This will build the project and create an executable file in the "build" directory. You can then run the executable to run your program.

## Resources

- [CMake Homepage](https://cmake.org/)
- [CMake 官方 Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
- [CMake Documentation](https://cmake.org/documentation/)
- [CMake Tutorial](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)
- [CMake Examples](https://github.com/ttroy50/cmake-examples)
- [CMake Cheat Sheet](https://cliutils.gitlab.io/modern-cmake/)
- [CMake FAQ](https://gitlab.kitware.com/cmake/community/wikis/FAQ)
- [CMake Best Practices](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1)
- [上海交通大学 IPADS 组新人培训](https://www.bilibili.com/video/BV14h41187FZ)
