# Land-Use-Classification using the UC Merced Dataset

## Description

This project shows how to classify Land Use images using various Image processing and Deep Learning methods. The UC Merced Dataset was used for this purpose. This project was done using Python3.7, Tensorflow as backend and using Keras as the high level library. The dataset contains of 2100 images with 100 in each of the 21 classes. A train/test split of 80%/20% was made (i.e. 1680 training images and 420 testing images). Each image is of the dimension 256 x 256 pixels. This being a research project, several models were created using various Image Processing techniques.

## Different Methods applied:

Several different methods were applied to create different models for the classification purpose. Five models that were created are:  

<b> 1. CNN model on RGB images </b>

<b> 2. CNN model on DCTs of RGB images </b>

<b> 3. Model ensemble with RGB images and their LBPs </b>

<b> 4. Model ensemble with RGB images and their DCTs </b>

<b> 5. N-ary conversion of DCTs of RGB images </b>

A Convolutional Neural Network (CNN) model was created from scratch on RGB channels of the images. This model
