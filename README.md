# PCA on Pokemon and MNIST
The goal of this analysis is to understand principal component analysis (PCA), one of the most widely used methods for exploratory data analysis, data visualization, and dimensionality reduction. It is also a demonstration of unsupervised transfer learning using PCA.

### Procedure
**PCA**: Run PCA on the MNIST handwritten digit data set, specifically using NumPy and good math instead of Scikit-Learn.

1. Download the MNIST dataset.
2. Plot the sorted eigenvalues of the covariance matrix.
3. Visualize and describe the top 10 principal components (as images).
4. Reconstruct images using K principal components.

**Transfer Learning**: Using the representation learned from MNIST, reconstruct Pokemon.

1. Using the previously-created MNIST PCA space, embed and reconstruct [images of Pokemon](https://github.com/peterjsadowski/pokemon_pca/blob/master/data/pokemon_mnist/pokemon_mnist_images.csv), preprocessed as 28x28 grayscale images. Use different numbers of principal components to reconstruct the Pokemon. Finally, plot the reconstruction error of the Pokemon and MNIST datasets as a function of the top K principal components for the MNIST PCA space.
2. Compare the Pokemon reconstructions made by the MNIST principal components as opposed to the principal components of of the Pokemon image dataset.