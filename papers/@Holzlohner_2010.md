#papers

---
title: Optimization of cw sodium laser guide star efficiency
authors: R. Holzlöhner, S. M. Rochester, D. Bonaccini Calia, D. Budker, J. M. Higbie, W. Hackenberg
year: 2010
---
notes:
- want to calculate the return flux from LGS (as when released was going into a new era)

- LGS are integral component of AO systems now

- new gen of ELTs are being developed as adaptive telescopes (rather than in the past it being a feature that has been added on later)

- current problem with generating LGS is that powerful sodium lasers are very expensive, and have a lack of solid state materials  (only using semiconductor materials)

- need to simulate lasers to determine the ideal set up to determine what the telescope will need 

- hard to do on sky measurements as there is little agreement to the measurement standards

- have double hump profile due to doppler broadening of the D$_{2a}$ and D$_{2b}$ lines

- want to use circularly polarised light as makes Na essentially a two level atom

- the flux returned from the sodium layer depends on many factors including: collisions w consistuent gas, temperature and geomagnetic field

- with higher flux also need to consider saturation, optical pumping and recoil from radiation pressure

- need numerical simulations to understand the interplay of all of these effects on the flux return

- common way to do this is the Bloch equations (density matrix evolution of a multi-level atom)

- have lots of previous studies which focus on different aspects of the layer

- if not using the Bloch equations, can simulate the rates of change (differentials) or Monte Carlo rate equations (track evolution of one atom)

- in simulation find the “three evils” are: larmor precession, recoil and transition saturation

- this paper is looking at optimising flux in based on a set flux out

- use code written in Mathematica, then compare it to code from Matlab using different techniques

# Mathematica Code:

- uses optical Boch equations for atomic density matrix

- the statistical state of an ensemble of atoms in the state space of D$_2$ transition

- consider velocity states for atoms at different velocities

- uses all 24 states of sodium atoms

- Equation 1, is the density matrix equations for the optical Boch eqns.

- use binning which gives better resolution in regions of interest

- use a error minimising technique to make steps

- -- just my interest, only 4% of the sodium atoms in the laser are used, other 96% travel straight into space --
