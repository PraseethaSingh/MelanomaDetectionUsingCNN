# Melanoma Detection using custom CNN
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
  * [Algorithm Used](#Algorihm-used)
  * [Dataset Used](#Dataset-used)
  * [Steps Involved](#Steps-involved )

* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
# Algorithm Used
  CNN Algorithm is used
 # Dataset Used
  The dataset consists of 2239 images of malignant and benign skin cancer cases, collected by ISIC The International Skin Imaging Collaboration. All images were sorted according to the classification done for 9 classes by ISIC, and all subsets were divided into different subfolders.
The different classes are -
  Actinic Keratosis
  Basal Cell carcinoma
  Dermatofibroma
  Melanoms
  Nevus
  Pigmented Benign Keratosis
  Seborrheic Keratosis
  Squamous Cell Carcinoma
  Vascular lesion
 # Steps Involved     
   - Data loading for training and validation data
   - Building Baseline Model , Compiling the model, Training the model, Evaluating the model
   - Building model with augmented images, Compiing, Training and evalauting
   - Building model with augmentation library to handle class imbalance, Compiling, Training and Evaluating model
   - Evaluation of model on test data 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The final model is with augmented images , handling class imabalance and reducing overfitting.
- Accuracy of model is 90%    

## Technologies Used
- Numpy library - version 1.26.4
- tensorflow library - version 2.17.1
- keras library - version 3.5.0



## Acknowledgements
- This project was a part of course work on ML


## Contact
Created by @PraseethaSingh - feel free to contact me! praseetha.singh@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
