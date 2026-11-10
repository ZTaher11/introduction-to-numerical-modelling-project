
# From Routes to Bridges: Investigating Numerical Computation Methods for Solving Scientific Problems

### Zaheer Taher

This repository contains my final project for the Introduction to Numerical Modelling module (5CCP211C), completed during the second year of my BSc Physics degree at King's College London (KCL). The project was awarded a First Class mark of 85%.

This repository includes the Jupyter Notebook containing the code, computational methods, visualisations and supplementary figures supporting the investigations presented in this project.

## Abstract

This project investigates two computational problems: an optimisation problem and the numerical modelling of a physical system.

The first investigates an instance of the **Travelling Salesman Problem (TSP)** involving 30 US capital cities. Three optimisation algorithms were implemented and compared: Nearest Neighbour (NN), Simulated Annealing (SA) and a Genetic Algorithm (GA). The resulting tour lengths were 2338.63, 2285.92 and 2202.91 respectively, with the Genetic Algorithm achieving the shortest route. The stochastic nature of SA and GA was also explored in comparison to the deterministic NN algorithm.

The second investigation focuses on the **Tacoma Narrows Bridge collapse**, modelling the bridge as a beam suspended by two wires using the McKenna-Tuama model. Heatmaps, frequency-response curves and phase-trajectory plots were used to investigate the nonlinear coupling between vertical displacement and torsional motion. The results demonstrated energy transfer from the vertical mode to the torsional mode, particularly near resonant frequencies, providing insight into the possible mechanisms behind the bridge's collapse.

Additional extensions explored the implementation of a Tuned Mass Damper (TMD) as a potential solution and the modelling of the bridge as a series of connected segments using Object-Oriented Programming (OOP).
