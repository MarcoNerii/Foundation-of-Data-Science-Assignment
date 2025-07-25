# Foundation-of-Data-Science-Assignment
# 🚕 Taxi Tipping Prediction — Ensemble Learning Challenge

This repository contains my solution for **Challenge II** in the Foundations of Data Science course.  
The goal was to build models that accurately **predict taxi tip amounts** using real-world ride data, with a focus on **ensemble methods** and model comparison.

---

## 📘 Project Overview

The dataset contains New York yellow cab rides from May 2015, including features like trip distance, fare, passenger count, and duration. After cleaning and preprocessing, I trained a variety of models — including tree-based ensembles and neural networks — to predict the **tip amount** left by passengers.

---

## 🧠 Key Learning Goals

- Understand tipping as a regression task
- Compare ensemble methods like XGBoost, LightGBM, Random Forest
- Evaluate models using MAE (Mean Absolute Error)
- Explore overfitting, feature scaling, outlier handling, and signal generalization
- Build a simple but effective **feedforward neural network** as the final model

---

## 📂 Files

- `main.ipynb`: Full notebook with EDA, preprocessing, model training, and evaluation
- `requirements.txt`: All dependencies needed to reproduce results
- `data/taxi_tidy_org`: The dataset used for the challenge (used for feature engineering or time-based analysis)

---

## ⚙️ Tech Stack

- Python 3.x
- `pandas`, `numpy` for data processing
- `matplotlib`, `seaborn` for visualization
- `scikit-learn` for modeling and preprocessing
- `xgboost`, `lightgbm` for gradient boosting
- `tensorflow` for neural networks

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/MarcoNerii/Foundation-of-Data-Science-Assignment.git
   cd taxi-tipping-prediction
   ```

2. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter and run the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

---

## 📈 Summary of Results

- ✅ Best model: Sequential Neural Network (feedforward, 100 neurons)
- ✅ MAE: ~0.52 on unseen data
- 📊 Other models evaluated:
  - XGBoost (v1–v3)
  - LightGBM
  - Random Forest (v1 & v2)
  - Support Vector Regression
  - MLP
  - KNN

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋 Acknowledgment

This is a personal academic project for learning purposes.  
Feedback and suggestions are welcome!
