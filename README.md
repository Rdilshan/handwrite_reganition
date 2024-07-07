# Handwritten Recognition System using IAM Dataset and TensorFlow

## Overview
This project implements a Handwritten Recognition System using the IAM Dataset and a Convolutional Neural Network (CNN) model, integrated into a TensorFlow-based Optical Character Recognition (OCR) system. The system aims to automate the recognition of handwritten text to enhance efficiency and accuracy in various applications.

## Problem Statement
Recognizing handwritten text accurately is a challenge in OCR systems. This project addresses this by leveraging deep learning techniques to improve recognition accuracy and handle various handwriting styles.

## Technology Stack
- **Dataset:** IAM Dataset, a collection of handwritten documents.
- **Model:** CNN architecture for learning spatial hierarchies in images.
- **Framework:** TensorFlow for deep learning and neural network capabilities.

## Key Features
- Achieved [mention accuracy rates or performance metrics].
- Capable of recognizing various handwriting styles and contexts.
- Integrated preprocessing techniques for noise reduction and enhanced readability.

## Challenges and Solutions
- Overcoming noise in handwritten text.
- Optimizing model performance through data augmentation and hyperparameter tuning.

## Demo
Explore the system in action:
- [![Screenshot 2024-07-07 132613](https://github.com/Rdilshan/handwrite_reganition/assets/93394383/e78c273b-78aa-4192-ac06-7a87c8aae86a)](https://randika123-handwriting.hf.space/)

## Impact and Applications
This system has potential applications in:
- Digitizing historical handwritten documents.
- Improving accessibility for the visually impaired.
- Automating data entry tasks across industries.

## Usage
### Prediction API
- Endpoint: `/prediction`
- Method: `POST`
- Input: Form data with image file (`upload` key)
- Purpose: Recognize individual words in handwritten text.

### Text Prediction API
- Endpoint: `/textpredict`
- Method: `POST`
- Input: Form data with image file (`upload` key)
- Purpose: Recognize sentences or phrases in handwritten text.


