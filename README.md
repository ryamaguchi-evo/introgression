# Title of Dataset: Timing and Fitness Consequences of Introgression in Speciation
---

SLiM source code of our model for speciation dynamics used to generate figures in the paper.

## Description of the code and file structure

This repository contains all the necessary code and resources to perform individual-based population genetics simulations using **SLiM 4.3** (Haller and Messer, 2023). Below is an explanation of the folder structure and the contents of each directory:

### 1. Folder: Constant Population Size
This folder contains SLiM source code files designed to simulate scenarios with a constant population size. The files included are:

- **Introgression_Mutation-order.slim**  
- **Introgression_Earlyphase.slim**  
- **Introgression_Latephase.slim**  
- **Introgression_Ecological.slim**  

These files represent different simulation scenarios and are self-explanatory based on their filenames. Each file is configured for specific evolutionary conditions or events and is referenced directly in the accompanying manuscript.

---

### 2. Folder: Variable Population Size
This folder includes SLiM source code for simulations where population size changes over time. The structure and filenames mirror those in the **Constant Population Size** folder:

- **Introgression_Mutation-order.slim**  
- **Introgression_Earlyphase.slim**  
- **Introgression_Latephase.slim**  
- **Introgression_Ecological.slim**  

These files also represent specific simulation scenarios and align with those discussed in the manuscript.

---

### 3. Folder: Run and Plot
This folder contains Python scripts for managing and visualizing simulation results. These scripts include:

- **`Simulation_loop.ipynb`**  
  A Jupyter notebook used to repeatedly execute the SLiM simulation code across various parameter settings.

- **`Fitness_reduction.ipynb`**  
  A Jupyter notebook designed to analyze and plot the reduction in hybrid fitness across different migration rates.

- **`Plot.ipynb`**  
  A Jupyter notebook that reproduces figures presented in the manuscript, enabling a direct comparison with published results.

- **`Hybrid_speciation.ipynb`**  
  A Jupyter notebook that explores hybrid speciation and calculates relative establishment probabilities.

---

### Notes
All source code and scripts are organized for reproducibility and straightforward execution. Ensure that **SLiM 4.3** is installed prior to running the simulations, and refer to the relevant sections of the manuscript for detailed explanations of each simulation scenario.


Reference
Haller, B. C., & Messer, P. W. (2023). SLiM 4: multispecies eco-evolutionary modeling. The American Naturalist, 201(5), E127-E139.


## Sharing/access Information

Links to other publicly accessible locations of the data: NA
