# Tomato Leaf Disease Classification

## Introduction
This project aims to develop a deep learning-based system for classifying tomato leaf diseases. It seeks to assist farmers and agricultural scientists by providing an automated and precise diagnosis of various leaf diseases, which are major contributors to economic losses in tomato farming due to their impact on crop yield and quality.

## Project Objectives
- **To implement and compare multiple convolutional neural network (CNN) architectures** for classifying tomato leaf diseases using three distinct datasets.
- **To evaluate the effectiveness of traditional training, transfer learning, and hyperparameter tuning** in improving the models' accuracy and performance.

## Datasets
Three datasets were utilized, each contributing to the diversity of training scenarios:
1. **[Dataset 1](https://www.kaggle.com/datasets/joseenriquelopez/tomato-leaf-diseases)**: Consists of six classes with a total of 2000 images, from which three evenly distributed classes were extracted.
2. **[Dataset 2](https://www.kaggle.com/datasets/cookiefinder/tomato-disease-multiple-sources)**: Contains 11 classes totaling 14,658 images, with 6 relevant classes extracted.
3. **[Dataset 3](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)**: From a larger dataset covering multiple leaf diseases, 10 classes comprising 18,000 images were selected.

## Models and Training
Three CNN architectures were explored:
- **ResNet18**
- **MobileNetv2**
- **VGG16**

A total of twelve models were trained:
- **Nine models from scratch**: Three models per dataset using each of the CNN architectures.
- **Two models with transfer learning**.
- **One model using hyperparameter tuning** to enhance performance.

## Challenges
The main challenges encountered include:
1. **Variability in light exposure and background noise** in images which could potentially hinder model accuracy.
2. **Inconsistent image quality** within datasets which affects the model training and validation phases.

## Methodology
- Models were trained and validated using the above datasets with adjustments for class balance and image quality.
- The performance of each model was evaluated, and the results were visualized using Grad-CAM techniques to understand model decision-making processes.

## Requirements
- Python 3.8+
- Pytorch
- Other dependencies are listed in the `requirements.txt` file.

## Installation and Usage
Steps to Run the Program

1. Import the file in Google Colab and Open it.
2. Import the datasets given into the content folder in Google Colab.
3. Run all the cells of the program.
4. Check the desired output.
