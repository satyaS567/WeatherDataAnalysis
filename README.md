🌦️ Weather Data Analysis Project


This project provides an in-depth Exploratory Data Analysis (EDA) and predictive modeling on a weather dataset using Python.
It includes data cleaning, preprocessing, visualization, statistical insights, and linear regression modeling to uncover meaningful weather patterns and relationships between variables like temperature, humidity, and wind speed.

🧰 Technologies Used

  1. Python 3.x

  2. Libraries:

  3. pandas – data manipulation

  4. numpy – numerical computations

  5. matplotlib, seaborn – data visualization

  6. scipy.stats – statistical analysis

  7. scikit-learn – machine learning model (Linear Regression)

🚀 Key Steps in the Project

1️⃣ Data Loading & Inspection

  Loads dataset (weatherHistory.csv)

  Displays shape, columns, missing values, and summary statistics

2️⃣ Data Cleaning & Preprocessing

  Renames inconsistent column headers

  Converts date column to datetime

  Removes duplicates and missing timestamps

  Ensures numeric data types are consistent

3️⃣ Feature Engineering

  Extracts Year, Month, Day, and Hour

  Creates a Season feature based on month

4️⃣ Exploratory Data Analysis (EDA)

  Distribution plots for Temperature and Humidity

  Relationship between temperature and humidity

  Correlation heatmap for feature relationships

  Seasonal boxplots and weather summaries

5️⃣ Time Series Analysis

  Monthly and daily temperature trends

  Seasonal variations visualized using line charts

6️⃣ Outlier Detection & Statistical Insights

  Identifies temperature outliers using Z-Score

  Calculates Skewness, Kurtosis, and correlation metrics

7️⃣ Predictive Modeling

  Builds a Linear Regression model using:

  Independent Variables: Humidity, Wind_Speed_km_h

  Target Variable: Temperature_C

  Evaluates model using:

  R² Score

  RMSE (Root Mean Squared Error)

8️⃣ Key Insights

  ✅ Temperature shows strong seasonal variation (warmest mid-year)
  
  ✅ Humidity has a negative correlation with temperature
  
  ✅ Wind speed shows weak correlation with temperature
  
  ✅ Model gives moderate accuracy in temperature prediction

📊 Example Visualizations

  Temperature Distribution

  Humidity Distribution

  Temperature vs Humidity Scatterplot

  Correlation Heatmap

  Monthly Temperature Trend

  Seasonal Boxplot

  (Plots generated using Matplotlib and Seaborn)

⚙️ How to Run the Project

🔧 1. Clone this repository

  git clone https://github.com/satyaS567/WeatherDataAnalysis.git

  cd WeatherDataAnalysis

📦 2. Install dependencies
  pip install -r requirements.txt

▶️ 3. Run the script
  python weather_analysis.py

📈 Sample Model Output

--- Linear Regression Model ---

R² Score: 0.742

RMSE: 1.86

Coefficients: {'Humidity': -12.57, 'Wind_Speed_km_h': 0.22}

🎯 Conclusion

This project demonstrates how data analysis and machine learning can uncover trends in weather patterns.
It highlights seasonal changes, humidity-temperature relationships, and builds a simple predictive model to forecast temperature using climatic parameters.

🧠 Future Enhancements

Apply advanced regression models (Random Forest, XGBoost)

Add temperature anomaly detection

Build an interactive dashboard using Plotly or Power BI

Deploy model as a Flask web app for live prediction

👨‍💻 Author

Satya Prakash Sharma

