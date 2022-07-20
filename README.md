# melanoma_detection
This Assignment is for Upgrad AI-ML - C36 Batch

In this assignment, you will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

 

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

 > Actinic keratosis
 > 
 > Basal cell carcinoma
 > 
 > Dermatofibroma
 > 
 > Melanoma
 > 
 > Nevus
 > 
 > Pigmented benign keratosis
 > 
 > Seborrheic keratosis
 > 
 > Squamous cell carcinoma
 > 
 > Vascular lesion

Challenges:
Its takes over 16 minutes to train even 20 Epochs
Its takes over 35 min to train 50 Epoch Thats too much of screen time, even with Google Colab


BOTTOMLINE/OBSERVATIONS:
a.The fixing of class imbalance helped in reducing overfititng of the data and thus the reducing loss.
b. Accuracy is reduced to low < 12%
c.Initially using the ImageDataGenerator , it created data to over fit at high ratio.
d.Introduction of dropout and ImageDataGenerator has reduced the over fit
e.In the End we tried, Batch Normalization and Augumentation which really helped in carry forward.



# This was an enjoyable and challenging Assignement, Shasheesh Rane(Myself) have tried to include all we could and follow the Rubric as described by Upgrad. In terms of :

> - Data Reading Data Understanding
> - Dataset creation
> - Dataset visualisation
> - Model Building  training
> - Data augmentation
> - Class distribution
> - Model Building  training  After Augmentor
> - Coding Guidelines

####  Our best sincere efforts were put in this assignment.


#### Thanking you,

# SHASHEESH RANE (Group Facilitator)
