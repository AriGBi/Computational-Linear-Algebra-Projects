# Computational Linear Algebra Projects

This repository contains three projects developed for the **Computational Linear Algebra** course, exploring practical applications of numerical linear algebra in graph analysis, dimensionality reduction, clustering, and facial recognition.

## Projects

### 1. PageRank — Sparse Matrix Computations

**Objective:** Investigate the mathematical foundations of PageRank and develop an efficient implementation for large-scale web graphs.

The project explores how different graph structures affect webpage rankings and investigates the convergence behavior of the Power Method.

**Key contributions:**
- Analyzed the impact of link structures, disconnected subgraphs, and teleportation on PageRank scores.
- Studied Power Method convergence and its relationship with the second-largest eigenvalue.
- Implemented PageRank using **Compressed Sparse Row (CSR)** representation for efficient sparse matrix-vector multiplication.
- Handled dangling nodes without explicitly constructing dense matrices.

**Results:** Successfully applied the algorithm to the Hollins web graph, containing **6,012 nodes and 23,875 links**, demonstrating efficient ranking computation on sparse networks.

---

### 2. PCA — Survey Data Analysis and Clustering

**Objective:** Apply Principal Component Analysis and clustering techniques to identify patterns in survey responses related to personality, interests, and lifestyle.

**Key contributions:**
- Preprocessed survey data using ordinal encoding and feature standardization.
- Applied PCA to analyze explained variance and reduce dimensionality.
- Interpreted principal components to identify underlying behavioral patterns.
- Performed **K-Means clustering** in the reduced-dimensional space, selecting the number of clusters through silhouette analysis.
- Evaluated cluster quality and relationships with demographic variables.

**Results:** Identified three behavioral profiles based on personality traits and lifestyle preferences, while assessing the limitations of their separation.

---

### 3. SVD — Eigenfaces for Facial Recognition

**Objective:** Develop a facial recognition system using Eigenfaces and a custom Singular Value Decomposition implementation, investigating the trade-off between accuracy and computational efficiency.

**Key contributions:**
- Implemented a custom SVD procedure using Householder-based bidiagonalization, tridiagonal eigendecomposition, and QR decomposition with column pivoting.
- Compared three recognition approaches: nearest-neighbor classification, mean-based representation, and PCA-based Eigenfaces.
- Applied dimensionality reduction to the **Olivetti Faces dataset**, containing 400 images of 40 individuals.

**Results:** Achieved **97.5% recognition accuracy using 50 principal components** and **90% accuracy with only 7 components**, demonstrating the trade-off between recognition accuracy and computational efficiency through dimensionality reduction.

---

## Technologies & Libraries

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** NumPy, SciPy, pandas, scikit-learn, Matplotlib

```

Each project folder contains the corresponding implementation and supporting materials.
