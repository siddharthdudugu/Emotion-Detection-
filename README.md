# Object-Gender-Detection

1) Problem Statement:

Human emotion recognition plays a vital role in the interpersonal relationship. The automatic identification of emotions has been an active research topic since the early eras. Emotions are reflected from speech, hand, and gestures of the body and through facial expressions. As a human, I am sure; for most of you, it must be an easy task to judge a person by his emotion and communicate with them. But what if you want the machine to talk similarly by analyzing the feeling. Just as a human extracting and understanding the emotions, it is equally essential for the machine to understand the sentiment and then interact/respond to the human. So as part of this project, let us try to resolve one of the issues and predict the emotion of a person using his facial features in real-time.

2) Tasks to be Performed:

In this tutorial I will be performing the following tasks:
Recognize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral)
Import Required Libraries
Prepare the dataset for the model
Develop CNN model for recognizing facial expression of the images
Analyse the model summary
Fit the basic CNN model
Save the model & load the saved weight to test the model
Predict the facial expression of the uploaded image
Use OpenCV and Haar Cascade File to check the emotion in real time
##Dataset Description

3) FER Dataset:

fer2013 is an open-source dataset, first created for an ongoing project by Pierre-Luc Carrier and Aaron Courville, then shared publicly for a Kaggle competition, shortly before ICML 2013. This dataset consists of 35,887 grayscale, 48x48 sized face images with 7 different emotions, all labelled.
Fer.csv contains two columns, emotion and pixels.

The emotion column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image.

The pixels column contains a string surrounded in quotes for each image

Classes: 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral

alt text

4) Skills Gained:

TensorFlow 2.x
Convolutional Neural Network (CNN) implementation
Load the pretrained model
OpenCV
