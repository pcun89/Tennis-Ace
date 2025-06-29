# Tennis-Ace
# 🎾 Tennis Ace - Predicting ATP Player Success with Linear Regression

## 📌 Project Overview

The **Tennis Ace** project is part of Codecademy’s Data Science Path (Machine Learning section). The goal is to analyze real-world tennis data and create a **Linear Regression** model that predicts a player's **earnings (Winnings)** based on their playing habits and statistics.

You’ll use real ATP data from 2009–2017 that includes offensive, defensive, and outcome-based features for the top 1500 players.

---

## 🧠 Learning Objectives

- Apply **Simple and Multiple Linear Regression**
- Perform **data preprocessing and cleaning**
- Interpret **model coefficients** and **evaluation metrics**
- Practice **independent model building and validation**

---

## 📂 Dataset Information

- File: `tennis_stats.csv`
- Source: ATP (Association of Tennis Professionals)
- Size: Top 1500 ATP players (2009–2017)
- Sample Columns:
  - `FirstServe`
  - `Aces`
  - `DoubleFaults`
  - `ReturnGamesWon`
  - `Winnings`
  - `Ranking`
  - and more...

---

## 🛠️ How It Works

### 1. Data Loading
We load the dataset with `pandas.read_csv()`.

### 2. Preprocessing
We:
- Drop rows with missing values
- Select key features and the target variable (`Winnings`)

### 3. Model Training
We use **scikit-learn’s** `LinearRegression` to fit the model on the training data.

### 4. Evaluation
The model is evaluated using:
- **R² Score** – for model accuracy
- **Mean Squared Error (MSE)** – for prediction error

---

## 🧪 Example Output

