# Analysis and Prediction of Air Quality in India

## Overview

The **Analysis and Prediction of Air Quality in India** project utilizes extensive data from the Central Pollution Control Board to analyze, visualize, and predict air quality trends across major cities in India. By leveraging advanced deep learning and statistical models, the project provides valuable insights into pollution levels, key contributors, and potential future scenarios, empowering policymakers and researchers with actionable information.

## Objectives

1. **Data Analysis**: 
   - Identified trends and patterns in Air Quality Index (AQI) across major Indian cities.
   - Analyzed the impact of the COVID-19 lockdown on air quality by comparing scenarios with and without the lockdown.
   - Highlighted major pollutants such as PM2.5 and NOx as dominant contributors to poor air quality.

2. **Forecasting**:
   - Predicted air quality for 2021 and 2022 using state-of-the-art time-series forecasting algorithms.
   - Benchmarked traditional models like ARIMA and ETS against deep learning models such as LSTM and Prophet.

3. **Visualization**:
   - Developed an interactive dashboard using the Dash framework to provide city-specific insights, real-time updates, and comparative analysis.

---

## Key Features

### Data Sources and Preprocessing
- **Data Source**: Central Pollution Control Board (India).
- **Preprocessing**: Extensive cleaning and transformation of raw data using Python libraries like `BeautifulSoup` and `Selenium`.

### Models Used
1. **ARIMA**: Effective for linear time-series patterns.
2. **Exponential Smoothing (ETS)**: Addressed short-term trend variations.
3. **Prophet**: Handled seasonal trends and holidays effectively.
4. **LSTM (Long Short-Term Memory)**: 
   - Best performance due to its ability to capture long-term dependencies in AQI trends.
   - Achieved lower RMSE compared to other models.

### Dashboard Features
- **City-Wise Analysis**: Explore AQI data for over 20 major Indian cities with a focus on emissions and trends.
- **Real-Time Forecasting**: Generate accurate predictions for AQI using the best-performing model.
- **Scenario Comparison**: Visualize and compare AQI levels during pre-lockdown and lockdown periods.
- **Safe vs. Unsafe Cities**: Identify cities with the highest and lowest AQI emissions dynamically.
- **Geographic Mapping**: Interactive maps using Google Maps to visualize pollutant distribution across cities.

---

## Significance

- **Impact of Lockdown**: Demonstrated a significant improvement in air quality during the COVID-19 lockdown, highlighting the influence of reduced human activities.
- **Policy Insights**: 
  - Correlations between air quality and health risks.
  - Supports sustainable urban planning by providing key insights on pollutant trends.
- **Advancing Research**:
  - Integrated advanced deep learning applications for dynamic forecasting.
  - Provided an open-source, user-friendly tool for researchers and policymakers.

---

## Novelty
- **Interactive Dashboard**: An accessible platform for non-technical users to explore air quality data.
- **Comparative Benchmarking**: Compared traditional models with deep learning algorithms to identify the most accurate forecasting methods.
- **Dynamic Scenarios**: Unique “What if” analysis to forecast air quality without lockdown interventions.

---

## Technical Stack
- **Data Processing**: Python (Pandas, NumPy, Selenium, BeautifulSoup)
- **Modeling**: ARIMA, ETS, LSTM, Prophet
- **Visualization**: Plotly, Matplotlib, Geoplot
- **Dashboard Development**: Dash framework

---

## Results and Impact
1. **Data Insights**:
   - Drastic AQI improvements during lockdown periods.
   - Identified dominant pollutants and city-specific emissions.
2. **Model Performance**:
   - LSTM showed the lowest RMSE, making it the best-performing model for long-term forecasting.
3. **Public Awareness**:
   - Empowered communities and researchers with real-time AQI trends and forecasts.
   - Enhanced public understanding of air quality challenges and health implications.

---

## How to Use
1. Clone the project repository:  
   ```bash
   git clone https://github.com/lucidopus/AQI-Prediction.git