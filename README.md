# Project Name
> Melanoma Detection through CNN.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Contact](#Contact)

## General Information

Problem statement: 
To build a CNN based model which can accurately detect melanoma. 
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of 
manual effort needed in diagnosis.

Create a multiclass classification model using a custom convolutional neural network in tensorflow for Melanoma detection.

## Conclusions
- 
1) Initial model is overfitting. 
Training Accuracy:  0.8018973469734192, Validation Accuracy:  0.563758373260498
Loss:  0.5264095067977905, Validation Loss 1.7899751663208008

2) Data is heavily imbalance and hence due to that results and predictions will be baised.

3) After rebalance/resampling of the data (that gave equal proportion of data )and raised the accuray of the mdoel to 90%. 
This addressed the low accuracy problem.overfitting probelm is adressed and now difference between train and val set is nearly 4-5%.
with these results it's conclusive that current module with rebalanced data is the best module.

## Contact
Created by @sang2012 - feel free to contact me!

