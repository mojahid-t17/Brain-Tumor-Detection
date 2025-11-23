# Brain Tumor Detection

## Course Information

- **Course Title:** Machine Learning Laboratory  
- **Course Code:** CSE 458  

## Authors

1. **Aditya Sankar Das** – Student ID: 2104010202310  
2. **Mojahidul Islam** – Student ID: 2104010202323  
3. **Abidul Haque Alvee** – Student ID: 0222210005101142  
4. **Rahat Imroz** – Student ID: 0222220005101128  

## Project Overview

This project focuses on the detection of brain tumors from MRI scans using deep learning models. We implemented and evaluated multiple Convolutional Neural Network (CNN) architectures including:

- **SimpleCNN**  
- **VGG16**  
- **DenseNet121**  
- **ResNet50**  
- **EfficientNetB0**  

The project explores both model performance and interpretability using metrics, confusion matrices, ROC curves, accuracy/loss plots, and Grad-CAM visualizations.

## Dataset

The dataset used for this project is publicly available from [Mendeley Data](https://data.mendeley.com/datasets/c9rt8d6zrf/1). It contains labeled MRI images of brain tumors, including different tumor types and non-tumor scans.  



## Features

- Training and evaluation of multiple deep learning models  
- Preprocessing with resizing, normalization, and data augmentation  
- Quantitative evaluation with metrics: accuracy, precision, recall, F1-score, and AUC  
- Confusion matrix and ROC curve visualizations  
- Grad-CAM heatmaps for model interpretability  
- Comparison of model performance through bar charts and loss curves  

## Requirements

All dependencies are listed in `requirements.txt` and include:

- Python 3.10+  
- TensorFlow 2.12+  
- NumPy  
- Matplotlib  
- scikit-learn  
- Pillow  
- h5py  

Install dependencies using:

```bash
pip install -r requirements.txt
