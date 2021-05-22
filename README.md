# MD_simulation

A non-working, floating-point based MD simulation using the Lennard-Jones potential. The integrator employed was the Verlet velocity algorithm. To run the animation in the last cell FFMPEG is required. Results are stored as 3 numpy ndarrays for positions, velocity, and acceleration respectively. All quantities are in natural units of $\sigma=\varepsilon=m=1$ 

Current simulation-breaking issue: acceleration imparted by the potential is unphysically large.
Created as part of the PHYS2020 course at ANU, independently investigating how rounding errors affects the Boltzmann H-function. 
