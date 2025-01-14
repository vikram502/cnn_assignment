# Melanoma Detection CNN Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Information

> Build a multiclass classification model using a custom convolutional neural network in TensorFlow

### Project Statement

> To build a CNN based model which can accurately detect melanoma. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual e!ort needed in diagnosis.

### Dataset

> The [dataset](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing) consists of 2357 images of malignant and benign oncological diseases which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The augmentation of images degraded the accuracy of the model.
- Augmentor library's images helped reduce the class imbalance and improved the model efficiency.
- BatchNormalization layer degraded the accuracy so had to use LayerNormalization.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraries Used
- pathlib
- tensorflow
- matplotlib.pyplot
- numpy
- pandas
- PIL (Python image Library)
- tensorflow.keras
- google.colab
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
The Assignment is developed as part of the Convolutional Neural Networks Module required for Post Graduate Programme in Machine Learning & AI - upGrad and IIIT, Bengaluru

## Contact
[Aditya Vikram Tata](https://github.com/vikram502)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->