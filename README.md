# Brainstation

## Description of Project

The purpose of this project is to identify an underlying pattern that exists in the dataset (pneumonia pattern that exists in the chest X-ray images) through model based learning 

I wanted to make a diagnostic tool that could effectively detect and classify pneumonia from chest X-ray imaging in patients and accurately distinguishes bacterial and viral pneumonia

## Design 

My approach to solving this problem was to use a convolutional neural network (CNN). This program takes in X-ray images from a dataset and uses a CNN to determine whether the patient has pneumonia or not. The reason I chose to use a convolutional neural network in this program is because CNNs were actually designed for image data and are very good with image classification. CNNs learn the various features of an image and can detect features in various positions in the image which makes them very effective in image classification and is why I chose to use them for this specific project. 

## Breakdown of Model 

There are 4 Conv2d Layers each with 32 output filters and a kernel size of 5 x 5 and each one uses the relu activation function   

There are 4 max_pooling layers with a pooling window size of 2x2 

There is one flatten layer to bring all the levels down to one plain 

3 Dense layers each with a different activation function and a different output size. 

## Summary of Evaluation 

On average the model will acheive a testing accuracy of around 80%


