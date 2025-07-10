# ⚽ Egyptian-League-Analytics

A data analytics and forecasting project built using **Power BI**, **Python**, and **Excel**, based on 10 seasons of the Egyptian Premier League (2015–2024). This project provides comprehensive insights into team and player performance, market value trends, and predictive modeling for future outcomes.

## 📊 Overview

This project cleans, models, analyzes, and visualizes football data spanning 10 seasons using a dual star schema (match-level and team-level). It provides interactive dashboards, KPIs, and forecasts that can help clubs, analysts, and fans understand past trends and anticipate future performance.

## 📁 Dataset Summary

The dataset was compiled and enhanced from multiple Excel files:
- Match results
- Goals and assists
- Referees and stadiums
- Coaches (nationality, changes, exit reasons)
- Player squads (positions, nationalities, market values)
- Final standings per season

## 🛠 Tools & Technologies
- **Power BI**: Dashboard creation, DAX measures, visualizations
- **Python (scikit-learn)**: Predictive modeling (Linear Regression, Random Forest)
- **Excel**: Data wrangling and integration
- **DAX**: 40+ custom measures for advanced insights

## 🧠 Project Features

### 🔹 Data Modeling
- Created a clean and scalable dual **star schema** (match-level & team-level)
- Handled inactive relationships using DAX for team-specific stats (home vs away)
- Integrated additional data (squads, coaches, standings) into the model

### 🔹 KPI Development
- Calculated key metrics:
  - Goals scored/conceded (home/away/total)
  - Points breakdown (home/away/total)
  - Win/draw/loss counts
  - Squad market value and size
  - Player and coach nationalities

### 🔹 Dashboards & Visualizations
- **League Overview**: Final standings, goals timeline, top scorers & assisters
- **Team Reports**: Team-specific stats, home vs away breakdowns
- **Stadiums & Referees**: Appearances, match counts, impact analysis
- **Coach Insights**: Nationality trends, coaching changes, final-season coaches
- **Market Value**: Team value trends, league-wide comparison
- **Forecasts**: Predicted next-season points & team valuations

### 🔹 Forecasting (Python)
- Trained Linear Regression and Random Forest models on historical team data
- Predicted:
  - Points per team for upcoming season
  - Estimated club market values for the next 5 years
- Visualized actual vs predicted in Power BI
## 🚀 Future Improvements
- Incorporate player-level time-series performance tracking
- Enhance prediction with more advanced ML models (e.g., XGBoost, LSTM)
- Deploy interactive version of dashboards online (e.g., Power BI service or Streamlit)
**Ayman Mahmoud**  
📧 ayman.anaylst@gmail.com  
📍 Giza, Egypt
🔗 [LinkedIn Profile](#) *(https://www.linkedin.com/in/ayman-mahmoud-8b2287235/))*;
