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
DBSCANExploration/
├── README.md                     # Project overview and instructions
├── LICENSE                       # License file for the project
├── .gitignore                    # List of files/folders ignored in version control
├── .gitattributes                # Git settings for line endings and other attributes
├── DBSCANExploration.Rproj       # R project file for easy setup in RStudio
├── src/                          # Source files for analysis
│   ├── Clustering.Rmd            # Main RMarkdown file for DBSCAN analysis
│   ├── Clustering.md             # Generated Markdown output (without adjustments for GitHub Pages)
│   ├── Clustering_files/         # Auto-generated figures and images from RMarkdown
│   └── R.File/                   # Folder for R script outputs from purling RMarkdown
│       ├── main.R                # Script to purl Clustering.Rmd into R code
│       └── Clustering.R          # Auto-generated R code extracted from Clustering.Rmd
├── docs/                         # GitHub Pages website files
│   ├── index.md                  # Main page for GitHub Pages site (based on Clustering.md)
│   ├── _config.yml               # Jekyll configuration for GitHub Pages
│   ├── Clustering_files/         # Auto-generated figures and images for GitHub Pages
│   └── images/                   # Additional images for the website
├── images/                       # Extra project images (plots, figures, etc.)
│   └── dbscan_clustering_example.gif # Animation illustrating the clustering process

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

