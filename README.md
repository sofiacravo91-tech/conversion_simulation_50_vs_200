# conversion_simulation_50_vs_200
conversion_simulation_50_vs_200
# Conversion Variance Simulation — 50 vs 200 Users

## 📌 Objective
Understand how natural statistical variation affects conversion rates depending on sample size, even when the underlying conversion probability remains constant.

## 🧪 Experiment Setup
- Conversion probability (p): 20%
- Scenario A: 50 users
- Scenario B: 200 users
- Method: Monte Carlo simulation using Google Sheets
- Number of simulations: 10,000

## 📊 Key Question
How often do we observe high or low conversion rates purely due to randomness?

## 📈 Findings
- With 50 users, conversion rates fluctuate widely (e.g. 10%–30%).
- With 200 users, conversion rates concentrate tightly around the true mean (20%).
- Large week-over-week swings in small samples are expected and should not trigger premature decisions.

## 🧠 Business Insight
Small sample sizes introduce significant noise in percentage-based KPIs. As volume increases, variance decreases, making trends more reliable for product and business decisions.

## 🛠 Tools Used
- Google Sheets
- Binomial distribution simulation
- Histograms for visualization

## 📂 Files
- `/sheets/conversion_simulation_50_vs_200.xlsx`: simulation data
- `/images/`: histograms comparing both scenarios
