# Melanoma Detection using a custom CNN in TensorFlow
> To build a multiclass classification model using a custom convolutional neural network in TensorFlow which can which can accurately detect the presence of melanoma


## Table of Contents
* [Project Info](#project-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Project Information

### 1. Business Problem Statement

Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

We will to try to build a multiclass classification model using a custom convolutional neural network in TensorFlow which can detect the presence of melanoma accurately.

### 2. Dataset

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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

## Technologies Used
- pathlib - 3.10.12v
- tensorflow - 2.14.0v
- matplotlib.pyplot - 3.7.1v
- numpy - 1.23.5v
- pandas - 1.5.3v
- PIL - 9.4.0v
- keras - 2.14.0v
- Augmentor - 0.2.12v
- sklearn - 1.2.2v
- python - 3.10.12v

## Conclusions
We created a custom CNN based model with decent accuracy to detect melanoma and formed the below conclusions

1. We have created 3 models and have seen improvement from first model to 3rd model by adding data agumentation & handling class imbalances.
2. We attained the 3rd model with 92.6% accuracy on train dataset and 83.7% accuracy on validation dataset.
3. With the right hyper-parameter tuning, accuracy can still be improved even more. We can experiment with different CNN configurations, regularisation techniques, loss functions, optimizers, and layer/epoch counts to see accuracy pattern.

## Acknowledgements

- I would like to thank [G. Srinivasaraghavan](https://in.linkedin.com/in/gopalakrishnan-srinivasaraghavan-43b4b9) for his explanation on CNN.
- References for data argumentation are taken form [Towards Datascience](https://towardsdatascience.com/class-imbalance-random-sampling-and-data-augmentation-with-imbalanced-learn-63f3a92ef04a?gi=8f2b3fdb24c1)
- References for regularizations techniques are taken from [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2018/04/fundamentals-deep-learning-regularization-techniques/)).
