# Fantasy Team Selection System Using Machine Learning & Deep Learning

## Problem Statement
This project aims to predict the performance of cricket players using historical IPL ball-by-ball data and recommend an optimal fantasy team based on predicted fantasy points.

---

## Objective
To build a data-driven system that selects the best fantasy cricket team using machine learning and deep learning techniques.

---

## Dataset Details
- Dataset: IPL Ball-by-Ball Data
- Records: 83,000+
- Type: Tabular Data
- Features: batter, runs, wickets, boundaries, balls faced, etc.

---

## Project Pipeline
Data Collection → Data Cleaning → Feature Engineering → Model Training (ML) → Best Model Selection → Deep Learning Model → Comparison → Fantasy Team Selection

---

## Feature Engineering
- Aggregation (player-level statistics)
- Feature Creation:
  - Total Runs
  - Balls Faced
  - Boundaries
  - Strike Rate
- Target Variable:
  - Fantasy Points

---

## Machine Learning Models Used
- Linear Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest (Best Model)
- Gradient Boosting (Ensemble)

---

## Deep Learning Model
- Artificial Neural Network (ANN)
- 2 Hidden Layers (ReLU Activation)
- Optimizer: Adam
- Loss Function: Mean Squared Error

---

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Optimization Techniques
- Feature Scaling (Standardization)
- Hyperparameter Tuning (GridSearchCV)
- Ensemble Learning
- Cross Validation

---

## Final Output
- Predicted fantasy points for each player
- Top 11 players selected as the final fantasy team

---

## How to Run the Project
1. Open the notebook in Google Colab
2. Upload dataset (all_matches_ball_by_ball1.csv)
3. Run all cells
4. View results and final fantasy team

---

## Files in Repository
- Fantasy_Team_Selection.ipynb
- all_matches_ball_by_ball1.csv
- final_fantasy_team.csv
- model_comparison_results.csv
- processed_player_stats.csv

---

## Team Members
- Priya
