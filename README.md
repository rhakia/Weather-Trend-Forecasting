# Weather-Trend-Forecasting
A comprehensive project that analyzes global weather trends using time series forecasting (ARIMA, Prophet, Naive), anomaly detection, and advanced climate analytics. Includes spatial visualizations, environmental correlations, and insights derived from a rich real-world weather dataset.


This is a complete weather trend forecasting project analyzing global weather data using various time series models and anomaly detection techniques. This project not only forecasts temperature trends but also performs in-depth climate and environmental analyses across countries and regions.

📁 Files Included

weather_forecasting.ipynb – Jupyter Notebook with all code and outputs (used in Google Colab)

Weather_Trend_Forecasting_Report.docx – Detailed final report of the project

GlobalWeatherRepository.csv – The dataset used

README.md – Project overview and documentation

🔍 Project Features
✅ Data Cleaning & Preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Time Series Forecasting using:

ARIMA

Prophet

Naive (Baseline)

Ensemble (Average of all three)

✅ Anomaly Detection using Isolation Forest

✅ Advanced Analyses:

Climate Trends Across Countries

Air Quality vs. Weather Correlations

Feature Importance

Spatial & Geographical Visualizations

📊 Forecast Model Evaluation (MAE)
Model	Mean Absolute Error (MAE)
ARIMA	0.249
Prophet	1.500
Naive	0.189
Ensemble	0.611
Ensemble forecasting helps reduce individual model limitations and improves robustness.

🧰 Tools & Technologies Used
Programming: Python

Libraries: Pandas, NumPy, Matplotlib, Prophet, Scikit-learn, Seaborn, Statsmodels

Platform: Google Colab

Version Control: GitHub

🌐 Dataset
Source: Global Weather Repository – Kaggle

Contains worldwide city-level weather data including:

Temperature, Humidity, Wind Speed, Air Quality Metrics, UV Index, Sunrise/Sunset, Moon Phase, and more.

📌 Unique Analyses
1. Climate Variation Across Regions
Compared long-term temperature patterns across multiple countries. Trends suggest rising temperatures in certain geographical areas.

2. Environmental Impact
Correlated air quality data (PM2.5, CO, NO₂) with weather conditions like temperature and humidity. Found strong relationships in polluted urban zones.

3. Feature Importance
Applied statistical methods and correlation heatmaps to determine impactful features on temperature. Humidity, PM2.5, and wind speed were most influential.

4. Spatial Analysis
Mapped average temperatures, air quality indexes, and humidity using latitude/longitude heatmaps.

5. Geographical Patterns
Grouped and visualized key parameters (UV index, wind speeds, etc.) across countries and continents.

🚨 Anomaly Detection
Applied Isolation Forest to detect temperature anomalies in the daily time series.

Visualized outliers to identify sudden spikes or drops, validating with real-world climate behavior.

🚀 How to Run
Download the repository or open the .ipynb file using Google Colab

Upload the dataset 

Follow the notebook cells sequentially to run analyses and generate visualizations

🎯 PM Accelerator Mission
This project supports the PM Accelerator initiative by applying machine learning and data science to solve real-world environmental problems and enable data-driven decision-making.

👩‍💻 Author
GitHub: rhakia

Feel free to fork this repository or contribute with improvements!
