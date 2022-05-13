## David Cullen Data Science Portfollio

### Project Examples:

This is an overview of projects I have completed using Python. 

# 1. Classification Using Machine Learning Pipeline

The machine learning problem is in relation to #Hums and Whistles Audio Dataset Sample# of Starwars and Harry Potter themetunes. The problem that this work aims to solve is binary classification, building a machine learning pipeline that takes as an input a Potter or Starwars audio segment and predicts its song and label.

[](https://github.com/DavidJCullen/Data-Science-Portfolio-/blob/gh-pages/images/Unknown-2.png)

# 2. Classification Using a Neural Network

**Stem**: A member function was created in Net Class. Each image was divided into non- overlapping patches. The patch size was 14 X 14 (creating 4 patches from one 28 x 28 image). In order to do this torch, unfold was used specifying the dimensions which the unfolds were to occur, the kernel size (slice size) and stride (step) length. The unfold was reshaped to the following tensor shape: 256 (batches), 4 (channels) and 196 (Height X Width).

**Backbone**: One block was created within the Net Class. The block consists of 3 fully connected layers:

**O1**: the transpose of x was passed to a linear layer and then to the RELU activation function.
Second Multi-Layer Perceptron:

**O2** : the transpose of O1 was passed to a hidden linear layer and then to the RELU activation function.

**Output**:Mean class: the mean of each class was passed to SoftMax cross entropy loss function. 


# 3. Regression Examples:

Examples of regression from using an analytuical approach to find weights in linear regression, to expermenting with a variety of orders.


# 4 Hadoop MRJob MapReduce 

Examples of big data processing using MapReduce.







