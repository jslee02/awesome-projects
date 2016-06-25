# Awesome Projects
A curated list of awesome projects from my experience

#### Table of Contents
* [Libraries](#libraries)
* [Software / Web Services](#software--web-service)
* [Other Awesome Lists](#other-awesome-lists)

## Libraries

### Benchmark / Profile

* [semile](http://r-kan.github.io/semile/) ([github](https://github.com/r-kan/semile)) - A profiling framework provides the ability to monitor programs, in general of any programming language with (1) consumed time per execution and (2) 'footprint' message per execution

### Math

* [CGAL](http://www.cgal.org/) ([github](https://github.com/CGAL/cgal)) -  A software project that provides easy access to efficient and reliable geometric algorithms in the form of a C++ library.
* [Eigen](https://bitbucket.org/eigen/eigen/) - A C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.
* [Elemental](http://libelemental.org/) ([github](https://github.com/elemental/Elemental)) - A modern C++ library for distributed-memory dense and sparse-direct linear algebra and optimization which supports [a wide range of functionality not available elsewhere](http://libelemental.org/about/).
* [libigl](http://libigl.github.io/libigl/) ([github](https://github.com/libigl/libigl)) - A simple C++ geometry processing library.
* [MathFu](http://google.github.io/mathfu/) ([github](https://github.com/google/mathfu)) - C++ math library developed primarily for games focused on simplicity and efficiency.
* [MathGeoLib](http://clb.demon.fi/MathGeoLib/nightly/) ([github](https://github.com/juj/MathGeoLib)) - A C++ library for linear algebra and geometry manipulation for computer graphics.

### Parallel Programming

#### SIMD

* [libsimdpp](https://github.com/p12tic/libsimdpp) - Header-only zero-overhead C++ wrapper for SIMD intrinsics of multiple instruction sets.
* [Vc](https://github.com/VcDevel/Vc) - SIMD Vector Classes for C++

##### SIMD Papers

* An evaluation of current SIMD programming models for C++ (2016) ([pdf](http://www.biagiocosenza.com/papers/PohlWPMVP16.pdf))

#### OpenCL

##### Wrapper

* [Chlorine](http://polytonic.github.io/Chlorine/) ([github](https://github.com/Polytonic/Chlorine)) - Dead Simple OpenCL (Compute).
* EasyCL ([github](https://github.com/hughperkins/EasyCL)) - Easy to run kernels using OpenCL
* EasyOpenCL ([github](https://github.com/Gladdy/EasyOpenCL)) - The easiest way to get started with OpenCL!
* [VexCL](http://vexcl.readthedocs.org) ([github](https://github.com/ddemidov/vexcl)) - VexCL is a C++ vector expression template library for OpenCL/CUDA.

##### OpenCL Application Libraries

* DeepCL ([github](https://github.com/hughperkins/DeepCL)) - OpenCL library to train deep convolutional neural networks.
* libclsph ([github](https://github.com/libclsph/libclsph)) - OpenCL based GPU accelerated SPH fluid simulation library.
* OpenCL-caffe ([github](https://github.com/amd/OpenCL-caffe)) - OpenCL version of caffe developed by AMD research lab.

### Meta Programming

* Brigand ([github](https://github.com/edouarda/brigand)) - A light-weight, fully functional, instant-compile time C++ 11 meta-programming library.
* [Metal](http://brunocodutra.github.io/metal/) ([github](https://github.com/brunocodutra/metal)) - A portable header-only C++14 library designed to make template metaprogramming enjoyable.

### Graphics

* [bgfx](https://bkaradzic.github.io/bgfx/index.html) ([github](https://github.com/bkaradzic/bgfx) :star: 1.9k) - Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library.
  * fips-bgfx ([github](https://github.com/floooh/fips-bgfx)) - fipsified version of bgfx (CMake support)
* [Magnum](http://mosra.cz/blog/magnum.php) ([github](https://github.com/mosra/magnum) :star: 0.7k) - C++11/C++14 and OpenGL graphics engine.
* [OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph) ([github](https://github.com/openscenegraph/OpenSceneGraph) :star: 0.5k) - An open source high performance 3D graphics toolkit, used by application developers in fields such as visual simulation, games, virtual reality, scientific visualization and modelling.
* [Urho3D](http://urho3d.github.io/) ([github](https://github.com/urho3d/Urho3D) :star: 1.1k) - A free lightweight, cross-platform 2D and 3D game engine implemented in C++ and released under the MIT license.
* [VisualizationLibrary](http://visualizationlibrary.org/documentation/) ([github](https://github.com/MicBosi/VisualizationLibrary) :star: 36) - A lightweight C++ OpenGL middleware for 2D/3D graphics.

### Game Engine

* [CRYENGINE](https://www.cryengine.com/) ([github](https://github.com/CRYTEK-CRYENGINE/CRYENGINE))
* LumixEngine ([github](https://github.com/nem0/lumixengine)) - 3D Game Engine.

### GUI

* [glfw](http://www.glfw.org/) ([github](https://github.com/glfw/glfw) :star: 1.9k) - A multi-platform library for OpenGL, window and input.
* imgui ([github](https://github.com/ocornut/imgui) :star: 3.6k) - Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies.
  * ImWindow ([github](https://github.com/thennequin/ImWindow)) - Window and GUI system based on ImGui from OCornut.
* NanoGUI ([github](https://github.com/wjakob/nanogui) :star: 0.6k) - A minimalistic cross-platform widget library for OpenGL 3.x.
* Nuklear ([github](https://github.com/vurtun/nuklear) :star: 4.6k) - A minimal state immediate mode graphical user interface toolkit written in ANSI C and licensed under public domain.

### Logging

* Loguru ([github](https://github.com/emilk/loguru)) - A header-only C++ logging library.
* spdlog ([github](https://github.com/gabime/spdlog)) - Very fast, header only, C++ logging library.

### Signal

* wigwag ([github](https://github.com/koplyarov/wigwag)) - C++ signals library.

### Test

* [Catch](https://github.com/philsquared/Catch) - A modern, C++-native, header-only, framework for unit-tests, TDD and BDD
* doctest ([github](https://github.com/onqtam/doctest)) - The lightest feature rich C++ single header testing framework for unit tests and TDD.
* [Google Test](https://github.com/google/googletest)

### Python binding

* pybind11 ([github](https://github.com/pybind/pybind11)) - Seamless operability between C++11 and Python.

## Software / Web Service

### Development

* [cloc](https://github.com/AlDanial/cloc) - _cloc_ counts blank lines, comment lines, and physical lines of source code in many programming languages.
* [COVERALLS](https://coveralls.io/) - Test Coverage History & Statistics.
* [Cppcheck](https://github.com/danmar/cppcheck)
* [Reviewable](https://reviewable.io/) - Github Code review assistant.

### Code Formatter

* [Uncrustify](http://uncrustify.sourceforge.net/) ([github](https://github.com/uncrustify/uncrustify)) - Source Code Beautifier for C, C++, C#, ObjectiveC, D, Java, Pawn and VALA

### Git/Mercurial

#### GUI client

* [SmartGit](http://www.syntevo.com/smartgit/)

#### Utilities

* [Github Wiki Search](https://github.com/linyows/github-wiki-search)


## ETC

* [Semantic Versioning Specification](https://github.com/mojombo/semver/blob/master/semver.md)

## C++ References

* [C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines) ([Kor](https://github.com/CppKorea/CppCoreGuidelines))
  * [GSL](https://github.com/Microsoft/GSL) - Guidelines Support Library by Microsoft
* [C++ reference](http://en.cppreference.com/)
* [C++ Samples](http://www.cppsamples.com/)
* [More C++ Idioms](https://en.wikibooks.org/wiki/More_C%2B%2B_Idioms)

## Other Awesome Lists

* [Awesome C/C++](https://github.com/fffaraz/awesome-cpp)
* [Awesome Modern C++](https://github.com/rigtorp/awesome-modern-cpp)
* [Awesome Robotics Libraries](https://github.com/jslee02/awesome-robotics-libraries)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
