# CNN for Melanoma Detection
> This project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- We will try to develop a CNN model that can evaluate images and alert dermatologists about the presence of melanoma. This has the potential to reduce a lot of manual effort needed in diagnosis.
- This project is undertaken as an assessment as part of the AI & ML certification I am undergoing through IIIT, Bengaluru.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images are sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 1) Importance of sample diversity: 
As proven in this exercise it is of utmost importance that the model receives enough data, with enough variations, and uniform distribution across all classes in order to train itself to high accuracy. Tuning strategies like dropouts and Batch Normalization can only improve the accuracy to a certain extent if the data the model has to work with is limited and skewed.
- 2) Plan your runs optimally:
Running multiple epochs is computationally expensive and time consuming. In an ideal world, we would be using high-end infrastructure like GPUs and TPUs to train our models, but, as we know, these are very expensive. Remember, syntax errors and run-time errors also cost computational units. Therefore, it is imperative that we run through our code with a fine comb, perform every possible syntax check and also ensure that the code is as we want it to be, by running it locally, before we run it on a GPU or a TPU.
- 3) How many epochs to run:
At first sight it may seem obvious that the more the epochs, the better the model accuracy. This is not necessarily true because after a certain number of epochs, the model might reach it's optimum accuracy and beyond that the accuracy might even reduce. And then there is the fact of computational costs, i.e., more epochs = more cost. Fortunately, we can capture the run-time statistics of every epoch, and we can clearly see at which epoch the accuracy is highest, beyond which the accuracy dwindles. We can then finalize the number of epochs to that epoch number.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow - version 2.11.0
- Keras - version 2.11.0
- Pathlib - version 1.0.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- I would sincerely like to acknowledge the fantastic tutorials by Dr. Gopalakrishnan Srinivasaraghavan on the Upgrad platform that helped me gain a functional understanding of Neural Networks.

## Contact
Created by robotigvin - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->