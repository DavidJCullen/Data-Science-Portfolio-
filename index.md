# Project Examples:

## [1. Classification Using Machine Learning Pipeline](https://github.com/DavidJCullen/ML-Pipeline-for-Classification/blob/main/Hums_and_Whistles_ML_Pipeline_(Binary_Class)_MileEnd_Dataset_.ipynb)

This is an example of a binary classification problem, that uses a machine learning pipeline to take an audio segment and predict its corresponding classes/label:

  **Data Extraction/Data Preparation**
   
   Input: the input audio data in .wav format derives from MLEnd Hums and Whistles Potter and StarWars public dataset, totalling 417 Potter and 417   StarWars samples.

  **Transformation:**

   Feature extraction was used to extract signal data from the input data.

   Feature selection/filtering using Pearson’s Correlation Coefficient above threhold of 0.50.

   Label encoding converting Potter and StarWars categorical data to boolean values (True and False).

   Linear tranformation of the extracted feature data using MinMaxScaler.

   **Models Explored:**

   A support Vector Machine, K-nearest neighbour classification and a Stacking Classifier using LogisticRegression as the final estimator has been used as a model for prediction on the dataset.

  Output: Transformed data passed to the machine learning models for training and validation.

  **Model Evaluation:**

   Model validation performance evaluated using classification metrics (f-score, precision and recall) and Matthews correlation coefficient (MCC).

  **Example Confusion Matrix obtained from the classification task:**

![](/images/Confusion Matrix.png)

## [2. Classification Using a Neural Network](https://github.com/DavidJCullen/MLP-Classificatiion-MNIST-Fashion-Dataset/blob/main/MLP%20Classification%20.ipynb):

This example includes the Fashion MNIST dataset. The data training set totals 60,000 images and the test set 10,000 images, consisting of 10 classes of various fashion items (shirt, sandal, pullover etc). Each image is 28 pixels in height and 28 pixels in width, representing a total of 784 pixels. A Multi-Layer Perceptron pipeline was built to classify each image, covering:

**Stem**: Each image was divided into non- overlapping patches. The patch size was 14 X 14 (creating 4 patches from one 28 x 28 image). Each image was reshaped and stored in a tensor of shape: 256 (batches), 4 (channels), 196 (Height X Width).

**Backbone**: One block was created. The block consists of 3 fully connected layers:

 **O1**: The transpose of x (input tensor) was passed to a linear layer and then to the RELU activation function.
 
 **O2**: The transpose of O1 was passed to a hidden linear layer and then to the RELU activation function.

 **Output**: The mean of each class was passed to SoftMax cross entropy loss function. 
 
 
  **Example training accuracy output:**
  
 ![](/images/MLP.png)


## [3. Regression Examples](https://github.com/DavidJCullen/Regression-/blob/main/Regression.ipynb):

Examples of regression using an analytical approach to find weights, experimenting with a variety of degrees (linear, cubic and quadratic).

![](/images/Regression Example.png)


## [4. Principal Component Analysis Example](https://github.com/DavidJCullen/PCA-Example/blob/main/Principle%20Component%20Analysis%20Example%20Using%20Wisconsin%20Breast%20Cancer%20Data.ipynb)

Using the  Breast Cancer Wisconsin (Diagnostic) Data Set a Principal Component Analysis was undertaken including a scatterplot to visualise the output.


  **Example Output::**

![](/images/PCA.png)

## [5.MapReduce (Hadoop Cluster](https://github.com/DavidJCullen/MapReduce-Example):

Examples of big data processing and analysis using Ethereum transaction data:

   1. Part A: Timeseries Analysis of Ethereum Transactions:
   2. Part B: Top 10 Most Popular Services on Ethereum:
   3. Part C: Top 10 Most Active Etherem Miners:
   4. Part D:  Popular Scams and Gas Guzzlers on Ethereum Ledger:
   
![](/images/Ether.png)





