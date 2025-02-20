# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma.Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
### Project Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

### Project Background
Melanoma is a severe type of skin cancer that originates in melanocytes, the cells responsible for producing pigment in the skin. The goal is to develop a CNN architecture to classify images as melanoma or not.


### Business problem
To detect Melanoma skin cancer disease based on the Images provided.


### Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
- Model1 was trained on 20 epochs with batch_size as 32. This model is overfitting with training accuracy as 0.81 and validation accuracy as 0.43.While the training loss is clearly decreasing, but the validation loss is fluctuating a lot.
- Model2 was trained on 20 epochs with batch_size as 32 and an additionally used data Augumentation. This model is underfitting with training accuracy as 0.53 and validation accuracy as 0.29. While the training loss is clearly decreasing, but the validation loss is fluctuating a lot.
- Model3 was trained on 30 epochs with batch_size as 32 and used Augmentor library. After adding the additional images using Augmentor library, now we can get rid of underfitting/overfitting. The class rebalance helped in achieving this outcome. The training accuracy is 0.93 and validation accuracy is 0.86, with the consistent decrease in loss for both training and validation.

## Technologies Used
- TensorFlow - version 2.18.0
- MatplotLib - version 3.9.1
- numpy - version 1.26.4
- pandas - version 2.1.4
- Augmentor - version 0.2.12

## Acknowledgements
This project was inspired by UpGrad IIITB Programme as a case study for the Artificial Intelligence Machine Learning course.


## Contact
Created by [@sravanthichundi] - feel free to contact me!
