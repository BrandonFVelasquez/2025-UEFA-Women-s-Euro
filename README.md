# 🏆 UEFA Women’s Euro 2025 Final Simulation  
### Predicting Spain vs England Outcomes Using Poisson Regression & Monte Carlo Simulation

![Dashboard Preview](Womens Euro 2025 Analysis Project\Data\🏆 UEFA Women's Euro 2025 Final Simulation_ Spain vs England Outcome Prediction via Poisson Regression & Simulation.png)

## 📌 Project Overview
This project simulates the potential outcome of the **UEFA Women’s Euro 2025 Final** between **Spain** and **England**, using real team statistics and statistical modeling.

Using **Poisson regression**, team-specific offensive and defensive metrics were modeled to simulate goal scoring. The match was then run through **10,000 Monte Carlo simulations** to predict:
- Most likely scorelines
- Win probabilities after 90 minutes
- Extra time and penalty outcomes

---

## 🎯 Business Task
**Objective**: Help stakeholders (teams, analysts, fans) understand the most probable outcomes of the final using historical performance data and statistical modeling.

---

## 📊 Key Results

| Metric | Spain | England |
|--------|-------|---------|
| Total Win Probability | **60.03%** | 39.97% |
| 90-Minute Win % | 50.62% | 32.49% |
| Extra Time Win % | 6.68% | 4.92% |
| Penalty Shootout Win % | 2.73% | 2.56% |

- Most frequent scoreline: **Spain 3 - England 2**
- Simulation ran for **10,000 matches** using team attacking/defensive metrics

---

## ⚙️ Methods Used
- Python (Pandas, NumPy, Statsmodels, Matplotlib)
- Poisson Regression for goal modeling
- Monte Carlo Simulation (10,000 runs)
- Tableau for final visualization

---

## 📂 Project Structure
📁 UEFA_Womens_Euro_2025_Simulation/
├── data/
│ ├── overview_stats.csv
│ ├── match_outcomes.csv
│ └── scorelines.csv
├── uefa_womens_euro_prediction.py
├── dashboard.png
└── README.md


---

## 📈 Visualizations

Dashboard built in **Tableau**, showing:
- Top 10 scorelines
- Win % after 90 mins, ET, Penalties
- Outcome breakdown by method of victory

> You can view the full dashboard [here](#) *(Replace with public Tableau link if available)*

---

## 🧠 Future Work
- Include more teams for a full tournament simulation
- Calibrate penalty shootout strengths based on historical trends
- Integrate Elo or FIFA rankings dynamically

---

## 🧪 How to Run This Project

1. Clone the repo  
   `git clone https://github.com/yourusername/euro2025-final-simulation.git`

2. Install requirements  
   ```bash
   pip install pandas numpy statsmodels matplotlib
    python uefa_womens_euro_prediction.py