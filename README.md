# Melanoma Detection Assignment
> The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Table of Contents
* [Problem statement](#Problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- After adding batch normalization and resampling using augumentor library has improved the model accuracy to great extent. By doing some experiment i could by increasing dropout value the model vaidation performance was stable it could be due the model starts to overfit due to more epoch and the addition of dropouts reduced the overfitting.

The class rebalance also improved the model performance greatly.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python version: 3.10.12
- TensorFlow version: 2.12.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by SIVASKANDAN.P - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
