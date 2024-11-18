# TIMOrientationAnalysis
Residue orientation analysis for substrate's residue side chains when translocating through TIM.

## Requirements
- python >= 3.10.10
- MDAnalysis >= 2.2.0
- numpy >= 1.24.2
- matplotlib >= 3.7.1

## Installation
The above dependencies can be installed using Anaconda or any other package manager.

## Demo
Use the provided Jupyter Notebook `pub_analyze_residues_orientation.ipynb` to run the analysis interactively.
### Input files
1. Structure and run input files: `.gro`, `.tpr`
2. SMD trajectories: `.xtc`
### Expected output
Running the analysis script will generate a figure illustrating residue orientation distributions. The process typically completes within a few minutes.

