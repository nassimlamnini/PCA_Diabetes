# PCA Analysis of Diabetes Dataset

## Overview
This repository contains a Jupyter Notebook where I've conducted a Principal Component Analysis (PCA) on the diabetes dataset available from the sklearn library.

## Objective
The goal of this analysis was to reduce the dimensionality of the diabetes dataset while preserving as much of the data's variation as possible. By transforming the dataset into principal components, I sought to identify the underlying structure and simplify the complexity of the dataset without significant loss of information.

## Methodology

- **CLeaning the Data**: by observing the correlation matrix to identify what to keep and what to drop
- **Data Standardization**: To ensure that each feature contributed equally to the analysis, I standardized the dataset.
- **PCA Application**: I applied PCA to the standardized data to identify the principal components.
- **Elbow Plot Creation**: To determine the optimal number of principal components, I created an elbow plot which showed the explained variance ratio.
- **Data Reconstruction**: After reducing the dimensions, I reconstructed the data from the principal components to visualize the loss of information.

## Results
By examining the elbow plot, I chose to reduce the dataset to two principal components which captured the majority of the variance in the data. The subsequent scatter plots and quiver plots showed how well the selected principal components represented the original data.

## Usage
The notebook is designed to be self-explanatory. Users can run the notebook in a Jupyter environment to reproduce the analysis.

## Requirements
To execute the notebook, you will need Python installed along with the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`

Thank you for visiting this repository and exploring PCA with the diabetes dataset.
