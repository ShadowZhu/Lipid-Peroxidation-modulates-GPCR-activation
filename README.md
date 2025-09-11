# Data and Input Files for: Lipid peroxidation modulates GPCR activation through site-specific lipid–protein hydrogen bonds and membrane reorganization
This repository contains the GROMACS input files and simulation parameters accompanying the manuscript: <br>

**Title**: Lipid peroxidation modulates GPCR activation through site-specific lipid–protein hydrogen bonds and membrane reorganization.<br>

**Authors**: Ying Zhu, Yiyang Zhang, Zhengxi Qian, Yachong Guo, and Wei Wang (Nanjing University)<br>

### Overview

This repository provides all necessary input files to reproduce the all-atom molecular dynamics (MD) simulations described in the study. The goal is to ensure the reproducibility of our key findings by providing the initial structures, topologies, force field parameters, and simulation control files for all five systems investigated.

Note: This repository does not contain the full simulation trajectories due to their large size.

### Software and Force Field Requirements
Simulation Engine: GROMACS (version 2022.x or later recommended)

Force Field (Protein, Ions, Water): CHARMM36m

Force Field (Lipids): CHARMM36 for DUPC. Parameters for the peroxidized lipids are provided within the topology files (.itp), derived as described in the manuscript's methods section.

### Repository Contents & Usage
The primary folder, MD_configurations, contains five subdirectories, one for each simulated system.

Each system directory (e.g., DUPC/) contains the complete set of files required to run a simulation for that specific system:

initial.pdb: The starting coordinates of the solvated system.

topol.top: The main GROMACS topology file that includes all molecules.

*.itp: All necessary include topology files for the force field, molecules, and water model.

*.mdp: GROMACS simulation parameter files for each stage (energy minimization, equilibration, and production run).

A typical GROMACS workflow for each system would involve using these files sequentially for energy minimization, NVT/NPT equilibration, and finally, the production run.



### System Descriptions

The five systems simulated in this study are detailed below.

| System                           | Total Nr. of Atoms | Box dimensions (nm) | Nr. of Lipids | Nr. of Waters | Cl-  | Na+  |
|----------------------------------|--------------------|---------------------|---------------|---------------|------|------|
| (1) DUPC + AT1R + S1I8           | 215,607            | 12.9x12.8x12.9      | 445           | 50,070        | 209  | 197  |
| (2) DUPO(O13) +  AT1R + S1I8     | 216,152            | 12.9x13.1x12.5      | 442           | 50,091        | 209  | 197  |
| (3) DUPO(O9) +  AT1R + S1I8      | 217,013            | 12.8x12.9x12.9      | 448           | 50,106        | 209  | 197  |
| (4) DUPO(O13X2) +  AT1R + S1I8   | 217,593            | 14.2x14.2x10.6      | 450           | 49,892        | 258  | 198  |
| (5) DUPO(O9X2) +  AT1R + S1I8    | 217,613            | 13.3x13.5x11.8      | 448           | 49,990        | 259  | 199  |
