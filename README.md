# Project Dog Breed Classifier Overview
In this project we will train a convolutional neural network (CNN) on different dog breed
images, and then on passing a picture of dog, it will be able to predict the class of breed.
And if human picture is given to our CNN model, it will identify it as human but also it
will try to match a similar dog breed that closely matches the picture provided.
The datasets of this project is provided by udacity

# Datasets
Download dog dataset at [Dog Dataset Download](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)

Download human faces dataset at [Human Faces Dataset Download](http://vis-www.cs.umass.edu/lfw/lfw.tgz)

# Set up instructions

1. Download project files

```
	git clone https://github.com/zainullahdev/dog-breed-classifier.git
	cd dog-breed-classifier
```

2. Download datasets, extract and place in the project folder
3. run notebook using this command
```
	jupyter notebook dog_app.ipynb
```



Optimizer: SGD

Pre-Trained Model: Resnet50


Download Custom Trained Model (without transfer learning): [Here](https://drive.google.com/file/d/1XJpmldzxs3F5yHU1JMWlPo6bGS6cvTde/view?usp=sharing)

Test Accuracy: 11%

Download Custom Trained Model (with transfer learning): [Here](https://drive.google.com/file/d/12EK9OGBIPrHKDCKrXZDiMbMDyXbcohmC/view?usp=sharing)

Test Accuracy: 77%

# Test Results

Dog Image
 
![alt text](https://raw.githubusercontent.com/zainullahdev/dog-breed-classifier/master/test_results/dog-image.png "Dog Image")


Human Image
 
![alt text](https://raw.githubusercontent.com/zainullahdev/dog-breed-classifier/master/test_results/human-image.png "Human Image")

# Important

1. This project requires GPU to run
2. datasets solely belong to Udacity



