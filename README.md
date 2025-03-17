# Real-Time-Emotion-Detection
# Introduction 
This project aims to classify emotions on a person's face into one of seven categories using deep convolutional neural networks (CNNs). The model is trained on the FER-2013 dataset, which was introduced at the International Conference on Machine Learning (ICML). The dataset consists of 35,887 grayscale images (48x48 pixels), categorized into seven emotions:
😠 Angry | 🤢 Disgusted | 😨 Fearful | 😃 Happy | 😐 Neutral | 😢 Sad | 😲 Surprised


# Data Preparation 
The original FER-2013 dataset is available as a CSV file on Kaggle. For convenience, it has been converted into PNG images for training/testing. The preprocessing code is available in dataset_prepare.py.


# Algorithm Overview
1.Face Detection: Uses Haar Cascade to detect faces in each frame.
2.Preprocessing: The detected face is resized to 48x48 pixels.
3.Model Prediction: The CNN outputs softmax scores for the seven emotion classes.
4.Display: The emotion with the highest probability is displayed on the screen.


# References
"Challenges in Representation Learning: A report on three machine learning contests." - I. Goodfellow et al., 2013


