Acoustic reverse-time migration using GPU card and POSIX thread based on the adaptive optimal finite-difference scheme and the hybrid absorbing boundary condition.

Complie is like

nvcc -g -o RTM kernel.cu -I/ segy.cpp simtab.cpp 

Then run with

./RTM
