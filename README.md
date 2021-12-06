# ml-model-cifar10-image-classification-

## Purpose
Classify the images present in the cifar10 data set given in the http://www.cs.toronto.edu/~kriz/cifar.html
_Input_: images and labels present in batch-wise pickle files .
_Output_: Valid classes:
1 : airplane
2 : automobile
3 : bird
4 : cat
5 : deer
6 : dog
7 : frog
8 : horse
9 : ship
10 : truck

# model 
Traind the Cifar10 data with resnet152 Network

# Current performance metrics

| Train accuracy| Test accuracy| Epochs|
| --- | --- |  --- |
| 82.4| 75| 20 |

# Model training
Download the data and keep the pickle files in data/cifar-10-batches-py/ 
Follow the steps provided in train/train.ipynb 

# Inferencing on image 

Load the check point as per steps provided in inference/inference.ipynb. 

