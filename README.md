# Gene Expression Data Analysis — Assignment 3

## Assignment Overview

For this assignment, I used Python to compare gene expression between Tumor and Normal samples. The goal was to identify probes with large differences in expression and visualize the results using Pandas, NumPy, Matplotlib, and Seaborn.

## Files Used

- **Gene_Expression_Data.xlsx:** Contains gene expression measurements.
- **Gene_Information.csv:** Provides information about the genes and probes.
- **Sample_Information.tsv:** Identifies samples as Tumor or Normal.

## Methods

I started by loading the three datasets and renaming the sample columns based on their phenotype. I then separated the Tumor and Normal samples, calculated the average expression for each probe, and determined the fold change between the two groups.

After combining the results with the gene information, I identified probes with an absolute fold change greater than 5. I also created histograms, a bar chart, a heatmap, and a clustermap to visualize the data.

## Results

The dataset contained 48,803 probes across 18 samples, including nine Tumor and nine Normal samples. My analysis identified **44 probes with an absolute fold change greater than 5**. All 44 showed higher expression in Tumor samples, resulting in 100% Tumor and 0% Normal.

## How to Run

Place all three datasets in the same folder as the Jupyter Notebook. Make sure Pandas, NumPy, Matplotlib, Seaborn, and OpenPyXL are installed, then run the notebook cells in order. The code will display the results and save the visualizations as PNG files.

## Conclusion

This assignment helped me practice organizing datasets, calculating gene expression differences, and creating visualizations in Python. It also helped me understand how data analysis can be used to explore biological differences between Tumor and Normal samples.
