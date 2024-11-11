# Mathematical Expression Recognition (MER)

This project focuses on recognizing handwritten mathematical expressions using a deep learning-based system. The approach leverages a hybrid model combining Convolutional Neural Networks (CNNs) with Transformers to accurately interpret and convert handwritten mathematical symbols into machine-readable formats like LaTeX.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Methodology](#methodology)
- [Results and Discussion](#results-and-discussion)
- [Future Work](#future-work)
- [Deployed Link](#deployed-link)
- [Authors](#authors)
- [Model and Code Access](#model-and-code-access)

## Introduction
Mathematical Expression Recognition (MER) plays a crucial role in educational and professional settings, allowing for the digitization of handwritten math content. This project aims to design a CNN-Transformer model capable of converting handwritten expressions into LaTeX for easy editing and digital storage.

## Features
- **Hybrid CNN-Transformer Model**: Combines CNNs for feature extraction and Transformers for spatial relationship interpretation.
- **Real-time Recognition**: Optimized for quick processing of mathematical symbols.
- **Output Formats**: Supports LaTeX or MathML output for recognized expressions.
- **Enhanced Accuracy**: Developed with a focus on high symbol recognition accuracy and handling a wide range of mathematical symbols.

## System Architecture
The architecture includes a CNN for symbol recognition and a Transformer to understand symbol relationships. This combined approach allows the model to manage the two-dimensional structure of handwritten mathematical expressions effectively.

## Methodology
1. **Data Acquisition**: Collect handwritten expressions from sources like scanned documents or digital input devices.
2. **Preprocessing**: Convert images to grayscale, reduce noise, and apply thresholding.
3. **Segmentation**: Separate images into individual symbols or groups for processing.
4. **Model Inference**: Use CNNs for feature extraction and Transformers for spatial relationships.
5. **Output Generation**: Convert the recognized symbols into LaTeX or MathML.

## Results and Discussion
The model demonstrates high accuracy in symbol recognition and effectively converts basic mathematical expressions. However, challenges remain with complex structures and diverse handwriting styles, suggesting areas for improvement in preprocessing and attention mechanisms.

## Future Work
- Implement advanced attention mechanisms for complex expressions.
- Improve preprocessing for better symbol isolation.
- Expand training data for broader handwriting diversity.
- Optimize model for deployment on mobile and resource-limited devices.

## Deployed Link
[View the Deployed Application](#)

## Authors
- Chime Gyeltshen Dorji
- Chencho Wangdi
- Tenzin Kinchap
- Karma Wangchuk

## Model and Code Access
Due to GitHub's file size limit of 100 MB, our model and code could not be uploaded to the GitHub repository. You can access the model and code on Google Drive at the following link:

[Download Model and Code](https://drive.google.com/file/d/1uXnDdeZsrp-Evht1aP1WXIoQ05ySpE3g/view?usp=sharing)
