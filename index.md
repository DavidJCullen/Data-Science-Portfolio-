## David Cullen Data Science Portfollio

You can use the [editor on GitHub](https://github.com/DavidJCullen/Data-Science-Portfolio-/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Project Examples:

This is an overview of projects I have completed using Python. 

# Classification Machine Learning Pipeline

The machine learning problem is in relation to #Hums and Whistles Audio Dataset Sample# of Starwars and Harry Potter themetunes. The problem that this work aims to solve is binary classification, building a machine learning pipeline that takes as an input a Potter or Starwars audio segment and predicts its song and label.


# Multi-layer Perceptron Neural Network to Classify MNIST Fashion Dataset


**Stem**: A member function was created in Net Class. Each image was divided into non- overlapping patches. The patch size was 14 X 14 (creating 4 patches from one 28 x 28 image). In order to do this torch, unfold was used specifying the dimensions which the unfolds were to occur, the kernel size (slice size) and stride (step) length. The unfold was reshaped to the following tensor shape: 256 (batches), 4 (channels) and 196 (Height X Width).

**Backbone**: One block was created within the Net Class. The block consists of 3 fully connected layers:

**O1**: the transpose of x was passed to a linear layer and then to the RELU activation function.
Second Multi-Layer Perceptron:

**O2** : the transpose of O1 was passed to a hidden linear layer and then to the RELU activation function.

**Output**:Mean class: the mean of each class was passed to SoftMax cross entropy loss function. 




- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DavidJCullen/Data-Science-Portfolio-/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
