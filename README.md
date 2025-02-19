# Skin Cancer Classification Project
This project develops a deep learning-based model to classify types of skin cancer. Using a pre-trained MobileNet model, skin lesions are categorized into seven different classes.

## 📌 Project Objective
Skin cancer is a disease that can lead to serious consequences if not detected early. This project aims to automatically classify types of skin cancer using machine learning.

## 📊 Dataset Used: HAM10000
HAM10000 is a dataset containing 10,015 dermoscopic images of various skin diseases. The images are labeled according to the following seven different types of skin lesions:

## Technologies Used
Python (Data processing and model training)
TensorFlow / Keras (Deep learning model development)
MobileNet (Fine-tuning with a pre-trained model)
ImageDataGenerator (Data augmentation and preprocessing)
NumPy, Pandas (Data processing and analysis)
Matplotlib, Seaborn (Visualization of results)

## Model Architecture Summary

Using the MobileNet model, the following steps were performed:

The last 6 layers of the model were removed, and Flatten, Dropout, and Dense layers were added.
The model was classified into 7 classes using the Softmax activation function.
Adam optimizer and categorical_crossentropy loss function were used.
Pre-trained layers were frozen except for the last 23 layers.

## Training Process

Data Preprocessing: Images were resized and normalized.
Model Training: Fine-tuning was performed on the MobileNet model.
