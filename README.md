# Credit-Card-Fraud-Detection
Data Science, Machine learning, Classifier, Logistic Regression, Shallow neural Networks, Deep Learning, Data visualizatin

**Introduction:**

The Fraud Detection Project aims to develop robust machine learning models for the detection of fraudulent transactions in financial data. With the increasing prevalence of digital transactions, financial institutions face challenges in identifying and preventing fraudulent activities. This project leverages advanced machine learning techniques to improve the accuracy and efficiency of fraud detection systems, thereby protecting the interests of financial institutions and their customers.

**Project Structure:**

- **data/**: Directory containing the dataset used for training and evaluation.
- **models/**: Directory for storing trained machine learning models.
- **notebooks/**: Jupyter notebooks for data exploration, model training, and evaluation.
- **scripts/**: Python scripts for data preprocessing, model training, and evaluation.
- **README.md**: Project overview and instructions.
- **requirements.txt**: List of required Python packages.
- **LICENSE**: Project license information.

**Data Description:**

The dataset used in this project contains financial transaction data, including features such as transaction amount, time, and various anonymized numerical features. The dataset is obtained from [source]. It is divided into two main classes: fraudulent transactions (Class 1) and non-fraudulent transactions (Class 0).

**Requirements:**

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TensorFlow/Keras

**Installation:**

To install the required Python packages, run the following command:
```
pip install -r requirements.txt
```

**Usage:**

- Clone the repository: `git clone https://github.com/yourusername/fraud-detection-project.git`
- Navigate to the project directory: `cd fraud-detection-project`
- Run Jupyter notebooks or Python scripts in the `notebooks/` and `scripts/` directories for data exploration, model training, and evaluation.

**Results:**

The project provides detailed classification reports for both the imbalanced and balanced datasets. Below are the outputs from the classification reports:

**Imbalanced Dataset:**

- Logistic Regression:
              precision    recall  f1-score   support

   Not Fraud       1.00      1.00      1.00     22743
       Fraud       0.88      0.71      0.79        42

    accuracy                           1.00     22785
   macro avg       0.94      0.86      0.89     22785
weighted avg       1.00      1.00      1.00     22785

- Random Forest:
```
              precision    recall  f1-score   support

   Not Fraud       1.00      1.00      1.00     22743
       Fraud       0.90      0.67      0.77        42

    accuracy                           1.00     22785
   macro avg       0.95      0.83      0.88     22785
weighted avg       1.00      1.00      1.00     22785

```
- Gradient Boosting:
```
              precision    recall  f1-score   support

   Not Fraud       1.00      1.00      1.00     22743
       Fraud       0.59      0.86      0.70        42

    accuracy                           1.00     22785
   macro avg       0.79      0.93      0.85     22785
weighted avg       1.00      1.00      1.00     22785

```
- Linear SVC:
```
              precision    recall  f1-score   support

   Not Fraud       1.00      1.00      1.00     56875
       Fraud       0.89      0.72      0.80        87

    accuracy                           1.00     56962
   macro avg       0.94      0.86      0.90     56962
weighted avg       1.00      1.00      1.00     56962

```
- Shallow Neural Network:
```
              precision    recall  f1-score   support

   Not Fraud       1.00      1.00      1.00     22743
       Fraud       0.88      0.83      0.85        42

    accuracy                           1.00     22785
   macro avg       0.94      0.92      0.93     22785
weighted avg       1.00      1.00      1.00     22785

```

**Balanced Dataset:**

- Logistic Regression:
```
          precision    recall  f1-score   support

       0       0.96      0.93      0.94        72
       1       0.93      0.96      0.94        70

accuracy                           0.94       142

```
- Random Forest:
```
          precision    recall  f1-score   support

       0       0.70      1.00      0.82        72
       1       1.00      0.56      0.72        70

accuracy                           0.78       142

```
- Gradient Boosting:
```
          precision    recall  f1-score   support

       0       0.89      1.00      0.94        72
       1       1.00      0.87      0.93        70

accuracy                           0.94       142

```
- Linear SVC:
```
          precision    recall  f1-score   support

       0       0.82      1.00      0.90        72
       1       1.00      0.77      0.87        70

accuracy                           0.89       142

```
- Shallow Neural Network:
```
          precision    recall  f1-score   support

       0       0.94      0.94      0.94        72
       1       0.94      0.94      0.94        70

accuracy                           0.94       142

```

**License:**

This project is licensed under the MIT License. See the `LICENSE` file for details.

**Author:**

Paul Machau

