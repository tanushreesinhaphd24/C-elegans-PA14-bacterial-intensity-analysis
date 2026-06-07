PA14 day-wise Bacterial Intensity and Deformation Index Analysis in C. elegans
Overview
This repository contains Python scripts used to analyze intestinal bacterial colonization and intestinal deformation in Caenorhabditis elegans infected with Pseudomonas aeruginosa PA14.
The repository includes scripts for:
1.	Correlation analysis between normalized fluorescent bacterial intensity and apical membrane deformation index and generating plot figures along with statistical analysis.
2.	Correlation analysis between normalized fluorescent bacterial intensity and colony-forming units (CFU) and generating plot figures along with statistical analysis.
Repository Contents
Day-wise normalised bacterial intensity correlation with CFU
This notebook evaluates the relationship between normalized fluorescent bacterial intensity and bacterial load measured by CFU per worm.
PA14-bacterial-intensity-deformation-index-correlation-analysis
This notebook investigates the relationship between normalized fluorescent bacterial intensity and apical membrane deformation index in wild-type (L4440) and cdc-42 RNAi animals.
Statistical Analysis
The analyses use:
•	Spearman rank correlation
•	Linear trend line visualization
•	Scatter plot representation of individual biological replicates
Software Requirements
Python 3.13.5
Required packages:
•	NumPy
•	Matplotlib
•	SciPy
•	Pandas (if used in the CFU analysis notebook)

The notebooks generate:
•	Scatter plots
•	Correlation coefficients (Spearman’s ρ)
•	Associated p-values
•	Publication-quality figures

If you use this code, please cite the associated manuscript and repository DOI.
License
This repository is provided for academic and research purposes.
