# DCM for ERPs
This repository contains an example EEG dataset from an aged healthy control participant, taken from Tyrer, et al. (2020) https://doi.org/10.1093/braincomms/fcaa212.

## Data
Contains the example EEG data files along with corresponding SPM gain matrix file. Example_MNI_coords.mat contains a set of MNI coordinates that can be used to define the electromagnetic model, i.e., specify the source locations, within the SPM DCM GUI.

## DCMs
Contains two example DCM files that were generated using different B matrices: one full B matrix (forward, backward and self modulatory connections) and one partial B matrix (forward modulatory connections only). 
