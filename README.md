# Premier-League-Predictor
# Premier League Match Outcome Predictor ⚽️

This project builds a machine learning model to predict the outcome of Premier League football matches (win or not) using historical match statistics and recent team performance trends.

## 🔍 Overview

Using match data from multiple seasons, the model predicts whether a team will win a given match based on factors like:
- Match venue and time
- Opponent team
- Recent form (goals, shots, penalties, etc.)

The final model uses a Random Forest Classifier to make predictions and evaluates performance using accuracy and precision metrics.

## 🛠 Tools & Libraries
- Python
- pandas
- scikit-learn
- Jupyter Notebook

## 🧠 Key Features
- Feature engineering using rolling averages of past 3 matches
- Encoding of categorical features (venue, opponent)
- Model training and prediction using Random Forest
- Evaluation with accuracy and precision metrics

## 📈 Sample Results
- Accuracy: 78%
- Precision (predicting wins): 81%
- Improved prediction accuracy by 15% using rolling features

## 📁 Files
- `matches.csv`: Dataset with historical match statistics
- `Predict Premier League Match Winners.ipynb`: Full analysis, modeling, and results

## ✅ How to Run
1. Clone this repo
2. Install required libraries: `pip install pandas scikit-learn`
3. Open the notebook and run all cells


