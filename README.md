# ML From Scratch Implementation

This repository contains educational implementations of fundamental Machine Learning algorithms built from scratch using only `NumPy`. The project serves as a reference to understand the mathematical mechanics behind these models compared to standard `scikit-learn` implementations.

## Implemented Algorithms
- **PCA:** SVD-based dimensionality reduction.
- **K-Means:** Centroid-based clustering (with L1, L2, and Linf distance metrics).
- **KNN:** K-Nearest Neighbors classifier.
- **SGD Regressor:** Linear regression using Stochastic Gradient Descent.

## Dataset
The implementation uses the **Boston Housing dataset** for benchmarking and validation.

## Usage
1. Ensure the `Boston_Housing.xlsx` file is in the project directory.
2. Run the `ML from scratch.ipynb` notebook to see the comparison between custom implementations and `scikit-learn` benchmarks.

*Note: Some algorithms (e.g., K-Means) are defined for educational purposes and may not be fully integrated into the test pipeline in the current version.*
