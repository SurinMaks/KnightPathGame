# KnightPathGame

In the game of "Knight Move", you need to fill the entire field by moving around it like a chess knight. Each position can only be moved once.

To build Qt 6 projects on Linux, you will need to install the following components:

- Installing the base dependencies:
```sh
sudo apt update
sudo apt install build-essential
sudo apt install cmake
```
- Installing Qt 6:
```sh
sudo apt install qt6-base-dev
```
- The process of building the project via cmake:
```sh
mkdir build
cd build
cmake /path/to/CMakeLists.txt
cmake --build .
```
