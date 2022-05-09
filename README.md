# Mini-Application Skeleton

The purpose of this repository is to serve as a template with which to fork and build mini-applications with.

As such, this code should provide:

* Build system, with linking to openBLAS, Intel MKL and various GPU-accelerated libraries:
  * CMake
  * Potentially also in Meson or make

* A main program or test programs (unit tests) to demonstrate linking and calling

* Demonstrate calls to external libraries that perform mathematical kernels commonly used in our electronic structure 
research, including: 
  * FFTs
  * Matrix - matrix multiplication
  * Tensor operations

* Potentially provide some higher-level API to common library calls

* Abstract away any MPI, CUDA, openACC and OMP directives  