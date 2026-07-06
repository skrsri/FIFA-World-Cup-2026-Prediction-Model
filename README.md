# ⚽ FIFA World Cup 2026 Prediction Model

A data-driven football analytics project that predicts the outcomes of the **FIFA World Cup 2026** using an **Elo rating system**, the **Dixon-Coles goal model**, and **Monte Carlo tournament simulation**.

The project estimates match probabilities, predicts tournament progression, calculates championship odds, and evaluates model calibration using historical international football data.

---

## 📌 Project Overview

This project combines statistical modeling and probabilistic simulation to forecast the FIFA World Cup 2026.

Instead of relying solely on historical win percentages, the model:

* Builds calibrated Elo ratings for international teams
* Estimates expected goals using the Dixon-Coles model
* Predicts match outcomes (Win / Draw / Loss)
* Simulates the complete tournament thousands of times
* Calculates each team's probability of winning the World Cup
* Evaluates prediction quality through walk-forward backtesting and calibration analysis

---

## ✨ Features

* ⚽ Calibrated Elo rating system
* 📊 Dixon-Coles goal probability model
* 🎯 Match outcome prediction
* 🌍 Head-to-head team comparison
* 🏆 Full FIFA World Cup 2026 tournament simulation
* 🔁 Monte Carlo simulations
* 📈 Probability calibration analysis
* 📉 Reliability diagrams
* 📊 Team strength visualization
* 📋 Championship probability rankings

---

## 📂 Project Structure

```
world-cup-2026-prediction-model/

│── world-cup-2026-prediction-model.ipynb
│── data/
│     ├── results.json
│     ├── elo-calibrated.json
│     └── wc2026-results.json
│── README.md
```

---

## 🧠 Methodology

### 1. Data Collection

The model uses historical international football match data and World Cup fixtures.

Datasets include:

* Historical international match results
* Calibrated Elo ratings
* FIFA World Cup 2026 schedule

---

### 2. Elo Rating System

Each national team is assigned a dynamic Elo rating representing its current strength.

The ratings are continuously updated based on:

* Match results
* Opponent strength
* Home advantage
* Expected performance

---

### 3. Dixon-Coles Model

The Dixon-Coles model estimates the probability of every possible scoreline.

It improves upon a standard Poisson model by adjusting for low-scoring football matches, making predictions more realistic.

Outputs include:

* Expected goals
* Scoreline probabilities
* Win probability
* Draw probability
* Loss probability

---

### 4. Match Prediction

For any two teams, the model predicts:

* Home win probability
* Draw probability
* Away win probability

Example:

```
Spain vs France

Spain Win : 41%
Draw      : 28%
France Win: 31%
```

---

### 5. Monte Carlo Tournament Simulation

The complete FIFA World Cup 2026 tournament is simulated thousands of times.

Each simulation predicts:

* Group stage standings
* Knockout qualification
* Round of 16
* Quarter-finals
* Semi-finals
* Final
* World Cup Champion

After all simulations, the model estimates every team's probability of winning the tournament.

---

## 📊 Evaluation

The model is evaluated using walk-forward backtesting on historical matches.

Performance metrics include:

* Ranked Probability Score (RPS)
* Reliability Diagrams
* Calibration Curves
* Prediction Accuracy
* Probability Calibration

---

## 📈 Visualizations

The notebook generates multiple visualizations, including:

* Team Elo Rating Rankings
* Match Probability Charts
* Reliability Diagram
* Calibration Curve
* World Cup Winning Probability Rankings

---

## 🛠 Tech Stack

**Programming Language**

* Python

**Libraries**

* NumPy
* Pandas
* Matplotlib
* JSON
* urllib

**Machine Learning & Statistics**

* Elo Rating System
* Dixon-Coles Model
* Poisson Distribution
* Monte Carlo Simulation
* Probability Calibration

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/world-cup-2026-prediction-model.git

cd world-cup-2026-prediction-model
```

### Install dependencies

```bash
pip install numpy pandas matplotlib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
world-cup-2026-prediction-model.ipynb
```

Run all cells sequentially.

---

## 📌 Example Outputs

The notebook can generate:

* Current Elo rankings
* Match outcome probabilities
* Head-to-head predictions
* Group stage simulations
* Knockout bracket predictions
* World Cup champion probabilities
* Team performance charts

---

## 🎯 Applications

This project can be used for:

* Sports analytics
* Football forecasting
* Betting probability research
* Statistical modeling
* Data science portfolios
* Machine learning demonstrations
* Monte Carlo simulation studies

---

## 🔮 Future Improvements

* Live FIFA rankings integration
* Player-level statistics
* Injury and suspension modeling
* Team form weighting
* Expected Goals (xG) integration
* Bayesian rating updates
* Interactive dashboard using Streamlit
* API-based live predictions

---

## 👨‍💻 Author

**Shikhar Srivastava**

If you found this project helpful, consider giving the repository a ⭐.
