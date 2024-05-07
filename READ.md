<div align ="center">

![image](https://github.com/rikytogni/tutorial_git/assets/43726876/2b94ee44-d8fb-4b1e-b719-7dbbef5b7503)

</div>

**LIGGGHTS(R)-PUBLIC** is an Open Source Discrete Element Method Particle Simulation Software, distributed by DCS Computing GmbH, Linz, Austria.
LIGGGHTS(R) is a registered trade marks of DCS Computing GmbH, the producer of the LIGGGHTS(R) software; see http://www.cfdem.com/terms-trademark-policy for details.

</div>

**LIGGGHTS(R)-PUBLIC** is an Open Source Discrete Element Method Particle Simulation Software, distributed by DCS Computing GmbH, Linz, Austria.
LIGGGHTS(R) is a registered trade marks of DCS Computing GmbH, the producer of the LIGGGHTS(R) software; see http://www.cfdem.com/terms-trademark-policy for details.
**LIGGGHTS** is a parallel C++ code for performing DEM simulations. It can run on shared-memory multi-core computational units such as multi-core CPUs or GPUs (for now it works on CUDA-enabled GPUs). The parallelization method mainly relies on loop-level parallelization on a shared-memory computational unit. You can build and run PhasicFlow in serial mode on regular PCs, in parallel mode for multi-core CPUs, or build it for a GPU device to off-load computations to a GPU. In its current statues you can simulate millions of particles (up to 80M particles tested) on a single desktop computer. You can see the [performance tests of PhasicFlow](https://github.com/PhasicFlow/phasicFlow/wiki/Performance-of-phasicFlow) in the wiki page.

**MPI** parallelization with dynamic load balancing is under development. With this level of parallelization, PhasicFlow can leverage the computational power of **multi-gpu** workstations or clusters with distributed memory CPUs. 
In summary PhasicFlow can have 6 execution modes:
1. Serial on a single CPU core,
2. Parallel on a multi-core computer/node (using OpenMP),
3. Parallel on an nvidia-GPU (using Cuda),
4. Parallel on distributed memory workstation (Using MPI)
5. Parallel on distributed memory workstations with multi-core nodes (using MPI+OpenMP)
6. Parallel on workstations with multiple GPUs (using MPI+Cuda).

## How to cite LIGGGHTS
If you are using PhasicFlow in your research or industrial work, cite the following [article](https://www.sciencedirect.com/science/article/pii/S0010465523001662):
```
@article{NOROUZI2023108821,
title = {PhasicFlow: A parallel, multi-architecture open-source code for DEM simulations},
journal = {Computer Physics Communications},
volume = {291},
pages = {108821},
year = {2023},
issn = {0010-4655},
doi = {https://doi.org/10.1016/j.cpc.2023.108821},
url = {https://www.sciencedirect.com/science/article/pii/S0010465523001662},
author = {H.R. Norouzi},
keywords = {Discrete element method, Parallel computing, CUDA, GPU, OpenMP, Granular flow}
}
