# Traffic-signs-detection
# What is traffic signs recoginition?
There are several different types of traffic signs like speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. Traffic signs classification is the process of identifying which class a traffic sign belongs to.
# Aim 
Aim of traffic signs recoginition project is that as now a days autonomous vehicles are coming so in that case this is very important, so that the automatic vehicles will be able to recognize that what is meaning of that sign and be able to follow rules .
# About this project 
In this project, i have build a deep neural network model that can classify traffic signs present in the image into different categories. With this model, we are able to read and understand traffic signs which are a very important task for all autonomous vehicles.
# The dataset 
The dataset contains more than 50,000 images of different traffic signs. It is further classified into 43 different classes. The dataset is quite varying, some of the classes have many images while some classes have few images. The size of the dataset is around 300 MB. The dataset has a train folder which contains images inside each class and a test folder which we will use for testing our model.
Dataset link:
https://github.com/barkha000/Traffic-signs-detection.git
# Contents
1. Explore the dataset
2. Build a CNN model
3. Train and validate the model
4. Test the model with test dataset
5. Predict the result
# Libraries used
1. numpy
2. pandas
3. matplotlib
4. tensorflow
5. PIL
6. model-selection
6. keras.utils
7. keras.models
8. keras.layers
# About this project
In this project i have use dataset from kaggle then i imported necessary libraries , then i perform EDA, then i build CNN model because CNN model is best for image classification purpose,
#Architecture of our model are:
2 Conv2D layer (filter=32, kernel_size=(5,5), activation=”relu”)
MaxPool2D layer ( pool_size=(2,2))
Dropout layer (rate=0.25)
2 Conv2D layer (filter=64, kernel_size=(3,3), activation=”relu”)
MaxPool2D layer ( pool_size=(2,2))
Dropout layer (rate=0.25)
Flatten layer to squeeze the layers into 1 dimension
Dense Fully connected layer (256 nodes, activation=”relu”)
Dropout layer (rate=0.5)
Dense layer (43 nodes, activation=”softmax”)

then i train and validate the model to predict best,then i test my model with test dataset,then at last my model get ready to predict the name of traffic sign.
# Thank-You




