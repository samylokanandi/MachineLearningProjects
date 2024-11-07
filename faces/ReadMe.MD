Part 1 : 
 - Loads training and testing data from text files. 
 - Reads and flattens images to 1D arrays, storing them in train_data and test_data with corresponding labels.
 -Calculates and displays the average face image across the training and test datasets.
 -Subtracts the average face from each image to center the data.
 -Computes the covariance matrix, performs eigendecomposition to get eigenvalues and eigenvectors, and displays the top 10 eigenfaces.
 -Projects the data onto the top eigenfaces to create reduced features for training and testing.
 -Tests logistic regression accuracy by varying the number of eigenfaces (principal components).
 - Reconstructs images using a subset of eigenfaces and calculates the Frobenius distance to assess reconstruction accuracy.
This notebook applies PCA and logistic regression for dimensionality reduction and classification in face recognition.
Part 2 
- Loads and visualizes the Old Faithful Geyser dataset, plotting eruption time versus waiting time.
- Defines the EM algorithm for Gaussian Mixture Models (GMM) with functions for:
     - E-step: Calculates the responsibilities for each data point.
     - M-step: Updates the means, covariances, and mixing coefficients.
     - Log-Likelihood: Computes the log-likelihood to check for convergence.
- Runs the EM algorithm with k=2 clusters, tracking and plotting the trajectories of mean vectors as they converge.
      - Applies K-means clustering with k=2 to the same dataset, plotting the data points, cluster centers, and visualizing how data is segmented.
This notebook uses both EM for GMM and K-means to cluster and analyze the structure of the geyser data. ​​
