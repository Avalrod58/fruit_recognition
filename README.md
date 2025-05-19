# Fruit Recognition with CNN

A deep learning project for classifying six types of fruits using a Convolutional Neural Network (CNN): **banana, strawberry, lemon, mandarin, apple**, and **pear**.

## Overview

This project was developed in **Google Colab** and leverages **TensorFlow/Keras** for training and evaluating a CNN model capable of classifying fruit images. It includes:

- A custom CNN architecture trained on color images of 128×128 pixels  
- Image preprocessing and augmentation to improve generalization  
- A **Flask** server exposing a `/predict` endpoint  
- A **Gradio** interface for real-time model interaction  
- Support for grayscale and RGB image modes (depending on model version)

## Technologies Used

- Python  
- TensorFlow / Keras  
- Flask (REST API)  
- Gradio (UI for model interaction)  
- NumPy, PIL, Matplotlib, and other utilities

## Features

- Real-time fruit classification via web UI or JSON API  
- Deployed in Colab with **ngrok** tunneling for external access  
- Clean, modular codebase with easy model loading and preprocessing  
- Returns class name and confidence score  
- Supports both grayscale and color models

## Getting Started

1. Clone the project or open the notebook in Google Colab.  
2. Train the model or load a pre-trained `.h5` file.  
3. Launch the Flask server or the Gradio interface.  
4. Use ngrok to expose the endpoint for external access (if needed).  

## Example Prediction Output

```json
{
  "Clase": "manzana",
  "Confidence": 0.9812
}
