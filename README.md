# AE370-Model-of-Satellite-Orbits-Around-Jupiter 
This repository contains the code we used to simulate the motion of a satellite about Jupiter under various conditions using the Velocity Verlet numerical method. The following is a description of our three jupyter notebook files, to be viewed in this order:

(1) Comparing No Drag Solutions - describes the motion of a satellite in one orbit with no perturbations. This code represents our implementation of Velocity Verlet and compares it to an analytical Keplerian implementation, which we call the "true solution." This code addresses the first question posed in our report.

(2) Effect of Drag Perturbation - uses Velocity Verlet to simulate the motion of the satellite about Jupiter in 50 orbits, with and without drag perturbations. Plots of semimajor axis over time are also included and discussed. This code addresses the second question posed in our report.

(3) Error vs Time Analysis - includes discussion and plots of numerical convergence for the No Drag simulations described in (1). 
