# Model Tester Application

## Overview

The Model Tester Application is a graphical user interface (GUI) tool designed to help users upload CSV files, preprocess the data, select features and target columns, train multiple machine learning models, and evaluate their performance. The application uses Tkinter for the GUI and integrates various machine learning algorithms to provide a comprehensive model evaluation platform.

## Features

- **File Upload**: Easily upload CSV files containing your dataset.
- **Data Preprocessing**: Automatically handle duplicate and missing values in the dataset.
- **Feature Selection**: Select features and target columns for model training.
- **Model Training**: Train multiple machine learning models including Linear Regression, Random Forest, Gradient Boosting, SVM, and KNN.
- **Model Evaluation**: Evaluate model performance using Mean Squared Error (MSE) and R-squared (R2) metrics.
- **Visualization**: Visualize model predictions with scatter plots.
- **Best Model Selection**: Identify and display the best model based on R2 score.

## Benefits

- **User-Friendly Interface**: Intuitive and easy-to-use GUI built with Tkinter.
- **Flexibility**: Supports any CSV dataset, making it versatile for various applications.
- **Comprehensive Analysis**: Provides detailed performance metrics and visualizations to help users understand model effectiveness.
- **Educational Tool**: Great for learning and experimenting with different machine learning models and preprocessing techniques.

## Requirements

- Python 3.x
- Tkinter
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
