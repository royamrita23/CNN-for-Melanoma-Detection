# CNN-for-Melanoma-Detection
Multiclass Classification Model using CNN for Melanoma Detection

## Submitted By:
	* Saurav Kumar Sinha
	* Dhananjaya Dutt Mishra
	* Amrita Roy

## Table of Contents
	* Objective
	* Problem Statement
	* Methodology
	* Conclusions

## Objective: 

To create a multiclass classification model using a custom convolutional neural network in tensorflow

## Problem statement: 

To address the critical task of accurately identifying melanoma, a potentially life-threatening form of cancer, a CNN-based model is being developed. 	Melanoma accounts for 75% of skin cancer-related deaths, emphasizing the urgent need for early detection. By employing this solution, which can analyze images and promptly alert dermatologists about the presence of melanoma, a significant reduction in the manual effort required for diagnosis can be achieved.

The dataset utilized for this project comprises 2,357 images of both malignant and benign oncological conditions. These images were obtained from the International Skin Imaging Collaboration (ISIC) and organized based on ISIC's classification system. The subsets of images were divided uniformly, except for melanomas and moles, which exhibit a slightly higher proportion of images.The data set contains the following diseases:

      1) Actinic keratosis
      2) Basal cell carcinoma
      3) Dermatofibroma
      4) Melanoma
      5) Nevus
      6) Pigmented benign keratosis
      7) Seborrheic keratosis
      8) Squamous cell carcinoma
      9) Vascular lesion

## Methodology

	1) Data Reading/Data Understanding
	2) Dataset Creation
	3) Dataset visualisation
	4) Model Building & training
	5) Model Building & training on the augmented data
	6) Class distribution
	7) Handling class imbalances
	8) Model Building & training on the rectified class imbalance data
	9) Selection of appropriate optimiser and loss function for model training
	
## Input Path Link:
	
https://drive.google.com/drive/folders/1VkjDobUyza06b8MWfPHXcelDOx9-TLxC?usp=sharing 

## Conclusions

	1) The training and validation accuracy is in range of 63-65%.
	2) The overfitting issue has been resolved as the training and validation accuracy are in similar ranges.
	3) The data augmentation technique helped to overcome overfitting and further class rebalance helped in improving accuracies.
	4) There are further scopes of improvement in model by adding more layers, more images in the augmentation step (instead of 500 images in each class) and more epochs.


## Contact

1) https://github.com/Saurav-Sinha-2022 - feel free to contact me!
2) https://github.com/DDMX2022 - feel free to contact me!
3) https://github.com/royamrita23 - feel free to contact me!
