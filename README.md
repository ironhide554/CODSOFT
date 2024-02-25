# Credit Card Fraud Detection Model

## Overview

This project implements two machine learning model one is Logistic Regression and other one is Random Forest Classifer for detecting fraudulent credit card transactions. The model is trained on a labeled dataset which contains both valid and fraudulent transactions to learn insights that distinguish between the two classifications.

## Dataset

The dataset used for training and testing the model is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) available on Kaggle. It consists of transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, with only 492 frauds out of 284,807 transactions.

Dataset is present in this repository in archive.zip file , you need to unzip this file in google colab or you can perform unzipping on your local computer .

## Model

The fraud detection model is developed using Python and scikit-learn. The following steps are involved in the model development:

1. Data Preprocessing: The dataset is preprocessed to handle missing values, scale numerical features, removal of duplicate values and balancing of the data via undersampling method.
2. Model Selection: Various machine learning algorithms such as Logistic Regression and Random Forest are evaluated to select the best performing model.
3. Model Training: The selected model is trained on the preprocessed data.
4. Model Evaluation: The trained model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. 

## Usage

To use the fraud detection model:

1. Clone this repository:
   ```
   git clone https://github.com/ironhide554/credit-card-fraud-detection.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook `credit_card_fraud_detection.ipynb` to train and evaluate the model.

## Results

The final model achieves an accuracy of 93%  on the test set. Detailed evaluation metrics are provided in the notebook.

## Future Improvements

- Explore advanced feature engineering techniques to improve model performance.
- Experiment with ensemble methods to further enhance the model's ability to detect fraud.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template according to your project's specific details and requirements.
