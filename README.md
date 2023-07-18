# Melanoma-Detection
* This repository contains code for CNN on Melanoma Cancer Detection .
* To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements
# Problem Statement:
In this assignment, you will build a multiclass classification model using a custom convolutional neural network in tensorflow.

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
NOTE: You don't have to use any pre-trained model using Transfer learning. All the model building process should be based on a custom model.

Project Pipeline
Data Reading/Data Understanding → Defining the path for train and test images
Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset
Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
Write your findings after the model fit, see if there is evidence of model overfit or underfit
Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: **
Examine the current class distribution in the training dataset
Which class has the least number of samples?
Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:
Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~30 epochs
Write your findings after the model fit, see if the issues are resolved or not?
# Technologies Used: 
* python - 3.11.2
* tensorflow - 2.13.0
* Jupyter  -  6.4.12
# Conclusion:
* To train the model we should have more data. Initially we are having class imbalance in the data. 
* We have used Augmentor to classify them equally.
* Overall the training accuracy and validation accuracy is almost same.
# Acknowledgements
This project was inspired to reduce the cancer in the world by detecting it in the early stages.
## Contact
Created by [@Shashi-Vadla] - feel free to contact me!
