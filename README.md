# Credit Card Fraud Detection 🕵️‍♂️💳🔍

## 🚀 Project Overview
This repository features a comprehensive analysis and modeling project aimed at detecting credit card fraud. The project uses a dataset from September 2013, consisting of European credit card transactions, to train models that can distinguish between legitimate and fraudulent transactions. The core of this project lies in addressing the challenges posed by the highly unbalanced nature of the dataset, where frauds constitute only a small fraction of all transactions.

## 📌 Key Features
- **Binary Classification Models**: The project approaches fraud detection as a binary classification problem, differentiating between fraudulent (1) and legitimate (0) transactions.
- **Dataset Analysis and Visualization**: Detailed exploration of the dataset, including visualization of transaction classes and amount distributions.
- **Data Preprocessing**: Standardization and normalization of features to prepare the dataset for modeling.
- **Model Training and Evaluation**: Implementation and evaluation of Decision Tree and Support Vector Machine (SVM) models using both Scikit-Learn and Snap ML.
- **Performance Metrics**: Evaluation of models based on ROC-AUC score and hinge loss, with a focus on handling class imbalance.

## 🛠️ Built With
- Python: For data manipulation and modeling.
- Scikit-Learn & Snap ML: For implementing and comparing machine learning models.
- Pandas & NumPy: For data handling and numerical operations.
- Matplotlib: For data visualization.

## 🎯 Application Scenarios
- **Fraud Detection**: Ideal for financial institutions looking to enhance their fraud detection systems.
- **Benchmarking**: Provides a basis for comparing the performance of Scikit-Learn and Snap ML models.

## 🔍 Inside the Code
- **Data Inflation**: Techniques to artificially inflate the dataset for more robust training.
- **Class Imbalance Handling**: Strategies like computing sample weights to make models more sensitive to the minority class.
- **Model Training and Timing**: Training of models with an emphasis on training time and efficiency.
- **Model Comparison**: Comparative analysis of Scikit-Learn and Snap ML models in terms of speed and accuracy.
