# ⚽ European Football Analytics & Ballon d'Or Predictor

An end-to-end sports analytics project exploring data engineering and predictive modeling to identify talent impact beyond standard box-score statistics.

🔗 **[View the Live Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/harsha.subramanian/viz/EuropeanTop5LeaguesFootballAnalytics2026/BallondOrvsRaw?publish=yes)**

## 📊 Project Philosophy
I built this out of a personal curiosity: **Standard stats (Goals/Assists) favor players on elite teams.** I wanted to see if I could build a system to identify "Unsung Heroes"—players like Deniz Undav—who perform at an elite level but are often overlooked because they play for smaller teams or don't win titles.

## 🚀 Analytical Features
This project moves beyond raw stats to provide deep-dive scouting insights:

*   **Raw Stats vs. Ballon d'Or Predictor:** I compared raw output (Goals/Assists) against a custom-weighted **Master Predictor Score** to see which players are statistically "over-performing" their team’s success.
*   **The "Carry Factor":** A custom metric designed to identify players who essentially "carry" their team's production. This helps teams scout undervalued players who could "ball out" if transferred to a bigger system.
*   **Positional Podiums:** I created custom, role-specific weightings for different positions. This ensures we aren't unfairly comparing a defensive midfielder's impact to a striker's.
*   **Kopa Trophy Predictor:** A dedicated U-21 power ranking to identify the next generation of global stars.
*   **Global Power Map:** A talent scouting tool visualizing which countries are producing the most top-tier talent across Europe's Top 5 leagues.

## 📸 Dashboard Snapshots
![Dashboard 1](https://github.com/user-attachments/assets/fda7c2d4-e0b0-43d5-ae16-86a4d17313f3)
![Dashboard 2](https://github.com/user-attachments/assets/9b22075e-4842-47ce-9026-aa4b8944d601)

## 🛠️ Tech Stack
*   **Visualization:** Tableau Public
*   **Data Pipeline:** Python (Pandas/SQLAlchemy), MySQL
*   **Concepts:** Metric Engineering, Custom Weighted Scoring, Exploratory Data Analysis, Talent Scouting Logic

---
*Note: This is an ongoing learning project. I'm actively experimenting with weightings and metrics to improve the predictive accuracy. If you have any thoughts on how to better quantify "player impact," I’d love to hear your feedback!*
