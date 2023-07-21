# Brain Tumour Detection and classfication using Transfer Learning:
ABSTRACT: One of the most leading death causes in the world is brain tumor. Solving brain tumor segmentation and classification by relying mainly on classical medical image processing is a complex and challenging task. In fact, medical evidence shows that manual classification with human-assisted support can lead to improper prediction and diagnosis. This is mainly due to the variety and the similarity of tumors and normal tissues. Recently, deep learning techniques showed promising results towards improving accuracy of detection and classification of brain tumor from magnetic resonance imaging (MRI). In this paper, we propose a deep learning model for the classification of brain tumors from MRI images using convolutional neural network (CNN) based on transfer learning. The implemented system explores a number of CNN architectures, namely ResNet50, VGG19. This latter achieved the best results with 97.80 % accuracy and 0.07% loss..

# Installation:
Anaconda 2021
Required Libaries: numpy==1.20.3 matplotlib==3.4.3 tensorflow==2.8.0 keras==2.8.0 

# Data Collection:
Dataset link : https://drive.google.com/drive/folders/1oD51hXMXcESxp4doEKB-TwDPY6Sxoep5?usp=drive_link

# Project Descriptions:
   No.of sample Images collected with classes: Cerebrovascular disease:500
                                               Normal Brain:500
                                               Degenerative Disease:500
                                               Inflammatory Disease:500
                                               Neoplastic Disease:500

# Model Training:
In this Model I have compared used Transfer Learning Method (CNN;VGG19;ResNet50) : With Sample Images I have trained the Images with Batch_size=8 Epochs=100 and attained better Training accuracy is 97% and Losses is 0.07% and Tested with same Epochs attained Testing Accuracy is 97.8% and Lossess is 0.07%...