# Weather-Trend-Forecasting
Project Overview

This project explores global weather patterns using the "Global Weather Repository" dataset, which includes daily weather data for cities worldwide. The primary goals are to:

Clean and preprocess the data to ensure usability.

Conduct exploratory data analysis (EDA) to identify trends, correlations, and anomalies.

Develop and evaluate forecasting models to predict weather trends.

Perform advanced analyses, such as anomaly detection, climate impact studies, and spatial analysis.

Methodology

1. Data Cleaning and Preprocessing

Missing Value Handling:

Replaced missing numeric values with the median to maintain distribution integrity.

Replaced missing categorical values with the mode to retain common patterns.

Outlier Detection and Handling:

Applied the Interquartile Range (IQR) method to cap outliers in key features like temperature and precipitation.

Normalization:

Scaled numeric data to a [0, 1] range using MinMaxScaler for consistent analysis.

2. Exploratory Data Analysis (EDA)

Temperature Trends:

Visualized seasonal patterns and identified long-term temperature trends.

Precipitation Trends:

Analyzed global precipitation fluctuations.

Correlation Analysis:

A heatmap revealed significant relationships among temperature, precipitation, and air quality metrics.

3. Forecasting Models

ARIMA:

A time-series forecasting model used to predict temperature trends.

Performance evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

Prophet:

Robust model for handling seasonal and long-term trends in temperature.

Gradient Boosting Regressor:

Predictive model used for temperature forecasting with feature-rich datasets.

Ensemble Model:

Combined predictions from ARIMA, Prophet, and Gradient Boosting using averaging to enhance accuracy.

4. Advanced Analyses

Anomaly Detection:

Utilized Isolation Forest to identify anomalous temperature data points.

Climate Analysis:

Grouped data by region and year to study long-term trends and variations.

Environmental Impact:

Analyzed correlations between air quality metrics (e.g., PM2.5) and weather conditions.

Global Trends:

Seasonal temperature variations were consistent, but anomalies indicated potential climate changes.

Forecasting Accuracy:

The ensemble model outperformed individual models by leveraging their strengths.

Air Quality Correlations:

High correlations between PM2.5 levels and temperature suggested significant environmental impacts on weather patterns.

Future Work

Integrate additional features like wind speed and humidity to improve model accuracy.

Develop region-specific models to provide localized weather predictions.

Expand spatial analysis to include additional environmental and climatic factors.

GitHub Repository

The complete code, dataset, and visualizations for this project are available on GitHub. The repository includes:

Notebook: Detailed steps for data preprocessing, analysis, and model implementation.

Visualizations: Graphs and maps highlighting key trends and insights.

Documentation: Detailed explanations of the methodology and results.

[https://github.com/sanikadeshmukh/Weather-Trend-Forecasting]

Contact Information

For further inquiries or collaboration opportunities, please contact:

Name: Sanika Deshmukh

Email: sanikadeshmukh178@gmail.com

LinkedIn: Sanika Deshmukh

