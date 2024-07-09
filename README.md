# Melanoma detection
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma.
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Without using augmentation, There is clearly a huge difference between training and validation accuracy. This indicates that the model is clearly an overfit model. Also the Validation loss is not recovering even with the increasing number of epochs but the training loss is decreasing. This is another indication of overfitting.
- Post Data Augmentation, the training accuracy and validation accuracy is close and thus we can infer that the model is a fairly good fit. We could probably use Batch Normalization with dropouts at each layer to get a better fit.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- matplotlib
- tensorFlow
- Keras
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@goyalanshul1303] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->