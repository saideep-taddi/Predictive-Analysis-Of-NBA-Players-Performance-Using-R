# Predictive-Analysis-Of-NBA-Players-Performance-Using-R
Predictive Analysis Of NBA Player Performance Using R
# Overview
This project analyzes and predicts NBA players' performance using various machine learning models in R. The dataset includes key player statistics such as points per game, assists, rebounds, and efficiency ratings to predict future performance trends.
The project is implemented in R Markdown and presents a structured analysis including data preprocessing, exploratory data analysis (EDA), feature engineering, and model building.

# Objectives
Analyze NBA player performance based on historical data.
Use regression models to predict a player’s future performance.
Identify key factors that contribute to high performance in the league.
Visualize player trends and comparisons using ggplot2.

# Dataset
The dataset contains NBA player statistics, including:
Basic Player Stats: Points per game, rebounds, assists, steals, and blocks.
Efficiency Metrics: Field goal percentage, free throw percentage, three-point percentage.
Advanced Stats: Player efficiency rating (PER), win shares, usage rate.

# Key Features of the Project
 Data Cleaning & Preprocessing: Handling missing values, outliers, and feature engineering.
 Exploratory Data Analysis (EDA): Insights into trends using data visualization tools like ggplot2.
 Machine Learning Models:
Linear Regression
Random Forest
Decision Trees
 Model Performance Evaluation: Using metrics like Mean Squared Error (MSE) and R-Squared to assess model accuracy.

# Technologies Used
Libraries:
tidyverse (Data manipulation and visualization)
ggplot2 (Data visualization)
caret (Machine learning model training)
randomForest (Random forest model)
rpart (Decision tree model)
shiny (For interactive visualizations)
knitr (For generating reports)

# How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/NBA-Player-Performance-Prediction.git
cd NBA-Player-Performance-Prediction
2. Install Dependencies in R
   install.packages(c("tidyverse", "ggplot2", "caret", "randomForest", "rpart", "shiny", "knitr"))
3. Run the Analysis
Open RStudio and run the R Markdown (.Rmd) file to generate insights.
rmarkdown::render("Predicting-NBA-Players-Performance-Using-R.Rmd")

# Results & Findings
Scoring efficiency is highly correlated with win shares and PER.
Players with higher usage rates tend to have higher scoring outputs but lower efficiency.
The random forest model outperformed linear regression in predicting player performance.

# Future Enhancements
Integrate real-time NBA data for live predictions.
Use deep learning models to improve accuracy.
Deploy as a Shiny App for interactive analysis.
   
   
