# AI-Based Leaf Disease Detection

### Client-Provided Project | Artificial Intelligence & Deep Learning

## Project Overview

AI-Based Leaf Disease Detection is an Artificial Intelligence and Deep Learning project designed to identify plant diseases through leaf images.

The system uses a trained deep learning model to classify leaf images into healthy and diseased categories across 38 supported classes.

## Project Objectives

- Detect plant diseases through leaf images.
- Identify healthy and diseased leaves.
- Apply AI and Deep Learning to image classification.
- Support preliminary identification of plant diseases.
- Explore AI applications in agriculture.

## Problem Statement

Plant diseases can negatively affect crop quality and agricultural production. Identifying diseases manually may require time and specialized knowledge. This project aims to use AI-based image classification to make preliminary plant disease identification more accessible.

## Proposed Solution

The project uses Computer Vision and Transfer Learning to analyze plant leaf images and predict their disease categories.

The model preprocesses input images, analyzes them using MobileNetV2 and generates a predicted class with a confidence score.

## Technologies Used

- Python
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- CNN (Convolutional Neural Network)
- Google Colab

## Implemented Features

- Plant leaf image classification.
- Identification of healthy and diseased leaves.
- Support for 38 plant disease categories.
- Image preprocessing and prediction.
- Prediction confidence score.
- Model training and evaluation.
- Classification Report and Confusion Matrix.

## Dataset & Model

- **Dataset:** PlantVillage
- **Number of Classes:** 38
- **Model:** MobileNetV2 with Transfer Learning
- **Image Size:** 224 × 224
- **Training Epochs:** 10
- **Framework:** TensorFlow / Keras

## Model Performance

The model was evaluated on 10,861 validation images.

| Evaluation Metric | Result |
|---|---:|
| Validation Accuracy | 95.41% |
| Weighted Precision | 0.95 |
| Weighted Recall | 0.95 |
| Weighted F1-Score | 0.95 |
| Macro F1-Score | 0.94 |

These results represent validation performance. Actual performance on real-world leaf images may vary.

## Project Scope

The project focuses on image-based plant disease classification using AI and Deep Learning. The current model supports the 38 categories available in the PlantVillage dataset.

Future improvements may include additional plant species, more diverse real-world images and disease management recommendations.

## Project Source

This project was received from a client as a project requirement.

---

**Project Category:** Artificial Intelligence / Machine Learning / Deep Learning

**Project Title:** AI-Based Leaf Disease Detection

**Purpose:** AI-Powered Plant Disease Identification
