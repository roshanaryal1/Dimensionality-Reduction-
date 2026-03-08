# 📐 Dimensionality Reduction with PCA

A comprehensive, beginner-friendly Jupyter Notebook tutorial on **Dimensionality Reduction** using **Principal Component Analysis (PCA)** in Python.

---

## 📖 Overview

In machine learning, **dimensionality** refers to the number of features (columns) in a dataset. High-dimensional data can lead to overfitting, increased computation cost, and difficulty in visualization. **Dimensionality Reduction** is the process of reducing the number of features while preserving as much useful information as possible.

This notebook provides a complete, hands-on walkthrough of PCA — the most popular dimensionality reduction technique — with clear explanations, visualizations, and real-world examples.

---

## 📂 Contents

The notebook is structured into the following parts:

### Part 1: PCA on Synthetic 2D Data
- Understanding PCA mechanics visually
- Creating correlated 2D data
- Centering data, computing covariance matrix, eigenvectors & eigenvalues
- Projecting data onto principal components
- Visualizing PCA directions and variance explained

### Part 2: PCA on the Digits Dataset (High-Dimensional Real Data)
- Applying PCA to the sklearn digits dataset (64 dimensions)
- Explained variance ratio and cumulative variance
- Choosing the optimal number of components
- Visualizing high-dimensional data in 2D using PCA

### Part 3: Classification — Original vs PCA-Compressed Data
- Training classifiers on original and PCA-reduced data
- Comparing accuracy between full and compressed features
- Understanding the trade-off between dimensionality and performance

### Summary
- Key takeaways about PCA
- When PCA works well and when it doesn't
- Comparison with other techniques (t-SNE, UMAP, LDA, Autoencoders)

---

## 🛠️ Technologies & Libraries

- **Python 3**
- **NumPy** — Numerical computing & matrix operations
- **Matplotlib** — Data visualization & plotting
- **Seaborn** — Statistical data visualization
- **Scikit-learn** — PCA implementation & Digits dataset

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3 and the following packages installed:

```bash
pip install numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/roshanaryal1/Dimensionality-Reduction-.git
   cd Dimensionality-Reduction-
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Dimensionality_Reduction_Complete.ipynb
   ```

3. Run all cells sequentially to see the full tutorial with outputs and visualizations.

---

## 🎯 Key Concepts Covered

| Concept | Description |
|---|---|
| **Curse of Dimensionality** | As features grow, data becomes sparse and models overfit |
| **Covariance Matrix** | Measures how each pair of features varies together |
| **Eigenvectors & Eigenvalues** | Directions of maximum variance and their magnitudes |
| **Explained Variance Ratio** | How much information each principal component captures |
| **Dimensionality vs Accuracy** | Trade-off between fewer features and model performance |

---

## 📊 Visualizations Included

- Scatter plots of original and PCA-transformed data
- Principal component direction arrows
- Explained variance plots (bar & cumulative)
- Digit images before and after reconstruction
- Classification accuracy comparison charts

---

## 👤 Author

**Roshan Aryal**

---

## 📄 License

This project is open source and available for educational purposes.
