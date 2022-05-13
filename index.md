# Project Examples:

## 1. Classification Using Machine Learning Pipeline

The dataset has over 800 individual hums and whistles audio samples, consisting of Star Wars and Harry Potter labelled theme tunes. This is an example of a binary classification problem, that uses a machine learning pipeline to take an audio segment and predict its corresponding classes/label.

 **Example Spectrogram of Audio Sample: **

![](/images/Spectogram.png)

  **Example Confusion Matrix obtained from the classification task:**

![](/images/Confusion Matrix.png)

## 2. Classification Using a Neural Network:

This example includes the Fashion MNIST dataset. The data training set totals 60,000 images and the test set 10,000 images, consisting of 10 classes of various fashion items (shirt, sandal, pullover etc). Each image is 28 pixels in height and 28 pixels in width, representing a total of 784 pixels. A Multi-Layer Perceptron pipeline was built to classify each image, covering:

**Stem**: Each image was divided into non- overlapping patches. The patch size was 14 X 14 (creating 4 patches from one 28 x 28 image). Each image was reshaped and stored in a tensor of shape: 256 (batches), 4 (channels), 196 (Height X Width).

**Backbone**: One block was created. The block consists of 3 fully connected layers:

 **O1**: The transpose of x (input tensor) was passed to a linear layer and then to the RELU activation function.
 
 **O2**: The transpose of O1 was passed to a hidden linear layer and then to the RELU activation function.

 **Output**: The mean of each class was passed to SoftMax cross entropy loss function. 


## 3. Regression Examples:

Examples of regression using an analytical approach to find weights, experimenting with a variety of degrees (linear, cubic and quadratic).

![](/images/Regression Example.png)


## 4. Principle Component Analysis Example

Using the  Breast Cancer Wisconsin (Diagnostic) Data Set a Principal Component Analysis was undertaken including a scatterplot to visualise the output.


  **Example Output::**

![](/images/PCA.png)

## 4 Hadoop MapReduce:

Examples of big data processing Ethereum transaction data including:

   1. Part A: Timeseries Analysis 
   2. Part B: Top 10 Most Popular Services 
   3. Part C: Top 10 Most Active Miners 
   4. Part D:  Popular Scams and Gas Guzzlers
   
![](/images/Ether.png)





