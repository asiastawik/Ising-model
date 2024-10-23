# Metropolis Algorithm for the Ising Model

This project implements the Metropolis algorithm for simulating the Ising model on a two-dimensional square lattice without a magnetic field. The goal is to study the behavior of spin configurations under various temperature conditions.

## Project Structure


## Simulation Overview

### Description

The program simulates the Ising model on a `L x L` square lattice for various lattice sizes (`L = 10, 20, 40, 80`). The Metropolis algorithm is used to evolve the spin configurations over a specified number of Monte Carlo (MC) steps. 

### Tasks

1. **Spin Configuration Visualization**:
   - Generate spin configurations after 100 MC steps for lattice sizes `10 x 10` and `80 x 80` at three temperatures:
     - \( T_1 = 1 \)
     - \( T_2 = 2.26 \)
     - \( T_3 = 4 \)
   
2. **Trajectory Visualization**:
   - For \( T_1 = 1 \), plot 10 trajectories for each lattice size \( L \). Four figures will be generated for different lattice sizes.
   
3. **Critical Temperature Analysis**:
   - For three different temperatures around the critical temperature \( T^* \) (below, at, and above), plot trajectories similar to the previous task.

4. **Magnetization vs. Temperature**:
   - Plot magnetization as a function of temperature \( T \) for the range \( T = 0.5 : 0.05 : 3.5 \). 
   - Include results for all lattice sizes in one figure, using different symbols to distinguish between them.
