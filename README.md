# Multivariate-PCA-and-Cluster-Analysis-of-Wheat-Kernel-Varieties-Using-Non-Destructive-X-Ray-Imaging

## Introduction
This project focuses on clustering and principal component analysis (PCA) of wheat kernel geometrical properties. The dataset consists of three different varieties of wheat: Kama, Rosa, and Canadian. The aim is to analyze and visualize the data to understand the differences between these varieties.

## Dataset
The dataset used for this project can be found at the following link: [Wheat Kernel Dataset](https://archive.ics.uci.edu/dataset/236/seeds). The dataset contains 210 instances with seven real-valued attributes representing geometrical properties of the kernels.

## Project Structure
- `data/`: Contains the dataset files.
- `Seeds_Unsupervised_Analysis.ipynb`: Jupyter notebook for data analysis and visualization.


## Requirements
To run the project, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Feature Selection
The following features were used for clustering and PCA:
1. Area
2. Perimeter
3. Compactness
4. Length of Kernel
5. Width of Kernel
6. Asymmetry Coefficient
7. Kernel Grooving

## Models
The following models were implemented:
- K-Means Clustering
- Hierarchical Clustering
- PCA

## Results
The results of the clustering and PCA analysis will be discussed in detail in the corresponding notebooks.

## Future Improvements
Future work could include experimenting with different clustering algorithms, feature engineering, and enhancing the visualizations.
