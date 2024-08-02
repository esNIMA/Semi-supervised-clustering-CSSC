# CSSC Algorithm Implementation

## Overview

This repository contains an implementation of the Compact-Cluster Semi-Supervised Clustering (CSSC) algorithm. The CSSC algorithm is designed to improve clustering performance by utilizing both labeled and unlabeled data under the compact-cluster assumption. This implementation includes functions for splitting and merging clusters to maintain compactness, and integrates with the scikit-learn framework for ease of use.
The CSSC algorithm is based on the paper "Semi-Supervised Clustering Under a 'Compact-Cluster' Assumption" by Zhen Jiang, Yongzhao Zhan, Qirong Mao, and Yang Du.

- Semi-supervised clustering using the compact-cluster assumption
- Integration with scikit-learn's BaseEstimator and ClassifierMixin
- Functions for computing cluster compactness, splitting clusters, and merging clusters
- Visualization of labeled and unlabeled data, as well as the final clustering results

## Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-learn

## Installation and usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/cssc-algorithm.git
2. Define the class and its functions. 
3. Fit the CSSC algorithm to the data
  ```bash
  cssc = CSSCClassifier(alpha=0.7, max_iter=100)
  cssc.fit(X_labeled, y_labeled, X_unlabeled)
4. Predict the new data
  ```bash
  y_pred = cssc.predict(X_test)

