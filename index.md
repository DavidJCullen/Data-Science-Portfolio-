# Project Examples:

This is an overview of projects I have completed using Python. 

## 1. Classification Using Machine Learning Pipeline

The dataset has 800 indiviudal hums and whistles audio samples, consisting of Starwars and Harry Potter theme tunes. The problem solved is a binary classification, building a machine learning pipeline that takes as an input Potter or Starwars audio segment and predicts the song and label.


  **Example Confusion Matrix obtained from the classification task:**

![](https://github.com/DavidJCullen/Data-Science-Portfolio-/blob/gh-pages/images/Confusion%20Matrix.png)

## 2. Classification Using a Neural Network:

The Fashion MNIST data was loaded using the utils.py file. The data training set totals 60,000 images and the test set 10,000 images, consisting of 10 classes  of various fashion items (shirt,sandal, pullover etc). Each image is 28 pixels in height and 28 pixels in width, representing a total of 784 pixels. An MLP pipeline was built to classsify each image covering:

**Stem**: Each image was divided into non- overlapping patches. The patch size was 14 X 14 (creating 4 patches from one 28 x 28 image). In order to do this torch, unfold was used specifying the dimensions which the unfolds were to occur, the kernel size (slice size) and stride (step) length. The unfold was reshaped to the following tensor shape: 256 (batches), 4 (channels) and 196 (Height X Width).

**Backbone**: One block was created. The block consists of 3 fully connected layers:

 **O1**: The transpose of x was passed to a linear layer and then to the RELU activation function.
 
 **O2** : The transpose of O1 was passed to a hidden linear layer and then to the RELU activation function.

 **Output**: The mean of each class was passed to SoftMax cross entropy loss function. 


# 3. Regression Examples:

Examples of regression from using an analytuical approach to find weights in linear regression, to expermenting with a variety of orders.

![](https://github.com/DavidJCullen/Data-Science-Portfolio-/blob/gh-pages/images/Regression%20Example.png)

# 4. Principle Component Analysis Example

Using the pre-processed breast cancer dataset, a Principal Component Analysis has been undertaken. The exampled variance ratio for each component has been computed, and  scatterplot of all samples along two principal components, color-coded according to the "Class" column has been provided.


  **Example Output::**

![](https://github.com/DavidJCullen/Data-Science-Portfolio-/blob/gh-pages/images/PCA.png)

# 4 Hadoop MRJob MapReduce:

Examples of big data processing using MapReduce including:

   1. Part A: Timeseries Analysis 
   2. Part B: Top 10 Most Popular Services 
   3. Part C: Top 10 Most Active Miners 
   4. Part D:  Popular Scams and Gas Guzzlers
   
![](https://github.com/DavidJCullen/Data-Science-Portfolio-/blob/gh-pages/images/Ether.png)
   








