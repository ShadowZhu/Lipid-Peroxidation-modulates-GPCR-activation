# Lipid peroxidation modulates GPCR activation through site-specific lipid–protein hydrogen bonds and membrane reorganization

These data/instructions acompany the folowing manuscript: <br>

**Title**: Lipid peroxidation modulates GPCR activation through site-specific lipid–protein hydrogen bonds and membrane reorganization.<br>

**Authors**: Ying Zhu (Nanjing University), Yiyang Zhang (Nanjing University), Zhengxi Qian (Nanjing University), Yachong Guo (Nanjing University), Wei Wang (Nanjing University)<br>

### Data and plotting scripts for figures in the main text and supplementary information

Each folder contains the input data generated from the MD simulations, the python script used to generate the corresponding plot, and the final png image. Each data file has a header that describes each column in the file. 

Statistical analyses including mean, standard deviation, quartiles, etc. calculated within the python scripts based on the input data files.

### Initial and final configurations of MD simulations

The folder `MD_configurations` contains the initial and final configurations for all the simulations presented in the study. The files are organized into folders labeled System_\#. The system description is shown in the table below and also inside a README.md file in each folder.

| System                           | Total Nr. of Atoms | Box dimensions (nm) | Nr. of Lipids | Nr. of Waters | Cl- | Na+ |
|----------------------------------|--------------------|---------------------|---------------|---------------|-----|-----|
| (1) DUPC + AT1R + S1I8           | 99,132             | 10x10x11.8          | 300           | 27,388        | 13  |  0  |
| (2) DUPO(O13) +  AT1R + S1I8     | 112,330            | 10.4x0.4x13.5       | 304           | 31,068        | 13  |  0  |
| (3) DUPO(O9) +  AT1R + S1I8      | 106,560            | 10.4x10.4x13.5      | 298           | 29,050        | 13  |  0  |
| (4) DUPO(O13X2) +  AT1R + S1I8   | 90,885             | 9.5x9.5x13          | 300           | 23,789        | 13  |  0  |
| (5) DUPO(O9X2) +  AT1R + S1I8    | 106,662            | 10.4x10.4x13.5      | 298           | 29,050        | 13  |  0  |
