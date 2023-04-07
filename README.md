# Parallel-Leiden

ParallelLeiden is a parallelized implementation of the Leiden algorithm

NetworKit is needed for this code to work, just place the entire folder in the same directory as the PL files

## Setting up the source code

1. Clone Graph-ParallelLeiden.
```console
Graph@:~$ git https://github.com/atmughrabi/ParallelLeiden.git
```
2. From the home directory go to the Graph directory:
```console
Graph@:~$ cd ParallelLeiden/
```
3. Setup the ParallelLeiden submodules.
```console
Graph@ParallelLeiden:~$ git submodule update --init --recursive
```
4. Create CMake build directory
```console
Graph@ParallelLeiden:~$ mkdir build
```
5. Create CMake build directory
```console
Graph@ParallelLeiden:~$ cd build
```
6. configure build
```console
Graph@ParallelLeiden:~build$ cmake ..
```
7. make ParallelLeiden
```console
Graph@ParallelLeiden:~build$ make
```