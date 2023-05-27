# Garbage-Classifying-Application
Developed an android application integrated with deep learning models (VGG-16, Resnet50, Simple CNN) to classify roadside images into garbage and non-garbage and automatically send the location of mobile to Firebase if the image classified as garbage.

The garbage classification process is automated by building an image classifier using a convolutional neural network (CNN) and thereby decrease the time for the waste segregation and make it cost-effective. The idea behind making the process automated is to decrease human intervention and make this waste segregation process more productive. In this work, three different models are being tested for higher accuracy: Simple CNN, ResNet50, and VGG16 trained on various datasets of images, these are used to extract features from images and feed them into a classifier for dump/trash classification. The trained models are then fed to a mobile application that captures pictures in the real-time using camera. The experimental results conclude the performance of VGG16 using Transfer Learning being significantly higher than all other models for the purpose of Trash Classification and the performance of Simple CNN being better for Dump Classification.
Achieved an accuracy of around 96%.

Link to the application: https://drive.google.com/file/d/1MIlbjWO1NbkrJjNxINGNyrAWDgvCOm5D/view?usp=sharing (Request Access)
Dataset Link: https://github.com/spotgarbage/spotgarbage-GINI
Link to the research paper: https://ieeexplore.ieee.org/document/9573599
