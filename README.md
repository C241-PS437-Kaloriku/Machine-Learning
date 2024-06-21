# Project Overview
This repository contains two machine learning models designed for nutritional analysis and food classification. The first model predicts caloric content based on food attributes like protein, fat, and carbohydrate levels. The second utilizes a convolutional neural network (CNN) to classify food images into predefined categories.

## Features
* Nutrition Prediction: Estimate calorie content from basic nutritional data.
* Image Classification: Classify images into categories like fruits, vegetables, and dishes using MobileNetV2.
* Data Preprocessing: Includes scaling and cleaning of data to prepare for modeling.
* Model Evaluation: Utilize various metrics to assess the accuracy and performance of the models

## Data
The data used in this project is stored in Google Drive:

* nutrition.csv for nutritional analysis.
* TFRecord files for food image classification.
Ensure you have the correct paths set up in your scripts to access this data.

## Models
*Nutrition Prediction Model
Built using TensorFlow, this model predicts calorie content based on the macronutrient composition of food items.

*Food Image Classifier
Leverages TensorFlow and MobileNetV2 for efficient image classification. It is trained on a diverse dataset of food images to recognize various food categories.

## Results
The nutrition prediction model achieves a mean squared error of X on the test data. The food classification model reaches an accuracy of Y% on the validation set.

## Acknowledgments
Food-101 dataset for providing a rich dataset for image classification.
TensorFlow and Keras libraries for their powerful machine learning tools.
