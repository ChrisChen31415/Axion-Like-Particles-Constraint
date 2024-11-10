# File Instruction
The code for constraining coupling constant with photon and mass of Axion Like Particles using spectral energy distribution(SED) from active galactic nuclei (AGN).

The excel files are used to store data obtained from other paper or observations, which shall be uploaded into csv file soon. They record the energy of photons received, the according flux, and standard deviation of flux. Data points from different observing groups are separated and clearly de-marked.

The file 'AGN_APL_MCMC.ipynb' is the jupyter notebook containing the main codes. It calculates the transmission probability of photon from AGN to Earth based on current ALP theory. Based on the calculation, an overall range of redshift--within which sources with stringent constraint may be found-- is developed, and two flat-spectrum radio quasars (B2 2234+28A and 3C 454.3) are hence used for parameter constraint. Using Markov Chain Monte Carlo method, we are able to give a coupling constant of 3.25e-11 GeV^(-1) and axion mass of 5.25e-8 eV from B2A, with (7.40e-11 GeV^(-1), 5.50e-8eV) from 3C 454.3. 
