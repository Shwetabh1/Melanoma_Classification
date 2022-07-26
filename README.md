# Project Name
> MELANOMA Classification


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Conclusions
- Accuracy increased considerably after class rebalancing. We built a neural network model that has three reLU units and the final layer which is a dense layer that has softmax activation for predicting multi-class probability output. We use a dropout of 0.5 in between for regularization. We have also used the categorical cross-entropy as our loss function with the Adam optimizer.



## Technologies Used
- tensorflow
- Augmentor
- matplotlib
- numpy
- pandas

## Acknowledgements
Following Tutorials were helpful.
- https://www.kaggle.com/code/wanderdust/melanoma-detection/notebook
- https://github.com/laurakoco/melanoma-detection-ml/blob/master/src/train_keras_cnn.py
- https://www.kaggle.com/code/anindya2906/fashion-mnist-classification/notebook
- https://www.kaggle.com/code/keypos/resnet50-melanoma-classification


## Contact
Created by [@shwetabh1] - feel free to contact me!
