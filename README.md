# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit Card Fraud Detection is a Machine Learning project that identifies fraudulent credit card transactions using Python.

The project implements and compares two supervised machine learning algorithms:
- Decision Tree Classifier
- Random Forest Classifier

SMOTE (Synthetic Minority Oversampling Technique) is also used to address the class imbalance problem.

## 🎯 Objectives

- Detect fraudulent credit card transactions.
- Perform Exploratory Data Analysis (EDA).
- Preprocess and normalize transaction data.
- Build and compare classification models.
- Handle imbalanced datasets using SMOTE.
- Evaluate model performance using classification metrics.

## 📊 Dataset

The project uses an anonymized credit card transaction dataset.

**Dataset details:**
- Total transactions: 284,807
- Genuine transactions: 284,315
- Fraudulent transactions: 492
- Total features: 31
- Target variable: `Class`

The dataset contains PCA-transformed features, along with Time and Amount.

**Target classes:**
- `0` – Genuine transaction
- `1` – Fraudulent transaction

Dataset: Anonymized Credit Card Transactions for Fraud Detection.

The dataset must be downloaded separately and placed in the project directory as `creditcard.csv`.

## 🛠️ Technologies Used

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Imbalanced-learn (SMOTE)

## ⚙️ Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Missing Value Analysis
4. Data Normalization
5. Feature and Target Separation
6. Training and Testing Data Split
7. Decision Tree Model Training
8. Random Forest Model Training
9. Model Evaluation
10. Class Imbalance Handling using SMOTE
11. Final Model Evaluation

## 🤖 Machine Learning Algorithms

### 1. Decision Tree Classifier

A supervised learning algorithm that makes predictions using a tree-like structure of decision rules.

### 2. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance and stability.

### 3. SMOTE

SMOTE generates synthetic samples of the minority class to help address the imbalance between genuine and fraudulent transactions.

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🚀 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/RagulRaj0101/Credit-Card-Fraud-Detection.git
```

**Step 2:** Navigate to the project directory.

```bash
cd Credit-Card-Fraud-Detection
```

**Step 3:** Install the required libraries.

```bash
pip install numpy pandas scikit-learn matplotlib imbalanced-learn
```

**Step 4:** Download the dataset and place `creditcard.csv` in the appropriate directory.

**Step 5:** Open the Jupyter Notebook.

```bash
jupyter notebook
```

**Step 6:** Open `credit_card_fraud.ipynb` and execute the cells.

## 📌 Results

The project compares Decision Tree and Random Forest classifiers before and after applying SMOTE.

The final Random Forest model demonstrates improved performance after addressing class imbalance, with the reference project reporting accuracy above 99%.

## 👨‍💻 Author

**RagulRaj0101**

GitHub: https://github.com/RagulRaj0101

