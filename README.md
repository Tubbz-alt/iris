# IRIS

IRIS is an intelligent runtime system for extremely heterogeneous architectures. IRIS discovers available functionality, manage multiple diverse programming
systems (e.g., OpenMP, OpenCL, CUDA, HIP) simultaneously in the same application, represents data dependencies, orchestrates data movement proactively, and allows configurable work schedulers for diverse heterogeneous devices.

IRIS is open source software. You may freely distribute it under the terms of the license agreement found in LICENSE.txt.

<img src="https://raw.githubusercontent.com/ornl/iris/master/iris.png" width="60%">

## Requirements

* C++11 compiler
* CMake (>=3.8)
* LLVM/Polly/Clang (*optional)

## Installation

The `master` branch of this repo is aimed to be buildable with the latest IRIS `master` revision.

```
git clone https://github.com/ornl/iris.git
cd iris
mkdir build
cd build
cmake .. -DCMAKE_INSTALL_PREFIX=<install_dir> -DUSE_PYTHON=ON -DUSE_FORTRAN=ON
make install
```

## The IRIS source code will be open in Spring 2021.
