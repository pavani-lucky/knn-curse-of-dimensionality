# knn-curse-of-dimensionality

# K-Nearest Neighbours and the Curse of Dimensionality

This repository contains the code and report for a tutorial exploring how the K-Nearest Neighbours (KNN) classifier behaves in low- and high-dimensional spaces using the `make_moons` dataset. The project demonstrates how the curse of dimensionality affects distance-based learning and how feature scaling and Principal Component Analysis (PCA) can mitigate these issues.


## Repository structure

- `knn_curse_of_dimensionality.ipynb`  
  Jupyter notebook with all experiments and code required to reproduce the figures in the tutorial.  
- `report/knn_curse_of_dimensionality.pdf`  
  Written tutorial (under 2000 words) aimed at students learning KNN and the curse of dimensionality.[web:46]  
- `LICENSE`  
  Licence file describing how the code and text can be reused.  
- `README.md`  
  This file.

## Installation

Create a Python 3 environment (e.g. with `venv` or Conda) and install the required packages:

pip install numpy matplotlib scikit-learn

These libraries provide data generation, modelling, preprocessing, and plotting tools used in the notebook.


## How to run

1. Clone this repository:  

git clone https://github.com/pavani-lucky/knn-curse-of-dimensionality.git
cd knn-curse-of-dimensionality

2. Start Jupyter:  

jupyter notebook

3. Open `knn_curse_of_dimensionality.ipynb`.  
4. Run all cells from top to bottom to regenerate the figures shown in the report.

## What this tutorial covers

- Intuition for KNN, Euclidean distance, and the role of the hyperparameter \(k\).  
- Behaviour of KNN on the 2D `make_moons` dataset, including decision boundaries and accuracy vs \(k\) curves. 
- Construction of a 50-dimensional version of the dataset with many noisy features to illustrate the curse of dimensionality. 
- Analysis of distance concentration via nearest/farthest distance ratios.  
- Mitigation techniques: standard feature scaling and PCA prior to KNN.
- Practical guidance and ethical considerations when using KNN on real data.

## Accessibility notes

- Plots use a colour-blind-friendly Matplotlib style for better visibility.  
- The PDF report includes descriptive figure captions so that readers using screen readers can understand the visual content.  
- Section headings follow a clear hierarchy (Introduction, Methods, Experiments, Mitigation, Conclusion) to aid navigation.

## Licence

The code in this repository is released under the MIT Licence, allowing reuse with attribution. The report text and figures may be reused for educational purposes with appropriate citation of this repository and the original data and library authors.



