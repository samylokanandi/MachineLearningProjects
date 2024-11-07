
---

# Homework 3 - PCA, Logistic Regression, and Clustering

This project consists of two parts: **Part 1** focuses on face recognition using PCA and logistic regression, while **Part 2** applies clustering techniques on the Old Faithful Geyser dataset using the Expectation-Maximization (EM) algorithm and K-means.

---

## Part 1: Face Recognition with PCA and Logistic Regression

This notebook utilizes **Principal Component Analysis (PCA)** and **logistic regression** to perform dimensionality reduction and classification on a face dataset.

### Steps:
1. **Data Loading**:
   - Loads training and testing data from text files.

2. **Image Preparation**:
   - Reads and flattens images to 1D arrays, storing them in `train_data` and `test_data` with corresponding labels.

3. **Average Face Calculation**:
   - Calculates and displays the average face image across the training and test datasets.

4. **Mean Subtraction**:
   - Subtracts the average face from each image to center the data.

5. **Eigendecomposition and Eigenfaces**:
   - Computes the covariance matrix, performs eigendecomposition to obtain eigenvalues and eigenvectors, and displays the top 10 eigenfaces.

6. **Feature Generation**:
   - Projects the data onto the top eigenfaces to create reduced features for training and testing.

7. **Logistic Regression Accuracy**:
   - Tests logistic regression accuracy by varying the number of eigenfaces (principal components).

8. **Image Reconstruction and Frobenius Distance**:
   - Reconstructs images using a subset of eigenfaces and calculates the Frobenius distance to assess reconstruction accuracy.

### Summary:
This notebook applies PCA for dimensionality reduction and logistic regression for classification, making it suitable for face recognition tasks.

---

## Part 2: Clustering the Old Faithful Geyser Dataset

This notebook applies **clustering algorithms** to analyze the structure of the Old Faithful Geyser dataset.

### Steps:
1. **Data Loading and Visualization**:
   - Loads the Old Faithful Geyser dataset and visualizes it by plotting eruption time versus waiting time.

2. **Expectation-Maximization (EM) Algorithm for Gaussian Mixture Models (GMM)**:
   - Defines and runs the EM algorithm with \( k=2 \) clusters, tracking and plotting the trajectories of mean vectors as they converge.
   - **E-step**: Calculates the responsibilities for each data point.
   - **M-step**: Updates the means, covariances, and mixing coefficients.
   - **Log-Likelihood**: Computes the log-likelihood to check for convergence.

3. **K-means Clustering**:
   - Applies K-means clustering with \( k=2 \) to the same dataset, plotting data points, cluster centers, and visualizing how data is segmented.

### Summary:
This notebook uses both EM for GMM and K-means to cluster and analyze the structure of the geyser data, providing insights into its natural grouping.

---

