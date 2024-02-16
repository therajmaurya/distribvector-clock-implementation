# vector-clock-implementation
distributed-systems-vector-clock-implementation

### Steps to run the code 
- Need to have Open MPI Setup locally

To compile the C++ file:
```bash
mpic++ -o compiled.out main.cpp
```
To run the compiled output:
```bash
mpirun --hostfile hostfile -n 6 compiled.out 
```

### References:
- https://www.geeksforgeeks.org/different-ways-to-setting-up-environment-for-cpp-programming-in-mac/
- https://www.bilibili.com/read/cv15365733/
- https://www.open-mpi.org/software/ompi/v5.0/
- https://www.mpi-forum.org/docs/