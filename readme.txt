Hand writing SPH
Based on CUDA Particles Samples[Green(2008)]

Restructure the directory tree
Add force interaction of SPH

This sample uses CUDA to simulate and visualize a large set of particles and their physical interaction.
Adding "-particles=<N>" to the command line will allow users to set # of particles for simulation.
A uniform grid data structure is implemented using a fast radix sort from the Thrust library

Make:
cd make
make particles

Run:
make run

Reference:
Green, S. (2008). CUDA Particles. Technical Report contained in the CUDA SDK, www.nvidia.com