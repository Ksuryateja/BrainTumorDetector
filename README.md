# BrainTumorDetector
Building a detection model using a convolutional neural network in Keras.

# About the data:
The dataset contains 2 folders: yes and no which contains 253 Brain MRI Images. 

The folder yes contains 155 Brain MRI Images that are tumorous and the folder no contains 98 Brain MRI Images that are non-tumorous.

Since the dataset is small I have used an augmented version of the dataset available at https://github.com/MohamedAliHabib/Brain-Tumor-Detection

After data augmentation, now the dataset consists of:
1085 positive and 980 examples, resulting in 2065 example images.

# Note: 
these 2065 examples contains also the 253 original images. They are found in folder named 'augmented data'.

# Architecture

