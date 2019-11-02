# BayMax: An AI Healthcare Companion 
## A Winner of TensorFlow #PoweredByTF2.0 Challenge: [Submission here](https://devpost.com/software/baymax-ohef01)
## Overview
Diagnosing diseases automatically has been an immense challenge, owing to their variable properties and symptoms. On the other hand, Neural Networks (NNs) have developed into a powerful tool in the field of machine learning, one that is showing to be promising at computing diagnosis even with inconsistent variables. 

I developed a low-cost device for straightforward analysis and treatment of human diseases. By utilizing NNs, the device can detect diseases and conditions, automatically, using end-to-end deep learning. It does so with an extremely high accuracy rate, relative to trained doctors. The Deep NN (DNN) algorithm can identify various diseases, along with providing treatment advice. Biometric values such as oxygen saturation and electrocardiogram (ECG) values are calculated using a Recurrent NN (RNN), developed to detect anomalies: myocardial arrhythmias and ischemias. A Convolutional NN is on the device to identify and segment dermatological lesions. These algorithms run on a Raspberry Pi processor. This device can augment doctors by speeding up the time needed for diagnosis by pre-analyzing the user and providing estimated conditions. This scalable method of detecting anomalies before they pose a threat, holds the ability to create clinical impact around the world by profoundly increasing access and scope of medical care. 

Overall, this device will help alert physicians to high-risk patients, while making the doctors' analysis much more efficient and accurate; therefore, saving people, while decreasing costs and time.

## Inspiration

More than 400 million people do not have access to essential health services. I personally have seen the struggles people in less fortunate areas have, as when I visit family in India, I regularly see many people suffering from treatable medical ailments, but many do not have the treatment knowledge.

## Objective

**Develop a device to automatically conduct medical analysis (dermatological, cardiovascular, and symptomatic) + develop corresponding algorithmic models that self-optimize their parameters, through TensorFlow 2.0.**

## Methods

HAM10000 was the database used to train the skin disease model. It contains 10,000 images of 26 different kinds of skin conditions. Dataset augmentation was only applied to the training set, as to conserve the quality of the images in the validation and testing groups.

PhysioNet’s and MIT-BIH’s databases on arrhythmias and myocardial ischemias were used to train the heart anomaly model. 

To house these NNs, and make them deployable, a cheap, Raspberry-Pi based device was constructed from scratch.

## Impact

In this project, a low-cost device was created that is able to diagnose diseases, offline: symptomatic, dermatological, and cardiovascular, with an accuracy rate that is comparable to modern doctors.

This tool will help augment doctors around the world, making their jobs easier by allowing for easy and convenient medical analysis within a home. By allowing scheduled analysis without the use of personnel, this device is capable of identifying medical anomalies before they occur, and alerting doctors. This scalable method of providing analysis comparable to medical personnel, and detecting anomalies before they pose a large threat, holds the ability to create clinical impact around the world by profoundly increasing access and scope of medical care.

# **Overall, this device will both alert physicians to high-risk patients, while making the doctors' analysis much more efficient; overall, saving people, while decreasing costs and time.**


