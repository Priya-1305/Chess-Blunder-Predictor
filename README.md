# Chess Blunder Predictor Model

A fun, behavioral‑driven machine learning project that predicts the **number of moves** a chess player might make before there first blunder, based on their mental state, habits, and match conditions.

This project is part of my **100 Days of AI/ML Learning Journey**, where I build projects that help others learn what I learned.

Join me here: https://www.linkedin.com/in/priya-sirohi-048079257/

---

## 📌 Overview

The goal of this model is to explore how **human factors** influence chess decision‑making. The dataset includes behavioral and game‑related features such as mood, sleep, caffeine, opponent rating, and more.

The model uses **Linear Regression / Random Forest / (your chosen algorithm)** to predict how likely a player is to blunder in a match.

Check out the dataset here : https://www.kaggle.com/datasets/priyasirohi1/chess-blunders-dataset
Important note: This dataset reflects my personal games, so it may not be fully generalizable.

---

## 🧠 Features Used

| Feature                 | Description                                      |
| ----------------------- | ------------------------------------------------ |
| **Mood (1–10)**         | Higher mood → fewer mistakes                     |
| **Caffeine Intake**     | 0 = none, 1 = chai, 2 = coffee, 3 = energy drink |
| **Sleep Hours (0–10)**  | Fewer hours → more blunders                      |
| **Phone Notifications** | More distractions = more mistakes                |
| **Opponent Rating**     | Stronger opponent → higher pressure              |
| **Time Control**        | 1 = Bullet, 2 = Blitz, 3 = Rapid                 |

---

## 📁 Project Structure

```
├── data/
│   ├── chess_blunders.csv
├── notebooks/
│   ├── model_training.ipynb
├── README.md
```

---

## 🚀 How to Run

1. **Clone the repo**

```
git clone <your-repo-url>
cd chess-blunder-predictor
```

2. **Run the notebook or script**

```
jupyter notebook notebooks/model_training.ipynb
```

---

## 📊 Model Summary

* **Problem Type:** Regression
* **Target Variable:** Number of moves
* **Algorithms Tried:**

  * Linear Regression
  * Random Forest Regressor
* **Evaluation Metrics:** RMSE, MAE, R²

---

## 🌟 Key Learnings

* How human behavior can be quantified in ML datasets
* Data cleaning & feature engineering
* Training and evaluating regression models
* Visualizing insights using Matplotlib/Seaborn

---

## 📝 Future Improvements

* Add more players and games
* Use real game data from Lichess API
* Try deep learning models
* Deploy the model as a web app (Streamlit / Gradio)

---

## ❤️ Acknowledgements

Created as part of my **100 Days of AI/ML Challenge**.

Feel free to fork this repo and experiment with your own data!
