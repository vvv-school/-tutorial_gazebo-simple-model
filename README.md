# tutorial_gazebo-simple-model
This tutorial shows how to create a simple single body model and how to spawn it in the [Gazebo simulator](http://gazebosim.org/). 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/vvv-school/tutorial_gazebo-simple-model)

## Prerequisites

For this tutorial, you just need to be aware of:
- What the [Gazebo simulator](http://gazebosim.org/) is
- Optionally run [CMake](https://cmake.org/)

## You will see how to:
- How to create a Gazebo model from a [mesh](https://en.wikipedia.org/wiki/Polygon_mesh) of a given object.
- How to install a Gazebo model in way that it can be found automatically by Gazebo.

## Build and Install the code
Follow these steps to build and properly install your module: 
```
$ cd tutorial_gazebo-simple-model
$ mkdir build; cd build
$ cmake ../
# make is not necessary as this project does not compile anything
$ make install
```
the `make install` will install your model and related files in the icub contrib folder which is already setup on your machine. 

## Have fun with the tutorial
The repo contains three files: 
* `CMakeLists.txt` : The file that describes where the files contained in the project should be installed by `make install` . 

### How to add a new model
TODO
