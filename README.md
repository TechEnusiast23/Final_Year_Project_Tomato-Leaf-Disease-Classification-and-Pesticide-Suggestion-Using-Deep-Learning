# Final_Year_Project_Tomato-Leaf-Disease-Classification-and-Pesticide-Suggestion-Using-Deep-Learning

# 🍅 Tomato Leaf Disease Classification and Pesticide Suggestion using Deep Learning

This project presents a **hybrid deep learning model** to classify tomato leaf diseases from images and suggest appropriate pesticides based on the prediction. The model leverages the combined power of **EfficientNet-B0**, **VGG16**, and a custom **Convolutional Neural Network (CNN)** for improved accuracy.

## 📌 Project Overview

Tomato crops are widely cultivated, and their health significantly impacts agricultural productivity. Early and accurate detection of tomato leaf diseases can prevent large-scale crop damage. This system aims to:
- Classify tomato leaf diseases using image data
- Suggest the most effective pesticide based on the disease

## 🚀 Features

- Hybrid deep learning architecture: EfficientNet-B0 + CNN + VGG16
- Image classification with high accuracy
- Pesticide recommendation system
- User-friendly interface for image upload and result display
- Suitable for farmers and agricultural researchers

## 🧠 Model Architecture

- **EfficientNet-B0**: Lightweight, efficient feature extractor
- **VGG16**: Deep feature extractor for high-level visual features
- **Custom CNN**: Fused layers for final prediction
- **Fusion Layer**: Combines outputs from all three models before classification
- **Softmax Classifier**: Outputs probabilities for each class

## 🗂️ Dataset

- Publicly available tomato leaf disease dataset (e.g., PlantVillage)
- 9 classes: healthy + 8 disease categories
- Preprocessed using resizing, normalization, and augmentation techniques

## 🏗️ Project Structure




















## 🧪 Requirements

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt

















git clone https://github.com/your-username/Tomato-Leaf-Disease-Classification.git
cd Tomato-Leaf-Disease-Classification









python predict.py --image path_to_leaf_image.jpg







cd app
python app.py












Disease: Early Blight
Confidence: 97.2%
Suggested Pesticide: Mancozeb or Chlorothalonil
