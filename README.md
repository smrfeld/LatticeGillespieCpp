# Gillespie on a Lattice in the single occupancy limit

## Features

Unimolecular and bimolecular reactions on 1D, 2D, 3D lattices.

![example](/figures/example.png)

## Installation

### Build

Use `cmake`
```
mkdir build
cd build
cmake ..
make
make install
```
The default location is `/usr/local/lib` and `/usr/local/include`.

### Including

Use the convenient `include <lattgillespie>`.

### Linking

Example:
```
g++ -std=c++14 -O3 -llattgillespie -o main.o main.cpp
```
Be sure to put it into your `DYLD_LIBRARY_PATH`:
```
export DYLD_LIBRARY_PATH=$DYLD_LIBRARY_PATH:/absolute/path/to/lib/folder
```
else use the `-L` flag when linking. (`-L` needed at link time; `DYLD_LIBRARY_PATH` needed at runtime).

## Usage

More documentation TBD!

### Namespace

The namespace is `lattg`.