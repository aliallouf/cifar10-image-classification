# CIFAR-10 Image Classification with TensorFlow

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)

This repository contains a Convolutional Neural Network (CNN) implementation for classifying images into 10 distinct categories using the **CIFAR-10** dataset. The project covers data exploration, visualization, model performance evaluation, and interactive image inference.

## 🚀 Mission
The goal is to build an accessible, pre-trained model that can reliably distinguish between various vehicles and animals. The notebook demonstrates high precision in identifying categories like **airplanes**, **ships**, and **trucks**, while providing an interactive widget for real-time user testing.

## 📊 Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes:
- **Animals:** Bird, Cat, Deer, Dog, Frog, Horse.
- **Vehicles:** Airplane, Automobile, Ship, Truck.

## 🧠 Model Performance
The model was trained and evaluated using a classification report. Key results include:
- **Vehicles:** Excellent performance, achieving ~99.7% confidence on airplanes and ~99.5% on ships in sample tests.
- **Animals:** Good general performance, though some organic classes like birds can show lower confidence (~33.4%) depending on image complexity.

## 🖼️ Interactive Inference
The notebook features an `ipywidgets` upload tool. Users can click the **Upload** button to select a local image, and the model will immediately display the prediction and confidence score.

## 🛠️ Installation & Usage
1. Clone the repo:
   ```bash
   git clone [https://github.com/aliallouf/cifar10-classifier.git](https://github.com/aliallouf/cifar10-classifier.git)