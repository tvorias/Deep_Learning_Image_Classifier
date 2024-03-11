# Deep_Learning_Image_Classifier

## SI 670 (Applied Machine Learning) - Kaggle Competition
This notebook is the cleaned version of the code used to create a deep learning image classifier for a Kaggle competition. The objective of the competition was to create a model that can accurately classify sinks as being either kitchen sinks or bathroom sinks. The train and test set is a collection of images of kitchen and bathroom sinks. 

This submission placed 4th out of 20 teams and accurately predicts 143/149 of the images in the test set (96% accuracy). 

## Set Up
### Dependencies 
- `Python3.11`
[Installation information can be found here (https://www.python.org/downloads/release/python-3112/)

### Installations
`pip install tensorflow`

### Getting started
The file routes to a directory called `images_train`. Once all files are downloaded, move `bathroom` and `kitchen` to a folder called "images_train"

Due to the size limitations, I removed a majority of the images from the train and test sets. The model may not be as robust because of this. As a result, the accuracy from the original train/test sets may not be reproducible. 

*Disclaimer:* I do not own the data. 
