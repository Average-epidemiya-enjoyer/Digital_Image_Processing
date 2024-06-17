This repository contains several laboratory works for the exam in the subject "Digital Image Processing" considered as part of the "Technical Vision" curriculum at ITMO University

Lab №3

In general, there were no problems with the mnist dataset, however, the FashionMNIST results can be somewhat misleading, since even after studying some of the images in the dataset one cannot always tell which class an image belongs to.

Lab №4  
For test model additionally, I selected a dataset from Kaggle:  
url: https://www.kaggle.com/datasets/yiyanghao/sushidataset

This test showed that despite the fact that the final dataset was expanded, the models increased the number of layers and the optimal number of epochs was selected, in some complex pictures the model gave the wrong result, in the future it is possible to select several different datasets, further increasing the training set.

Lab №5

Going modular involves taking code from Jupyter notebooks and organizing it into separate Python scripts, each responsible for different aspects of the functionality. 

For example:   
data_setup.py: Prepares and downloads data.   
engine.py: Contains training functions.   
model_builder.py: Creates PyTorch models.   
train.py: Trains a PyTorch model using the other scripts.   
utils.py: Provides utility functions.

Lab №6

There were no exercises in assignment 6, so this file will not be in the repo since it was done in class

Lab №8

At the end of the laboratory, regularization methods are presented that can be considered in more detail.