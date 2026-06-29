# ⚾ Baseball Team Wins Prediction using Machine Learning

A Machine Learning project that predicts the number of wins (`W`) for baseball teams using player and team statistics. The project demonstrates the complete machine learning pipeline, including data preprocessing, feature engineering, feature selection, model training, and prediction using **Linear Regression**.

---

## 📌 Project Overview

This project uses a baseball statistics dataset to predict a team's total wins based on selected performance metrics. It demonstrates essential machine learning concepts such as:

* Data preprocessing
* Missing value handling
* Target Encoding
* Feature Selection
* Train-Test Split
* Linear Regression
* Prediction

---

## 🚀 Features

* Load and analyze the baseball dataset
* Handle missing values using Median Imputation
* Encode high-cardinality categorical data using Target Encoding
* Select the best features using Mutual Information
* Split the dataset into training and testing sets
* Train a Linear Regression model
* Predict team wins
* Compare predicted and actual values

---

## 📂 Dataset

**File:** `train.csv`

The dataset contains baseball team statistics, including:

* W (Wins)
* H (Hits)
* HR (Home Runs)
* SO (Strikeouts)
* SB (Stolen Bases)
* and other team performance statistics.

---

## 🛠️ Technologies Used

* Python 3
* Pandas
* NumPy
* Scikit-learn
* Category Encoders

---

## 📦 Required Libraries

Install the required packages using:

```bash
pip install pandas numpy scikit-learn category_encoders
```

---

## 📊 Machine Learning Workflow

1. Load the dataset
2. Handle missing values using Median Imputation
3. Create a high-cardinality categorical feature
4. Apply Target Encoding
5. Perform Feature Selection using Mutual Information
6. Split the dataset into training and testing sets
7. Train a Linear Regression model
8. Predict team wins
9. Compare predicted and actual results

---

## 📁 Project Structure

```text
Baseball-Team-Wins-Prediction/
│
├── train.csv
├── ml_project.py
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Baseball-Team-Wins-Prediction.git
```

Go to the project folder:

```bash
cd Baseball-Team-Wins-Prediction
```

Run the project:

```bash
python ml_project.py
```

---

## 📈 Sample Output

```text
Loading Dataset...

Dataset loaded successfully.
Rows: XXXX
Columns: XX

Handling Missing DATA...

Applying Target Encoder...

Selected Features:
['H', 'HR']

Training data size: (xxx, 2)
Testing data size: (xxx, 2)

Predictions

Model guessed: 89
Real answer: 91
Difference: 2
```

---

## 📚 Machine Learning Concepts Used

* Data Cleaning
* Missing Value Imputation
* Feature Engineering
* Target Encoding
* Feature Selection
* Linear Regression
* Model Prediction

---

## 🔮 Future Enhancements

* Add Random Forest Regressor
* Add Decision Tree Regression
* Compare multiple ML algorithms
* Evaluate model using MAE, RMSE, and R² Score
* Create visualizations using Matplotlib and Seaborn
* Build a web interface using Streamlit
* Deploy the model using Flask or FastAPI

---

## 👨‍💻 Author

**Shiva**

If you found this project useful, consider giving it a ⭐ on GitHub.


