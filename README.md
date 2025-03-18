# Credit Card Fraud Detection

## Overview
This repository contains an analysis and machine learning models for detecting fraudulent transactions using the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The dataset consists of real-world transactions made using credit cards in September 2013 by European cardholders.

## Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Features:** 30 numerical features (V1-V28, Time, and Amount)
- **Class Distribution:** Highly imbalanced (99.83% legitimate, 0.17% fraudulent)
- **Confidentiality:** Due to privacy reasons, the dataset is anonymized

## Project Structure
```
├── data/               # Dataset files (not included due to size limitations)
├── notebooks/          # Jupyter notebooks for EDA and model training
├── src/                # Source code for data preprocessing and model training
├── models/             # Saved trained models
├── results/            # Evaluation metrics and visualizations
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
```

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/creditcard-fraud-detection.git
   cd creditcard-fraud-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download the dataset from Kaggle and place it in the `data/` directory.

## Usage
### Exploratory Data Analysis (EDA)
Run the following Jupyter notebook for data visualization and exploration:
```sh
jupyter notebook notebooks/eda.ipynb
```

### Model Training
To train a machine learning model, execute the training script:
```sh
python src/train_model.py
```

### Evaluation
Evaluate the trained model using:
```sh
python src/evaluate_model.py
```

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
- [Machine Learning Group - ULB](https://mlg.ulb.ac.be/)
- Kaggle for hosting the dataset

---
For any questions, feel free to reach out!

