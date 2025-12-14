# The Empirical Pareto Frontier of Automated Driving: Consensus Across Safety, Interaction, and Traffic

This repository contains the code and visualizations accompanying the paper  
**“The Empirical Pareto Frontier of Automated Driving: Consensus Across Safety, Interaction, and Traffic”**  
(*under review at Transportation Research Part C*).

The study integrates data from the **Third Generation Simulation (TGSIM)** datasets, including **Foggy Bottom** and **I-395**, to analyze how automated and human-driven vehicles trade off **safety**, **interaction**, and **traffic performance** in real-world mixed traffic environments.

![Conceptual overview of the framework](Figures/Consensus_Paper_Abstract_HR.gif)

---

## Overview

This project develops an empirical multi-dimensional framework that:
- Quantifies **behavioral consensus** across safety, efficiency, and interaction dimensions  
- Constructs an **empirical Pareto frontier** of automated driving  
- Enables cross-context comparison between urban (Foggy Bottom) and freeway (I-395) settings  

All computations and visualizations are performed through Jupyter notebooks.  
`.ipynb` files are provided here for transparency and reproducibility.

---

## Repository Contents

| File | Description |
|------|--------------|
| **[TGSIM_FB_Metrics.ipynb](./TGSIM_FB_Metrics.ipynb)** | Metric computation for the Foggy Bottom dataset, including TTC, PET, headway, jerk, deceleration, proximity time, yielding delay, hesitation and platoon gain analyses. |
| **[TGSIM_I-395_Metrics.ipynb](./TGSIM_I-395_Metrics.ipynb)** | Equivalent metric computation for the I-395 dataset, highlighting behavioral contrasts under highway conditions. |
| **[TGSIM_Consensus.ipynb](./TGSIM_Consensus.ipynb)** | Consensus quantification across safety, interaction, and efficiency dimensions using threshold-based alignment and UpSet-style visualizations. |
| **[Pareto.ipynb](./Pareto.ipynb)** | Derivation and visualization of the **Empirical Pareto Frontier**, showing trade-offs between behavioral objectives and identifying compliant versus non-compliant operating regimes. |

---

## Data Dependencies

### 1. Foggy Bottom Dataset
Available publicly from the U.S. Department of Transportation’s Data Catalog:  
➡️ [TGSIM Foggy Bottom Dataset – data.gov](https://catalog.data.gov/dataset/third-generation-simulation-data-tgsim-foggy-bottom-trajectories)

### 2. I-395 Dataset (SAE Level 2 AVs)
Available publicly from the U.S. Department of Transportation’s Data Catalog:  
➡️ [TGSIM I-395 – data.gov](https://catalog.data.gov/dataset/third-generation-simulation-data-tgsim-i-395-trajectories)


> **Note:** Both datasets must be downloaded locally before running the `.ipynb` notebooks. 

---

## Usage

To reproduce the analysis:
1. Download and extract both datasets locally.  
2. Update file paths in the notebooks if necessary.  
3. Run all notebook cells sequentially to reproduce:
   - Metric computation  
   - Consensus quantification  
   - Empirical Pareto construction  

> **Note:**  
> The analysis does not require generating every intermediate `.csv` file.  
> You may modify the notebooks to pass intermediate dataframes directly between cells or scripts instead of saving and reloading them.  
> This approach streamlines execution and reduces file I/O without affecting results.
---

## Citation

If you use this repository or its analysis in your research, please **cite it directly** until the paper is published.  
Once the journal version is available, updated citation details will be provided here.

**Suggested citation:**

Elayan, M., & Kontar, W. (2025). *The Empirical Pareto Frontier of Automated Driving: Consensus Across Safety, Interaction, and Traffic (Code Repository).* GitHub. Available at: https://github.com/wissamkontar/Consensus-AV-Analysis.git


---

## License

This project is released under the **MIT License**.
