# Coupled Oscillators in a Stochastic Thermal Bath

## Project Overview

Developed a Python-based stochastic simulation to investigate the dynamics of four coupled harmonic oscillators subjected to Gaussian thermal fluctuations. The project explores how random thermal perturbations influence collective oscillations, normal modes, and the stability of interacting particle systems.

## Theory

The model describes four masses connected through nearest-neighbor harmonic interactions in a periodic lattice, with stochastic forcing representing thermal fluctuations.

$$m\ddot{\phi}_i=-k(2\phi_i-\phi_{i-1}-\phi_{i+1})+\eta_i(t)$$

where \(\phi_i\) represents angular displacement, \(k\) is the coupling stiffness, and \(\eta_i(t)\) represents Gaussian random forcing controlled by temperature \(T\).

The system supports collective normal modes determined by the eigenvalues and eigenvectors of its coupled equations of motion.

## How It Was Built

Developed a Python numerical simulation of four coupled oscillators over 100,000 time steps using finite-difference integration of second-order differential equations. Implemented nearest-neighbor harmonic interactions with periodic boundary conditions and Gaussian-distributed random forces to model thermal perturbations. Applied iterative velocity and position updates to calculate angular displacement trajectories, mapping particle motion onto two-dimensional coordinates using trigonometric transformations. Generated time-series visualizations to examine collective oscillations and temperature-dependent fluctuations.

## Results

Simulated 100,000 time steps of coupled oscillator dynamics under stochastic thermal forcing at a temperature parameter of 0.09. Generated angular displacement time series for all four particles to examine the evolution of collective motion, oscillatory behavior, and thermal fluctuations. The model provides a computational framework for investigating normal-mode dynamics and stochastic behavior in coupled mechanical systems.

## Technologies

Python, NumPy, Matplotlib, Stochastic Dynamics, Gaussian Noise, Coupled Differential Equations, Finite-Difference Methods, Harmonic Oscillators, Normal Mode Theory, Time-Series Analysis.
