# LibraryShowcase

This is a simple project to showcase my code libraries, for purposes of documenting, testing and showing example.

# How to use (outdated)

```
git clone
git submodule update --init --recursive
mkdir build
cd build
cmake ..
make
```

Then you can start any Showcase, eg GeometricAlgebraShowcase, like this:

```
./GeometricAlgebraShowcase/GeometricAlgebraShowcase
```

For SFML, you might need to install the following packages
```
sudo apt install libxi-dev libxrandr-dev libxcursor-dev libflac-dev libvorbis-dev
```

# Ideas to develop

## Graph library

manage a graph with nodes and edges

cool algorithms : pathfinding, mst, triangulation, voronoi, etc

quadtree, kdtree

## Geometric algebra

2D multivectors : scalar, vector (×2), bivector

maybe 3d multivectors : scalar, vector (×3), bivector (×3), trivector

## Logging library

rotate log files, multiple logging levels, log timestamping

## Visual stuff

SFML, imgui

look into GLSL shaders with SFML

"3D engine" with axonometric projection
