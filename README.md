# Dimensionality Reduction Analysis of the CIFAR-10 Dataset using PCA and t-SNE

This code performs an exploratory data analysis (EDA) on the CIFAR-10 dataset, a widely used dataset for image classification tasks. The key steps are:

# Load the CIFAR-10 dataset: 
The code loads the CIFAR-10 dataset from the Keras library and prints the shapes of the training and testing data.
Explore the dataset: The code finds the unique classes in the dataset and prints the total number of output classes, as well as the class labels.

# Preprocess the data: 
The code normalizes the pixel values of the training data to the range [0, 1].
Flatten the training data: The code flattens the 3D training data (images) into a 2D matrix and creates a pandas DataFrame with the flattened data and the corresponding labels.

# Perform Principal Component Analysis (PCA): 
The code applies PCA to the flattened training data and creates a 2D scatter plot of the first two principal components, colored by the class labels.

# Perform t-SNE visualization: 
The code applies t-SNE (t-Distributed Stochastic Neighbor Embedding) to the flattened training data and creates another 2D scatter plot, again colored by the class labels.

These visualizations help to understand the structure and separability of the different classes in the CIFAR-10 dataset, which can provide valuable insights for building effective image classification models. By using both PCA and t-SNE, the code provides complementary views of the data's underlying structure, allowing for a more comprehensive exploration of the dataset.
