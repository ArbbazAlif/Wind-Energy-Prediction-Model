# 🌬️ Wind Energy Prediction using Multiple Linear Regression

This project demonstrates how to use a **Multiple Linear Regression** model to predict wind energy generation based on historical data from a wind turbine. The goal is to analyze the relationship between wind speed, wind direction, and the power output of a wind turbine.

## 📊 Dataset Overview

The dataset includes 10-minute interval data and the following features:

- `Date/Time`: Timestamp of the observation
- `LV ActivePower (kW)`: Actual power generated
- `Wind Speed (m/s)`: Wind speed at the turbine’s hub height
- `Theoretical_Power_Curve (KWh)`: Manufacturer-specified expected output
- `Wind Direction (°)`: Wind direction at the hub height

## 🧠 Objective

- Explore wind turbine data
- Apply feature engineering
- Train and evaluate a Multiple Linear Regression model
- Visualize predictions vs actual power output

## 🛠️ Tools and Libraries

- **Python 3**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** for visualizations
- **Scikit-learn** for model training and evaluation

## 📈 Methodology

1. **Data Preprocessing**: Load and clean the dataset
2. **Exploratory Data Analysis**: Understand distributions, correlations, and feature importance
3. **Modeling**: Fit a multiple linear regression model
4. **Evaluation**: Use metrics such as R² and RMSE to assess performance
5. **Visualization**: Plot actual vs predicted energy outputs

## 📎 How to Run

```bash
git clone https://github.com/yourusername/wind-energy-prediction.git
cd wind-energy-prediction
pip install -r requirements.txt
jupyter notebook Wind_Energy_Prediction.ipynb
```

## 📌 Results

- Achieved high accuracy using simple regression
- Insights into how wind speed and direction influence turbine performance

## 📂 File Structure

```
Wind_Energy_Prediction.ipynb   # Main notebook
README.md                      # Project documentation
requirements.txt               # Python dependencies
```

## 📃 License

This project is licensed under the MIT License.
