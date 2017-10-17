CUDA Rasterizer
===============

[CLICK ME FOR INSTRUCTION OF THIS PROJECT](./INSTRUCTION.md)

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 4**

* Name: Jiahao Liu
* Tested on: Windows 10, i7-3920XM CPU @ 2.90GHz 3.10 GHz 16GB, GTX 980m SLI 8192MB (personal computer)

Project Description
======================

This project is a implementation of a simple rasterizer using cuda. Mainly implements part of the OpenGL pipeline, the vertex shader to fragment shader.

Features implemented
======================

* Basic Lambert and Blinn shading.
* Perspective correct interpolation.
* Correct color interpolation between points on a primitive.
* UV texture mapping with bilinear texture filtering and perspective correct texture coordinates.
* Line rasterization mode.
* Point cloud rasterization mode.

Rasterization result
======================

* Perspective correct interpolation

This use normal as color for each point.

![](renders/1.gif)

* Correct color interpolation between points on a primitive.

![](renders/7.gif)

* Basic Lambert and Blinn shading.

![](renders/4.gif)

* UV texture mapping with bilinear texture filtering and perspective correct texture coordinates.

![](renders/2.gif)

![](renders/3.gif)

* Line rasterization mode.

![](renders/5.gif)

* Point cloud rasterization mode.

![](renders/6.gif)

Performance Analysis
======================

* TODO

### Credits

* [tinygltfloader](https://github.com/syoyo/tinygltfloader) by [@soyoyo](https://github.com/syoyo)
* [glTF Sample Models](https://github.com/KhronosGroup/glTF/blob/master/sampleModels/README.md)
