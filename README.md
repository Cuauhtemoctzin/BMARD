# BMARD
Bayesian Mixture Auto-Regressive Decomposition of time series into latent processes

## Data

We share two types of data to test the BMARD method

### SimulationDATABASES
Databases of the periodograms computed for each of the simulations settings described in section 3.

### Test_data 
PseudoData based on the odor C=Anise trial, presented in incorrect order (OutSeq) before and after the odor delivery.

## Code

The structure of the code is clasiffied in several folders, for higher details consult the Reproduce_instructions.docx guide and BMARD_simuations_data_dictionary.txt file in the README folder.

### BASHcode_HPCclusters
Auxiliary codes and technical specifications for running BMARD on HPC clusters managed by SLURM

### CPPcode
Main Rcpp code of BMARD and the Bernstein polynomial method of Choudhuri (2014)

### Rcode_auxiliary
Auxiliary R code for MCMC post processing and simulations generation


## Instructions for use

In Rstudio run the following code to replicate the BMARD fitting on simulations settings. 

BMARD_Simulation_Replication.R

To test BMARD on the pseudodata, in Rstudio run the following code

BMARD_DATA_Replication.R
