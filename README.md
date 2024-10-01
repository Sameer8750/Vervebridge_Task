# Predictive Maintenance for Industrial Equipment Using IoT Data.


![Picture1555](https://github.com/user-attachments/assets/5f732aa4-995b-47e9-8c6a-760fd6f8d3bc)


## 📊 Dataset Overview:

The Predictive Maintenance project focuses on using IoT data to monitor industrial equipment performance and predict when maintenance is needed. The dataset includes information on temperature, vibration, pressure, RPM, and an indicator of maintenance requirements, along with calculated metrics such as changes in temperature and vibration over time.

## Key Features of the Dataset:

- Timestamp: Time of the sensor reading.
- Temperature (°C): Temperature data in Celsius.
- Vibration (mm/s): Vibration data in millimeters per second.
- Pressure (Pa): Pressure data in Pascals.
- RPM: Revolutions per minute.
- Maintenance Required: A binary column indicating whether maintenance is required (1) or not (0).
- Temp_Change: Change in temperature since the previous reading.
- Vib_Change: Change in vibration since the previous reading.
- Temperature_Mean: Average temperature recorded up to the current timestamp.
- Vibration_Mean: Average vibration recorded up to the current timestamp.
- Pressure_Mean: Average pressure recorded up to the current timestamp.
- RPM_Mean: Average RPM recorded up to the current timestamp.

## 🧪 Exploratory Data Analysis (EDA):

EDA was conducted to uncover patterns and insights within the dataset:

- Temperature and Vibration Trends: Analyzed changes in temperature and vibration over time.
- Maintenance Needs: Examined how temperature, vibration, and pressure influence the need for maintenance.
- Pressure Analysis: Investigated how pressure fluctuations affect equipment performance.
- RPM Behavior: Explored the RPM data and its role in equipment failure.

## 🚀 Machine Learning for Predictive Maintenance:

In addition to EDA, we applied advanced machine learning techniques to predict equipment failures and analyze anomalies using:

- Scikit-learn: Used for feature selection and building simple predictive models like Logistic Regression and Random Forest.
- XGBoost: Applied to capture complex patterns in equipment failures and achieve high accuracy in failure prediction.
- LSTM (Long Short-Term Memory): Employed for time-series forecasting, detecting anomalies, and predicting future maintenance requirements by learning from historical data patterns.
- ARIMA (AutoRegressive Integrated Moving Average): Used for time-series modeling to predict trends in temperature, vibration, and pressure over time, helping us forecast equipment behavior.

## 🧰 Tools Used :

- Python: For data manipulation and analysis.
- Pandas, NumPy: For data cleaning, processing, and numerical operations.
- Matplotlib, Seaborn: To generate insightful visualizations.
- Scikit-learn: For implementing machine learning models.
- XGBoost: For boosting model performance.
- LSTM, ARIMA: For time-series analysis and forecasting.

## 💡 Insights:

- Temperature Fluctuations: Significant temperature spikes correlate with increased maintenance needs.
- Vibration Analysis: Sudden changes in vibration are key indicators of potential equipment failures.
- Machine Learning Models: XGBoost and LSTM provided the most accurate predictions for maintenance requirements, helping optimize predictive strategies.

## 🛠️ Setup and Usage
<br>

**1. Clone the repository :**
```bash
  https://github.com/Sameer8750/Vervebridge_Task
```

**Install Dependencies:**

To run the analysis, install necessary packages:
```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost tensorflow statsmodels

```
**Running the Analysis:**

- Open the Jupyter notebook Predictive_Maintenance_analysis.ipynb.
- Run each cell step-by-step to clean the data, conduct EDA, and implement machine learning models.



## 📬 Contact Information

For inquiries or further discussion on this project, feel free to reach out:

- Sameer Shinde
- Email: sameershinde1621@gmail.com

## Explore the power of IoT-driven predictive maintenance analytics and improve equipment uptime and operational efficiency with this comprehensive solution! 🌐🔧📈


