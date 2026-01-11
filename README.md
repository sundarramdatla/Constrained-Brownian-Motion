# Brownian motion on constrianed particles using Langevin dynamics 

Langevin dynamics is an important framework of Newton's equations that allow one to study the behavior of particles subject to Brownian motion.
A 4 particle circular lattice with interactions occuring between neighboring particles via a spring potential is first simulated classically with a Euler leapfrog algorithm where each particle is displaced according to its normal mode.
A Langevin noise term is then appended to the equations of motions reflecting the lattice placed in a thermal heat bath, modeling thermal vibrations of a circular lattice structure.

Limiting behavior as the temperature tends to 0 reflects physical intutition as the lattice vibrations return to their normal mode behavior. 
As temperature increases slowly, thermal excitation leads to gradually erratic vibrations and the decay of normal mode behavior. 
