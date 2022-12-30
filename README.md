# hello-world-new
Aha...A new Hello World.

# Build
To build it, you just need:
```
sudo pacman -Syyu
sudo pacman -Syy gcc g++ cmake make m4
# Or your own package manager.
mkdir bin
cd bin
cmake ..
make -j3 V=s
```
Then if you see "Hello, world!" in your console, Your C/C++ build environment is successfully configured.
