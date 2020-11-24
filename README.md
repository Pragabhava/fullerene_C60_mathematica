# Acompanying *Mathematica* code for
# [Nonlinear Vibrations in the Fullerene Molecule](https://arxiv.org/abs/1804.05455)
Accepted for publication at [SIADS](https://www.siam.org/publications/journals/siam-journal-on-applied-dynamical-systems-siads)

In this repo are the main numerical solution generators for the paper. By looking at PSALC-XX-X, it can be seen how the code can be adapted to generate other solutions.

What's in this repo
-------------------

* Potential_01_2.nb
>Stationary state position generator
* PSALC-E1-1.nb
>Pseudo ArcLength Continuation for Eigenvalue 1, multiplicity 1.
* PSALC-E3-1.nb
>Pseudo ArcLength Continuation for Eigenvalue 3, multiplicity 2, S4 symmetry.
* PSALC-E1-RW.nb
>Pseudo ArcLength Continuation for Eigenvalue 1, Rotating wave.
* AnimationGenerator.nb
>Generic gif animation generator (there are also specific files; if you need one, please ask.)
* FiguresGenerator.nb
>Paper figures generator.
* PSALC
>All solutions generated.

**Note:** this code is not *production* quality. For properly annotated code, look for the python version (to be uploaded soon).

Manuel Tejada-Wriedt
