# Face-Recognition-and-Emotion-Detection

## Introduction
Facial emotion recognition is the process of detecting human emotions from facial expressions. The human brain recognizes emotions automatically, and software has now been developed that can recognize emotions as well. This technology is becoming more accurate all the time, and will eventually be able to read emotions as well as our brains do.

## Problem Statement
Digital classrooms are conducted via video telephony software program (ex: Zoom) where it’s not possible for medium scale class (25-50) to see all students and access the mood. Because of this drawback, students are not focusing on content due to lack of surveillance. 

We will solve the above-mentioned challenge by applying deep learning algorithms to live video data. The solution to this problem is by recognizing facial emotions.

## Dataset Information
The images for the project is obtained from https://www.kaggle.com/datasets/msambare/fer2013. The dataset consists of 35887 grayscale, 48x48 sized face images with seven emotions - angry, disgusted, fearful, happy, neutral, sad and surprised. The whole dataset is divided into train set and test set with 28779 images on train set and 7188 images on test set.

## Dependencies
Tensorflow

Opencv

Streamlit

Streamlit-webrtc

## CNN Modelling
A convolutional neural network is used to detect and classify objects in an image. In CNN-based approaches, the input image is convolved through a filter collection in the convolution layers to produce a feature map. Each feature map is then combined to fully connected networks, and the face expression is recognized as belonging to a particular class-based the output of the softmax algorithm. 

## Steps for running in local computer
**STEP-1**: Install all the dependencies mentioned in requirements.txt file. You can run the following command in your command prompt to install all the dependencies:
```python
pip install -r requirements.txt
```

**STEP-2:** After installing all the dependencies, open command prompt from the direction where app.py file is present and run the following command:

```python
python app.py
```
That's it, you can see the web application running at you localhost.

## Live Video of Face Emotion Recognition
https://user-images.githubusercontent.com/96906297/160372044-eb31ed58-fcef-4f97-9c43-d4a272cee201.mp4

