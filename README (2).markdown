# K-Means Clustering

## Overview

This project implements a K-Means clustering algorithm using scikit-learn on a synthetic 2D dataset. It demonstrates data generation, clustering, and visualization of clusters with centroids.

## Requirements

- Python 3.x
- scikit-learn
- numpy
- matplotlib

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Install dependencies:

   ```bash
   pip install scikit-learn numpy matplotlib
   ```

## Usage

1. Run the script:

   ```bash
   python KMeans_Clustering.py
   ```

2. The script outputs the model's inertia and saves a plot as `clustering_plot.png`.

## Project Structure

- `KMeans_Clustering.py`: Main script containing the K-Means clustering implementation
- `README.md`: Project documentation
- `clustering_plot.png`: Output visualization of clusters and centroids

## Notes

- The synthetic dataset is generated with 4 clusters using `make_blobs`.
- The plot shows data points colored by cluster and red 'x' markers for centroids.
- Inertia measures the sum of squared distances of samples to their nearest centroid.