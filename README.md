# Credit Card Fraud Detection

## Overview
This repository contains an analysis and machine learning models for detecting fraudulent transactions using the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The dataset consists of real-world transactions made using credit cards in September 2013 by European cardholders.

## Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Features:** 30 numerical features (V1-V28, Time, and Amount)
- **Class Distribution:** Highly imbalanced (99.83% legitimate, 0.17% fraudulent)
- **Confidentiality:** Due to privacy reasons, the dataset is anonymized


## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/Aditya-Pal01/Credit-Card-Fraud-Detection.git
   cd creditcard-fraud-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download the dataset from Kaggle and place it in the `data/` directory.


## Models Used
- Logistic Regression
- Random Forest
- XGBoost
- Neural Networks

## Results
- Performance metrics include Precision, Recall, F1-score, and AUC-ROC.
- Due to class imbalance, techniques like SMOTE and class weighting are applied.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Kaggle for hosting the dataset

---
For any questions, feel free to reach out

