# Breast Cancer Classification using Machine Learning

This repository contains a Jupyter Notebook implementation of a breast cancer classification model. The project uses machine learning techniques to classify tumors as **benign** or **malignant** based on features in the dataset.

## 📊 Dataset

The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Data Set**, which includes features computed from digitized images of fine needle aspirate (FNA) of breast masses.

### 📁 Features

- Radius, texture, perimeter, area, smoothness, etc. (mean, standard error, worst)
- Diagnosis label: **B (Benign)** or **M (Malignant)**

You can download the dataset directly from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)) or use `sklearn.datasets`.

## 🚀 Project Highlights

- Exploratory Data Analysis (EDA)
- Feature scaling and preprocessing
- Model training (Logistic Regression / SVM / Decision Tree / etc.)
- Performance metrics (accuracy, confusion matrix, precision, recall, F1-score)
- Visualization using Matplotlib and Seaborn

## 📦 Requirements

- Python 3.7+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install the required packages using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
