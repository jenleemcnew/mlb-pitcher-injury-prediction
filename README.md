# MLB Pitcher Injury Prediction

## Overview
A machine learning project analyzing Major League Baseball (MLB) pitcher performance 
and injury data from 2008 to 2024, with a focus on Tommy John surgery prediction 
and player injury return timelines. This project combines statistical analysis, 
data scraping, and predictive modeling to help identify injury risk factors and 
inform player management decisions.

---

## Key Objectives
- Predict the likelihood of Tommy John surgery based on pitcher workload and pitch count data
- Estimate injury return timelines across multiple injury types
- Identify performance trends before and after injury events

---

## Machine Learning Approach
- **Model:** Random Forest Classifier
- **Optimization:** GridSearchCV hyperparameter tuning (108 combinations, 5-fold cross-validation)
- **Initial Accuracy:** 60%
- **Optimized Accuracy:** 70%
- **Target Variable:** Tommy John Surgery occurrence (Yes/No)

---

## Key Findings
- High pitch counts show a clear correlation with increased Tommy John surgery risk
- Hyperparameter tuning via GridSearchCV significantly improved model predictive power
- Recovery timelines vary meaningfully across injury types, with Tommy John 
  surgeries averaging 12–18 months before return to play

---

## Tech Stack
- Python (Pandas, NumPy, Scikit-learn, TensorFlow, Matplotlib, Seaborn, hvPlot)
- Beautiful Soup (web scraping)
- Jupyter Notebook
- VS Code
- Microsoft Excel

---

## Repository Structure
| Folder | Description |
|--------|-------------|
| `Cleaning files/` | Data cleaning and preprocessing scripts |
| `Data/` | Source and cleaned datasets |
| `Drivers/` | Web scraping drivers |
| `Machine Learning/` | ML model notebooks and scripts |
| `PNG/` | Generated visualizations |
| `Visuals code/` | Visualization scripts |

---

## Data Sources
- [Baseball Savant](https://baseballsavant.mlb.com)
- [MLB Pitching Stats](https://www.mlb.com/stats/pitching)
- [FanGraphs Injury Report](https://www.fangraphs.com/roster-resource/injury-report)
- [Sean Lahman Baseball Database](http://seanlahman.com/)
- [SABR](https://sabr.org/sabermetrics/data)
- [Retrosheet](https://www.retrosheet.org/)

---

## Contributors
Abigail Parsley · Jack Yeager · Jennifer McNew · Josh Still · Kayli Smith ·
Lisa Ybarra · Thierno Diallo · Sylvia Turner

*SMU Data Science Certificate Program — Project 4*
