<div align="center">

  ![Image_Classifier](https://github.com/user-attachments/assets/4d36abb4-c14a-4fd9-9350-d3a7a1a89072)

   ![GitHub repo size](https://img.shields.io/github/repo-size/BaraSedih11/image_classifier) ![GitHub repo file count (file type)](https://img.shields.io/github/directory-file-count/BaraSedih11/image_classifier) [![Python Version](https://img.shields.io/badge/python-3.8-blue)](https://www.python.org/downloads/release/python-380/)
[![Pip Version](https://img.shields.io/badge/pip-21.0-orange)](https://pypi.org/project/pip/21.0/)
 ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/BaraSedih11/image_classifier/main)
[![Version](https://img.shields.io/badge/version-v1.0.0-blue)](https://github.com/BaraSedih11/image_classifier/releases/tag/v1.0.0)
[![Contributors](https://img.shields.io/github/contributors/BaraSedih11/image_classifier)](https://github.com/BaraSedih11/image_classifier/graphs/contributors)
![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/BaraSedih11/image_classifier)
</div>


This project demonstrates the implementation of an image classification model using **TensorFlow**. It utilizes **transfer learning** with a pre-trained **MobileNet** model to classify images into multiple categories, showcasing the power of modern machine learning techniques.

## Project Overview
- **Dataset**: The model is trained on the **Oxford Flowers 102** dataset.
- **Model**: Transfer learning with MobileNet for feature extraction.
- **Application**: A command-line tool for image classification.

## Features
- Data preprocessing pipelines for resizing and normalizing images.
- Transfer learning for efficient model training.
- Command-line application for inference, including top-K predictions and class mapping.

## Technologies Used
- **Python**
- **TensorFlow** and **TensorFlow Hub**
- **Matplotlib** for data visualization

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/BaraSedih11/image_classifier.git
   ```
2. Install the required libraries:
  ```bash
  pip install -r requirements.txt
  ```
3. Train the model:
  ```bash
  python train.py
  ```
4. Use the trained model to classify images:
  ```bash
  python predict.py --image_path <path_to_image> --model_path <path_to_model>
  ```

## Results
* Achieved high accuracy in classifying flower species using transfer learning.
* Provided a flexible and easy-to-use tool for image classification tasks.
