# TGSIM AV-HDV Comparative Behavior Analysis

This repository contains code used for analyzing and comparing the behavior of Automated Vehicles (AVs) and Human-Driven Vehicles (HDVs) during left-turn interactions with vulnerable road users (VRUs) using the **Third Generation Simulation (TGSIM) Foggy Bottom** dataset.

## Repository Contents

- **[TGSIM_Analysis_Published.ipynb](./TGSIM_Analysis_Published.ipynb)**:  
  A fully annotated Jupyter notebook that calculates and generates:
  - Time-to-Collision (TTC) and Post-Encroachment Time (PET) metrics
  - Headways 
  - Platoons
  - String stability
  - AV-VRU interactions across safety, interaction quality, and performance dimensions
  - Key figures and plots featured in our initial paper submission

## Data Dependency

**Note**: Due to file size limitations, the full trajectory dataset is **not included** in this repository.  
You must download the `Third_Generation_Simulation_Data__TGSIM__Foggy_Bottom_Trajectories.csv` dataset separately from the U.S. Department of Transportation's Data Catalog:

[TGSIM Foggy Bottom Dataset – data.gov](https://catalog.data.gov/dataset/third-generation-simulation-data-tgsim-foggy-bottom-trajectories)

## Usage

To reproduce the analysis:
1. Download and extract the dataset locally.
2. Update file paths in the notebook if needed.
3. Run all cells in `TGSIM_Analysis_Published.ipynb` sequentially.
