# CUDA Libraries Project

## Project Description

This project was created as a playground for investigating various algorithms provided by the CUDA Thrust Library. Currently, the project provides an implementation of the following algorithms:
 * transformation;
 * reduction;
 * prefix-sum;
 * reordering;
 * sorting.
 
The project allows to choose the size of the generated dataset and specify the needed algorithms:
```
./thrustAlgorithms <size> <algorithm> 
```
For example:
```
./thrust 100 reduction
```

The project requires a Coursera Lab environment to execute since it provides the configured CUDA environment and doesn't require additional configuration, which currently is out of the scope of this project.

The project structure follows the template from https://github.com/PascaleCourseraCourses/CUDAatScaleForTheEnterpriseCourseProjectTemplate.

## Code Organization

```bin/```
This folder should hold all binary/executable code that is built automatically or manually. Executable code should have use the .exe extension or programming language-specific extension.

```data/```
This folder should hold all example data in any format. If the original data is rather large or can be brought in via scripts, this can be left blank in the respository, so that it doesn't require major downloads when all that is desired is the code/structure.

```lib/```
Any libraries that are not installed via the Operating System-specific package manager should be placed here, so that it is easier for inclusion/linking.

```src/```
The source code should be placed here in a hierarchical fashion, as appropriate.

```README.md```
This file should hold the description of the project so that anyone cloning or deciding if they want to clone this repository can understand its purpose to help with their decision.

```INSTALL```
This file should hold the human-readable set of instructions for installing the code so that it can be executed. If possible it should be organized around different operating systems, so that it can be done by as many people as possible with different constraints.

```Makefile or CMAkeLists.txt or build.sh```
There should be some rudimentary scripts for building your project's code in an automatic fashion.

```run.sh```
An optional script used to run your executable code, either with or without command-line arguments.