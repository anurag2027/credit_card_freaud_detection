# Credit Card Fraud Detection

This repository contains a machine learning project that focuses on detecting fraudulent credit card transactions using classification models. The project includes data preprocessing, SMOTE oversampling, model training (Random Forest), and performance evaluation using metrics like precision, recall, and AUC-ROC.

## Dataset

We use the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.

- It contains anonymized transaction data for European cardholders in September 2013.
- Total: 284,807 transactions
- Fraudulent: 492
- Legitimate: 284,315

> **Note**: The full dataset is not included in this repository due to its size and licensing terms.  
Please download the dataset manually and place the `creditcard.csv` file in a `data/` folder.

```bash
/data/creditcard.csv
```

##  How to Use

1. Clone this repository
2. Download the dataset from Kaggle (link above)
3. Place the CSV file in the `data/` directory
4. Run the notebook or Python scripts to train and evaluate the model

##  Model Used

- Random Forest Classifier
- SMOTE for handling class imbalance
- GridSearchCV for hyperparameter tuning

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

##  Visualizations

- Class distribution before and after SMOTE
- ROC Curve
- Confusion Matrix

---

Feel free to fork this project or contribute improvements!
