# DBSCAN: Density-Based Spatial Clustering of Applications with Noise, Technique Exploration

**Author**: Maciej Kuchciak  
**Date**: January 2024  

[DBSCAN Technique Exploration RPubs link](https://rpubs.com/TusVasMit/DBSCANExploration)

[GitHub Pages link to project](https://mpkuchciak.github.io/dbscan-exploration/)

This project explores the **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) clustering technique, applied to a synthetic dataset. DBSCAN is a powerful method for identifying **arbitrary-shaped clusters** and **noise/outliers**.

## Project Overview

DBSCAN is a clustering algorithm that excels at identifying clusters of varying shapes and handling noise in data. This project demonstrates how DBSCAN works, including:
- **Cluster detection** in datasets with different densities.
- **Noise and outlier identification**.
- **Visualization** of the clustering process, including epsilon-neighborhood reachability and k-distance graphs.
- Use of a **synthetic dataset** to showcase DBSCAN’s flexibility and robustness.


## Project Files

```bash
dbscan-exploration/
├── README.md
├── LICENSE
├── DBSCAN.Rproj
├── .gitignore
├── Clustering.Rmd
├── docs/
│   ├── index.md                 # Main page (formerly Clustering.md)
│   ├── _config.yml              # Jekyll config for GitHub Pages
│   ├── Clustering_files/        # Figures and generated files
│   │   └── figure-gfm/
│   │       └── plotting-1.png   # Images and figures
│   ├── images/                  # Extra project images
└── Clustering_files/
    └── figure-gfm/              # Generated figures
``` 

## Getting Started

To replicate this analysis, you need to install the required R packages and set up your environment:



## Prerequisites:
R (>= 4.0)
RStudio (Optional but recommended)
r
Copy code



## Install necessary packages
if (!requireNamespace("Rtsne", quietly = TRUE)) install.packages("Rtsne")
if (!requireNamespace("ggplot2", quietly = TRUE)) install.packages("ggplot2")
if (!requireNamespace("magick", quietly = TRUE)) install.packages("magick")



## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). You are free to modify, share, and use this project under the terms of the GPL-3.0 license. If you distribute modified versions of this work, you must release them under the same license.



## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

