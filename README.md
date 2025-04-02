# Master_Thesis
The name of my thesis is 
Comparison of deep learning neural networks in applications of image classification into thematic categories

It focuses on two architectures of NN design to classify images of the Faashion MNIST dataset.
One is tranfer learning from an existing CNN ( EfficientNetB0) and an ensemble of 10 much more simpler CNNs
The link to the paper is this: https://polynoe.lib.uniwa.gr/xmlui/handle/11400/8719


Abstract:
Very deep neural networks are at the heart of innovation in image classification. 
However, training and using such networks remains out of reach for projects that do not have the required computational power. 
This paper focuses on finding strategies for designing efficient neural networks with low computational 
requirements and comparing their performance in classifying images into thematic categories. 
The research resulted in two models which were implemented and evaluated. 
One is an inductive transfer learning model in which the feature extractor of EfficientNetB0 was moved to a different classifier layer. 
The second model is an ensemble of Convolutional Neural Networks, which were trained using the Bagging technique. The dataset is derived from Fashion MNIST, 
an open-access collection of images. Its data is divided into 60,000 training examples and 10,000 test examples. 
The efficiency of the models on the test set brings the transfer learning model to an accuracy of 88.56% and 91.59% for the Bagging model.
