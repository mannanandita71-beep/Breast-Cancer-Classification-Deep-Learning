# Breast-Cancer-Classification-Deep-Learning
Deep learning project for breast cancer classification using TensorFlow, Keras, and the Wisconsin Breast Cancer Dataset.
# Breast Cancer Classification Using Deep Learning

## Project Overview
This project focuses on classifying breast cancer tumors as **Benign** or **Malignant** using a deep learning model. The project uses the Wisconsin Diagnostic Breast Cancer (WDBC) dataset and a feed-forward neural network built with TensorFlow and Keras.

## Problem Statement
Breast cancer classification is an important medical application of machine learning. The objective of this project is to build a neural network that can classify tumors based on numerical features extracted from breast mass images.

## Objectives
- Understand and preprocess the breast cancer dataset.
- Build a neural network using TensorFlow and Keras.
- Train and evaluate the model.
- Measure performance using classification metrics.
- Analyze challenges such as overfitting and model limitations.

## Dataset
The project uses the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.

- **Number of records:** 569
- **Numerical features:** 30
- **Target classes:** Benign (B) and Malignant (M)
- **Label encoding:** Benign = 0, Malignant = 1

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology
1. Load and explore the dataset.
2. Separate the features and target labels.
3. Split the data into training and testing sets using stratification.
4. Standardize the features using `StandardScaler`.
5. Build a neural network with Dense and Dropout layers.
6. Train the model using the Adam optimizer and binary cross-entropy loss.
7. Use Early Stopping to help reduce overfitting.
8. Evaluate the model on the test dataset.

## Model Architecture
- Input layer: 30 numerical features
- Hidden layer 1: 64 neurons, ReLU activation
- Dropout layer: 20%
- Hidden layer 2: 32 neurons, ReLU activation
- Dropout layer: 20%
- Output layer: 1 neuron, Sigmoid activation

## Evaluation Metrics
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Classification report

The actual evaluation results are available in the project notebook and report.

## Project Files
- `Breast_Cancer_Classification_Using_Deep_Learning.ipynb` — Jupyter/Colab notebook containing the code.
- `Breast_Cancer_Classification_Using_Deep_Learning.pdf` — Final project report (if uploaded).

## How to Run
1. Open the notebook in Google Colab.
2. Upload or load the WDBC dataset.
3. Run the notebook cells in order.
4. Review the model training and evaluation outputs.

## Limitations
This project is educational and uses a limited dataset. The model is not intended for real-world medical diagnosis. Further validation with independent clinical data would be necessary before any practical medical use.

## Conclusion
This project demonstrates an end-to-end deep learning workflow for breast cancer classification, including data preprocessing, neural network design, model training, and evaluation.

**Note:** This project is for educational purposes only and is not a substitute for professional medical advice or diagnosis.
