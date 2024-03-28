## HWW-EFT-Interpretation of the ggF process

### Introduction
This repository contains all the MadGraph@NLO Job options,the Rivet job options and all the submission/running codes I have used in during my Master Thesis Project at Nikhef
on the Off-shell EFT Interpretation of the HWW channel.

In the scope of this thesis I have generated different samples of the ggF process (Signal process, known as S), the background process associated (known as B), and the full process called the SBI (Signal Background and Interference).
I have tested the impact of the EFT operators included in the SMEFTatNLO model on the ggF process. I have tested to which operators the S, B and SBI processes were sensitive to.

### Content of the repository
- Madgraph Job Options: this folder contains all the job options I used in order to generate samples with MadGraph@NLO.
  - There is a descriptive file, DSID.txt, that explains all the labelling of the processes.
  - For each process (S, B and SBI), there is a folder containing all the job options I have used.
  
- Bash-scripts: this folder contains all the different bash script, so all the commands I've type to generate processes, , run Rivet analysis, make plots or submit jobs to the cluster.
  - Generation submission to the cluster: there are the scripts I have used to submit the calculations to the cluster. There is also be a file called instructions.txt that explains how to run a generation.
  - Rivet running scripts for Rivet routines and the plotting
  - Rivet analysis compiling script

- Rivet Job Options: this folder contains one generic Rivet Job option and explain how to use it
   - A generic Rivet job option commented
  
- Rivet analysis codes: this folder contains the Rivet analysis I have used to perform the plotting 
