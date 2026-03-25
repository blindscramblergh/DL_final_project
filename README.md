# DL_final_project
This is the repo for my final DL project.

The data consists of ensemble MHD simulation runs of an ensemble of one Coronal Mass Ejection (CMEs). 

## Coronal Mass Ejection simulations
This is a Uncertainty quantification of initial values problem. The magnetic profile of CMEs are hard to predict. This is because the observations of CMEs close to the Sun are plagued with uncertainties. I think a ML technique for quantifying this uncertainties would be something substantial. 

If I can make this work, a neural network can look at the time series data and understand the degree to which each of the ensemble runs explain "the real observation." After performning this training for the first few hours of the CME transit, the rest of a CME's magnetic profile could be predicted. 

## Data Generation
There is no URL, I generated this data by running physics based simulations using an MHD fluid model developed by my team.
