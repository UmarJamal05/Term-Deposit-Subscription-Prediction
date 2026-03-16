# **Term-Deposit-Subscription-Prediction**

This project aims to predict whether a client will subscribe to a term deposit based on the **Bank Marketing Dataset**.

## **Dataset**
- The dataset used is **"bank-full.csv"**, obtained from the **UCI Machine Learning Repository**.
- **Dataset Link**: [Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank%2Bmarketing)

## **Project Overview**
The following steps were performed in this project:

1. **Corpus Preparation**:
   - **Data Cleaning**: Removing duplicates, handling missing values, removing irrelevant features, and addressing outliers.
   - **Data Transformation**: Encoding categorical variables, scaling numerical features, and balancing the dataset using SMOTE.

2. **Training Models**:
   - **Random Forest**: Trained with default hyperparameters and evaluated.
   - **Neural Network**: Trained with three hidden layers (128, 64, 32 neurons) and evaluated.

3. **Model Comparison**:
   - The models were compared based on metrics such as accuracy, precision, recall, and F1-score.
   - Results were summarized in a comparison table.

4. **ROC Curve Visualization**:
   - ROC curves were plotted for both models to visualize their performance across various thresholds.
   - The Area Under the Curve (AUC) was calculated to quantify model performance.
