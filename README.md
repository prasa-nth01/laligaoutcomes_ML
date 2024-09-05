Project Overview

This project involves predicting the outcomes of La Liga football matches from the 2019-2020 to the 2023-2024 seasons using machine learning models. The dataset used was sourced from football-data.co.uk, containing comprehensive match statistics, team performance metrics, and betting odds. The primary objective is to evaluate and compare the performance of different machine learning classifiers to predict home team wins.

Dataset Description

Source: football-data.co.uk
Coverage: La Liga matches from the 2019-2020 to 2023-2024 seasons.
Key Features:
Match Details: Date, home team, away team, final score.
Performance Metrics: Goals scored, goal difference, points, win/loss streaks.
Betting Odds: Pre-match odds from various bookmakers.
Outcome: Full-Time Result (FTR) - Home Win (H), Draw (D), or Away Win (A).
Machine Learning Workflow

1. Data Collection
Data was collected from various sources including official match reports, betting companies, and sports analytics firms. The data was consolidated to create a comprehensive historical dataset for La Liga.

2. Data Pre-processing
Cleaning: Filtered out irrelevant attributes and handled missing values.
Standardization: Normalized variables to ensure equal treatment.
Feature Engineering: Created dummy variables for categorical data, engineered features like goal difference and last season's rankings.
3. Data Analysis
Exploration: Analyzed feature correlations and visualized match outcomes and variable relationships.
Cleaning: Removed redundant or minimally predictive features based on the correlation matrix.
4. Model Training and Testing
Models Used: Logistic Regression, Random Forest, and XGBoost.
Metrics: Accuracy, F1 Score, Precision, and Recall.
5. Results
Logistic Regression: Accuracy of 0.68, F1 Score of 0.63.
Random Forest: Accuracy of 0.69, F1 Score of 0.64.
XGBoost: Accuracy of 0.67, F1 Score of 0.62.
Random Forest demonstrated the highest overall performance in terms of accuracy, precision, and F1 Score.

Data Files

final_dataset.csv: Processed and cleaned dataset used for modeling.
Tools and Libraries

Python: Programming language used.
Libraries: NumPy, Pandas, Matplotlib, scikit-learn.
Data Ethics

The dataset contains aggregate team-level statistics and does not include personal information, making GDPR regulations and University of Hertfordshire ethical approval unnecessary. The data is open-access and used in accordance with its Creative Commons license.

Figures

Fig. 3.1: Machine Learning Cycle
Fig. 3.2: Correlation Matrix
Fig. 3.3: Distribution of Match Outcomes
Fig. 3.4: Scatter Matrix Visualization
Fig. 4.1: Confusion Matrix for Logistic Regression
Fig. 4.2: Adjusted Confusion Matrix for Logistic Regression
Fig. 4.3: Confusion Matrix with Polynomial Features
Fig. 4.4: Confusion Matrix for Random Forest
Fig. 4.5: Adjusted Confusion Matrix for Random Forest
Fig. 4.6: Confusion Matrix for XGBoost
Fig. 4.7: Confusion Matrix after Tuning Parameters for XGBoost
Fig. 4.8: Comparison of Home Team Prediction Models
Fig. 4.9: Model Accuracy Comparison
References

Tang, Alelyani, and Liu (2014)
Bardhi and Zapirain (2021)
Hucaljuk & Rakipović (2011)
Chen et al. (2014)
Tukey (1977)
For further details, please refer to the project's documentation and source code files.
