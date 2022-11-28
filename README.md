# Graphene Fracture
Accompanying files to submitted work.

Simulation parameters based on the 2014 Zhang et al. paper _Fracture toughness of graphene_

https://doi.org/10.1038/ncomms4782

![300KFractureSmall](https://user-images.githubusercontent.com/71855260/169610313-00894d98-0e48-42a5-92e7-387aaa09c87d.gif)

Within this repository are all the necessary files to recreate the molecular dynamics portion of this paper, including the Graphene Sheet data files, the Ovito save states to make modify the raw Graphene Sheets, the modified REBO potential described in the paper, the LAMMPS input files, and the Python files needed to read the outputs and plot. 

LAMMPS Dependencies:
- must be built with MANYBODY for REBO potential support

Python Dependencies:
- Numpy 
- Scipy
- Matplotlib

