# Credit Card Fraud Detection

## Overview

This project is a machine learning solution for detecting fraudulent credit card transactions. The dataset and notebook focus on building and evaluating models to distinguish between legitimate and fraudulent transactions using features such as transaction amount, time, and anonymized variables.

## Features

The key features in the dataset include:

- **Time**: Time elapsed since the first transaction in the dataset.
- **Amount**: Transaction amount.
- **V1 to V28**: Anonymized features resulting from PCA transformation.
- **Class**: Target variable (0 for legitimate transactions, 1 for fraudulent transactions).

## Requirements

To run this project, ensure you have the following installed:

- Python 3.8+
- Jupyter Notebook
- Required Python libraries (install using `pip install -r requirements.txt`):
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Project Workflow

1. **Data Loading**:

   - Load the dataset, typically available as a `.csv` file.
   - Perform initial data exploration and preprocessing.

2. **Exploratory Data Analysis (EDA)**:

   - Visualize the class imbalance.
   - Analyze feature distributions and correlations.

3. **Data Preprocessing**:

   - Scale numerical features like `Time` and `Amount`.
   - Split the dataset into training and testing sets.

4. **Model Building**:

   - Train machine learning models such as Logistic Regression, Decision Trees, or Random Forests.
   - Use techniques like SMOTE for handling class imbalance.

5. **Evaluation**:

   - Evaluate models using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
   - Visualize confusion matrices and ROC curves.

## How to Use

1. Clone this repository.
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory and install dependencies.
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook.
   ```bash
   jupyter notebook credit_card_fraud_detection.ipynb
   ```
4. Run the cells sequentially to execute the workflow.

## Results

- Include details about the best-performing model, evaluation metrics, and any key insights.
- Example:
  - **Best Model**: Random Forest Classifier
  - **AUC-ROC**: 0.98
  - **Precision**: 0.92
  - **Recall**: 0.88

## Acknowledgements

The dataset is typically sourced from the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## License

This project is licensed under the MIT License. See the LICENSE file for details.

