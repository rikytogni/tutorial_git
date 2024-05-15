<div align ="center">
<p float="left">
  <img src="https://github.com/rikytogni/tutorial_git/assets/43726876/9f4dd9cd-b0fb-4825-88eb-a1001bccf4c7" width="300" />
  <img src="https://github.com/rikytogni/tutorial_git/assets/43726876/d2f6ad1e-7de5-4a7f-bdfe-64069c94f5f3" width="300" /> 
</p>

</div>

## CFDEM®coupling-PUBLIC is no longer mantained - request the latest version!

This repository contains only a free version of CFDEM®coupling (CFDEM®coupling-PUBLIC) and will not be updated in the foreseeable future.

The latest version of CFDEM®coupling, which is compatible with the DEM software [Aspherix®](https://www.aspherix-dem.com/), is developed and distributed by DCS Computing GmbH, Linz, Austria. For more information, please contact [DCS Computing](https://www.aspherix-dem.com/contact/).

</div>

## CFDEM®coupling-PUBLIC

CFDEM®coupling-PUBLIC is an Open Source coupled CFD-DEM framework combining the strengths of LIGGGHTS® DEM code and the Open Source CFD package OpenFOAM® [^1]. CFDEM®coupling stands for Computational Fluid Dynamics (CFD) - Discrete Element Method (DEM) coupling.

LIGGGHTS® and CFDEM® are registered trade marks of DCS Computing GmbH, the producer of the LIGGGHTS® software and the CFDEM®coupling softwar; see http://www.cfdem.com/terms-trademark-policy for details.

CFDEM®coupling-PUBLIC  is open-source, distributed under the terms of the GNU Public License, version 3 or later. CFDEM®coupling-PUBLIC is part of CFDEM®project: www.liggghts.com | www.cfdem.com. Core developer and main author: Christoph Goniva, christoph.goniva@dcs-computing.com

[^1]: This offering is not approved or endorsed by OpenCFD Limited, the producer of the OpenFOAM software and owner of the OPENFOAM® and OpenCFD® trade marks.

</div>

## Structure
The CFDEM®coupling distribution includes the following files and directories:

* `README` file: this file
* `COPYING` file: the GNU General Public License (GPL)
* `DISCLAIMER` file
* `src` directory: includes the source files of the coupling toolbox and models
* `applications` directory: includes the solver files for coupled CFD-DEM simulations
* `doc` directory: includes the documentation of CFDEM®coupling
* `tutorials` directory: includes basic tutorial cases showing the functionality

Details on installation are given on the www.cfdem.com website.

## Copyrights
* Copyright 2012-now: DCS Computing GmbH, Linz
* Copyright 2009-2015: JKU Linz

Some parts of CFDEM®coupling are based on OpenFOAM® and Copyright on these parts is held by the OpenFOAM® Foundation (www.openFoam.org) and potentially other parties. Some parts of CFDEMcoupling are contributied by other parties, which are holding the Copyright. This is listed in each file of the distribution.

## How to cite CFDEM®coupling-PUBLIC
If you are using PhasicFlow in your research or industrial work, cite the following [article](https://doi.org/10.1016/j.partic.2012.05.002):
```
@article{goniva2012influence,
  title={Influence of rolling friction on single spout fluidized bed simulation},
  author={Goniva, Christoph and Kloss, Christoph and Deen, Niels G and Kuipers, Johannes AM and Pirker, Stefan},
  journal={Particuology},
  volume={10},
  number={5},
  pages={582--591},
  year={2012},
  publisher={Elsevier}
}
```
