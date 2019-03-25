## Photon-v2-ThirdParty

This repository holds pre-compiled third party libraries used by [Photon-v2 renderer](https://github.com/TzuChieh/Photon-v2). Here is the list of libraries as well as the used versions:

* [googletest](https://github.com/google/googletest)
  * git commit hash a868e618c0607259c63f37d948b72586a13922ff
* [stb](https://github.com/nothings/stb)
  * git commit hash e6afb9cbae4064da8c3e69af3ff5c4629579c1d2
* [StackWalker](https://github.com/JochenKalmbach/StackWalker)
  * git commit hash 42e7a6e056a9e7aca911a7e9e54e2e4f90bc2652
* [libsimdpp](https://github.com/p12tic/libsimdpp)
  * git tag v2.1
* [openexr](https://github.com/openexr/openexr/tree/8cd1b9210855fa4f6923c1b94df8a86166be19b1)
  * git tag v2.3.0
  * python binding is not needed (OPENEXR_BUILD_PYTHON_LIBS=OFF for CMake)

## Build

All libraries should be build (except for header-only libraries) for static linking, and settings compatible with the renderer.

## License

See each library's corresponding project site for more detail. Licenses (if present) are also included in each library's folder.