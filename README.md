# Credit Card Fraud Detection

## Project Overview

Credit Card Fraud Detection is a critical application of machine learning that aims to protect financial institutions and cardholders from fraudulent transactions. This project focuses on developing an effective fraud detection system using various machine learning algorithms. The system is designed to identify and flag potentially fraudulent transactions in real-time, thereby enhancing security and reducing financial losses.

Fraudulent transactions can cause significant financial damage and compromise the safety of credit card holders. To address this issue, this project uses historical transaction data to train and evaluate models that can detect anomalies and suspicious patterns indicative of fraud. The dataset contains anonymized transaction details, which are processed and analyzed using advanced machine learning techniques.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and includes anonymized credit card transactions. The dataset consists of:

- **Time**: The number of seconds elapsed between this transaction and the first transaction in the dataset.
- **V1, V2, V3, ..., V28**: Anonymized features derived from a Principal Component Analysis (PCA) transformation to protect sensitive information.
- **Amount**: The monetary value of the transaction.
- **Class**: The target variable, where `1` represents a fraudulent transaction and `0` represents a legitimate transaction.

## Installation

To set up and run the project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/5jpablo/Credit_Card_Fraud_Detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Credit_Card_Fraud_Detection
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

The project provides several scripts for different stages of the workflow:

1. **Data Preprocessing**: Load and preprocess the dataset to prepare it for modeling. This step includes handling missing values, normalizing features, and splitting the data into training and testing sets.

2. **Model Training**: Train various machine learning models to detect fraudulent transactions. The available models include:
   - **Decision Trees**: Simple, interpretable models that are effective for initial exploration.
   - **Random Forest**: An ensemble method that improves performance by combining multiple decision trees.
   - **Gradient Boosting Machines (GBM)**: A boosting technique that enhances model accuracy through iterative learning.
   - **XGBoost**: An optimized version of gradient boosting with advanced features and faster performance.
   - **Neural Networks**: Deep learning models that capture complex patterns in the data.

3. **Model Evaluation**: Assess the performance of the trained models using various metrics such as accuracy, precision, recall, F1-score

## Results

The project includes detailed results and performance metrics for each model. The evaluation process involves generating visualizations and reports that highlight the effectiveness of each model in detecting fraudulent transactions. Key metrics include:

- **Accuracy**: The overall correctness of the model.
- **Precision**: The proportion of true positive predictions among all positive predictions.
- **Recall**: The proportion of true positive predictions among all actual positives.
- **F1-Score**: The harmonic mean of precision and recall.

