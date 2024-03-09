# Project Name
> Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
<li>This dataset has 2357 images of skin cancer types.</li>
<li>The dataset contains 9 sub-directories in each train and test subdirectories.</li>
<li>The 9 sub-directories contains the images of 9 skin cancer types respectively.</li>

#### Here are the findings after the model fit experiment 1: 
<li>Model is overfitting as there is a discernible gap in the loss functions between the training and test sets, particularly noticeable after the 8th epoch.</li>
<li>Model accuracy is around 90%, indicating that the model might be grappling with an abundance of features, attempting to memorize patterns rather than generalizing effectively.</li>

#### Here are the findings after the model fit experiment 2:
<li>There is no improvement in accuracy but overfitting problem has solved due to data augmentation.</li>
<li>Increasing the epochs may increase the accuracy</li>

#### Other finding related to dataset:
<li>Seborrheic keratosis class has the least number of samples</li>
<li>Pigmented benign keratosis classes dominate the data in terms proportionate number of samples</li>
<li>Since few classes have very less sample so added more samples</li>

#### Drawing Conclusions and Analyzing Results
<li>Accuracy on training data has increased by using Augmentor library</li>
<li>Model is still overfitting</li>
<li>Problem of overfitting can be solved by adding more layer, neurons or adding dropout layers</li>
<li>Model can be further improved by tuning the hyperparameter</li>
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
<li>numpy - version 1.24.3</li>
<li>pandas - version 1.5.3</li>
<li>matplotlib - version 3.7.1</li>
<li>sklearn - version 0.13.5</li>
<li>tensorflow - version 2</li>
<li>Augmentor - version 0.2.12</li>

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
<p>"I want to express our heartfelt gratitude to the teachers and peers at Upgrad/IIITB for their consistently clear and informative sessions, as well as for patiently addressing our queries every day. I also extend my appreciation to the entire Upgrad team for providing us with this incredible learning platform."</p>


## Contact
Created by [Narendra Jha]
