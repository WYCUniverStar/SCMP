# SCMP

We propose a leaderless, hierarchical search-based cooperative motion planning (SCMP) method. The high-level utilizes a binary conflict search tree to minimize runtime, while the low-level fabricates kinematically feasible, collision-free paths that are shape-constrained; these are adaptable to scenarios featuring multiple shapes, groups, and elaborate obstacles. 



## Simulation Test

![sim_test](img/sim_test.gif)



## Field Test(Ideal path)

![field_test](img/field_test.gif)



**For detailed information, please refer to our video file named [SCMP.mp4](./SCMP.mp4)**.

# <font color="red">**The source code will come soon**</font>

## Requirement

```
sudo apt-get install g++ cmake libboost-program-options-dev libyaml-cpp-dev \
clang-tidy clang-format python3-matplotlib libompl-dev libeigen3-dev
```

