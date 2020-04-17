# EDFT
Research and analysis of Electron Density Functional Theory


# Summary
Quantum mechanical simulations of atoms are still too complex for today’s modern
computers to process. There are two approaches to this problem, either to develop a more
capable computer or to further develop quantum mechanical theory itself. Working with Randall
Jones, Ph.D. of the Loyola University Physics Department, I have made advancements to
Electron Density Functional Theory and built upon the ground work done by two physicists in
the late twentieth century, 𝑃𝑖𝑒𝑟𝑟𝑒 𝐻𝑜ℎ𝑒𝑛𝑏𝑒𝑟𝑔 𝑎𝑛𝑑 𝑊𝑎𝑙𝑡𝑒𝑟 𝐾𝑜ℎ𝑛.


The many particle wavefunction solutions to Schrodinger’s equation are difficult and
nearly impossible to solve for atoms. In particular, one major challenge in determining the
properties of nanoparticles is the calculation of the total energy of any particular configuration of
the atoms. Due to the lack of exact wavefunction solutions, only approximations have been
available to use in defining the total energy of a system. In current practice, the total energy
depends on 3N variables, where N particles are free to move in the three dimensions, but the
Hohenberg-Kohn theorem states it should be possible to determine the total energy of a system
directly as a functional of the electron density. If the energy could be a function of only three
coordinates, the problem would be greatly simplified! Reasonably good approximations exist for
the functional representing electron-electron potential energy, but if we knew the kinetic energy,
we could use that to determine the total energy and search for its relation to the electron density.


During the Hauber Summer Research Program, Dr. Jones and I have rediscovered a
𝑚𝑜𝑑𝑒𝑙 𝑠𝑦𝑠𝑡𝑒𝑚 consisting of N, interacting, spin ½ particles that can be solved exactly to obtain
the many-particle wavefunction. This model system involves particles that interact via springlike forces, therefore the Schrodinger equation can be completely solved to obtain its
wavefunction, particle density, and exact energy. I am now working to determine the functional
for this model system with an arbitrary number of particles that generates the kinetic energy
density from the particle density where the potential is already defined. The form of this
functional corresponding to this model system can provide insight and guide the development of
the functional for a real electron system.


# Important files
1. Research Report write-up

https://github.com/AHalarewicz/EDFT/blob/master/ALHalarewicz_Goldwater_Research_Essay_EDFT.pdf


2. Mathematica Notebook File

https://github.com/AHalarewicz/EDFT/blob/master/EDFT.nb

3. PDF of executed mathematica notebook file with anotated results

https://github.com/AHalarewicz/EDFT/blob/master/EDFToutput.pdf
