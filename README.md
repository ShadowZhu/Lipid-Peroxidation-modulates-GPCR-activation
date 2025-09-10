# Lipid peroxidation modulates GPCR activation through site-specific lipid–protein hydrogen bonds and membrane reorganization

These data/instructions acompany the folowing manuscript: <br>

**Title**: Lipid peroxidation modulates GPCR activation through site-specific lipid–protein hydrogen bonds and membrane reorganization.<br>

**Authors**: Ying Zhu (Nanjing University), Yiyang Zhang (Nanjing University), Zhengxi Qian (Nanjing University), Yachong Guo (Nanjing University), Wei Wang (Nanjing University)<br>

### Data and plotting scripts for figures in the main text and supplementary information

Each folder contains the input data generated from the MD simulations, the python script used to generate the corresponding plot, and the final png image. Each data file has a header that describes each column in the file. 

Statistical analyses including mean, standard deviation, quartiles, etc. calculated within the python scripts based on the input data files.

### Initial and final configurations of MD simulations

The folder `MD_configurations` contains the initial and final configurations for all the simulations presented in the study. The files are organized into folders labeled System_\#. The system description is shown in the table below and also inside a README.md file in each folder.

| System                           | Total Nr. of Atoms | Box dimensions (nm) | Nr. of Lipids | Nr. of Waters | Cl-  | Na+  |
|----------------------------------|--------------------|---------------------|---------------|---------------|------|------|
| (1) DUPC + AT1R + S1I8           | 215,607            | 12.9x12.8x12.9      | 445           | 50,070        | 209  | 197  |
| (2) DUPO(O13) +  AT1R + S1I8     | 216,152            | 12.9x13.1x12.5      | 442           | 50,091        | 209  | 197  |
| (3) DUPO(O9) +  AT1R + S1I8      | 217,013            | 12.8x12.9x12.9      | 448           | 50,106        | 209  | 197  |
| (4) DUPO(O13X2) +  AT1R + S1I8   | 217,593            | 14.2x14.2x10.6      | 450           | 49,892        | 258  | 198  |
| (5) DUPO(O9X2) +  AT1R + S1I8    | 217,613            | 13.3x13.5x11.8      | 448           | 49,990        | 259  | 199  |
