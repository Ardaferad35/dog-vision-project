# dog-vision-project
=======

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)

## 1. Project Overview
This project aims to classify dog breeds using a deep learning model built with TensorFlow. The goal is to create an accurate and efficient system for recognizing different dog breeds from images.
The dataset contains various breeds with varying image counts, so models are evaluated with a focus on accuracy to ensure robust performance.

## 2. Data Preprocessing

In the data preprocessing stage, all images were resized to a shape of 224×224×3 to ensure consistency for the deep learning model. 
The dataset was then divided into batches of 32 images each to optimize memory usage and training efficiency.The dataset was split into 80% training and 20% validation sets to evaluate the 
model’s performance effectively and prevent overfitting.
