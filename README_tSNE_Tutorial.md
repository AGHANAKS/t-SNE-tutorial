# Visualizing High-Dimensional Data with t-SNE

This tutorial demonstrates how to use t-SNE (t-distributed Stochastic Neighbor Embedding) to visualize high-dimensional data. The example uses the Digits dataset from scikit-learn, which contains 1,797 handwritten digit images represented by 64 features each. The tutorial includes comparisons with PCA and emphasizes the strengths and limitations of t-SNE for data exploration.

## Files

- tsne_visualization_digits_tutorial.ipynb: Main notebook with full implementation and visualizations
- README.md: This file with instructions
- requirements.txt: Python dependencies required to run the notebook

## Dataset

The Digits dataset is included in scikit-learn. It consists of 8x8 grayscale images of digits (0-9), flattened into 64 features. It is commonly used for testing clustering, dimensionality reduction, and classification algorithms.

## Learning Objectives

- Understand the difference between PCA and t-SNE
- Visualize high-dimensional data using 2D embeddings
- Interpret how t-SNE preserves local structure in data
- Use Python and seaborn to create meaningful visual comparisons

## How to Run

1. Clone the repository or download the files
2. Install the required dependencies using:
   pip install -r requirements.txt
3. Open and run the notebook:
   jupyter notebook tsne_visualization_digits_tutorial.ipynb

## Acknowledgements

- The Digits dataset is available via scikit-learn
- Inspired by t-SNE research by van der Maaten and Hinton (2008)
- Tutorial structure based on educational resources and visualization best practices
