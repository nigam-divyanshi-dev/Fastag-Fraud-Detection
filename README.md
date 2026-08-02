# 🚗 Fastag Fraud Detection using Machine Learning

A Machine Learning project that detects fraudulent FASTag transactions by analyzing transaction data and classifying them as **Fraudulent** or **Legitimate**. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and hyperparameter tuning.

---

## 📌 Project Overview

The objective of this project is to build an accurate fraud detection model that can identify suspicious FASTag transactions using supervised machine learning techniques. Multiple classification algorithms are trained and compared to determine the best-performing model.

---

## ✨ Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Handling Missing Values
- Label Encoding for Categorical Features
- Feature Selection
- Train-Test Split
- Multiple Machine Learning Models
- Model Performance Evaluation
- Hyperparameter Tuning using RandomizedSearchCV/GridSearchCV

---

## 📂 Dataset

The project uses the **Fastag Fraud Detection** dataset containing transaction-related information.

Example features include:

- Fastag ID
- Vehicle Type
- Vehicle Speed
- Toll Plaza Information
- Transaction Details
- Amount Paid
- Fraud Label (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting Classifier

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Fastag-Fraud-Detection/
│
├── fraudDetection.ipynb
├── data/
│   └── FastagFraudDetection.csv
├── README.md
└── .gitignore
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Fastag-Fraud-Detection.git
```

Move into the project directory:

```bash
cd Fastag-Fraud-Detection
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
fraudDetection.ipynb
```

---

## 📈 Workflow

1. Import Dataset
2. Perform Data Cleaning
3. Exploratory Data Analysis
4. Encode Categorical Features
5. Split Data into Training & Testing Sets
6. Train Multiple ML Models
7. Compare Model Performance
8. Tune Hyperparameters
9. Select the Best Model

---

## 🎯 Future Improvements

- Deploy using Streamlit or Flask
- Add real-time fraud prediction
- Handle class imbalance using SMOTE
- Experiment with XGBoost and LightGBM
- Build an interactive dashboard

---

## 📷 Output

The notebook includes:

- Dataset Analysis
- Visualizations
- Model Comparison
- Performance Metrics
- Final Fraud Predictions

---

## 👩‍💻 Author

**Divyanshi Nigam**

B.Tech Computer Science Student

---

## ⭐ If you found this project useful, consider giving the repository a star!
