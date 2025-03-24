# 📊 Airline Booking Forecast
Forecasting airline booking data using Additive and Multiplicative models with MASE evaluation.

## 🚀 Project Overview
This project predicts airline booking data using two models:
- **Additive Model**: Forecasts bookings by adding the average remaining demand.
- **Multiplicative Model**: Forecasts bookings by dividing cumulative bookings by the average booking rate.

## 📂 Project Structure
.
├── data/                    # Contains CSV files (input data)  
├── notebooks/               # Jupyter Notebooks (.ipynb) for data analysis and forecasting  
├── src/                     # Python scripts (.py) with core logic and model functions  
├── README.md                # Project documentation  
├── .gitignore               # Excludes unnecessary files like __pycache__ and checkpoints  
└── requirements.txt         # List of dependencies for easy installation  

## 📋 Key Results
- **Additive Model MASE:** 0.63
- **Multiplicative Model MASE:** 1.63

## 🔧 Requirements
pip install -r requirements.txt

## 📈 Visual Results
Below is a visual comparison of MASE scores between the Additive and Multiplicative models:
https://github.com/Aashma-T/Airline-booking-forecast/blob/main/booking_curve_by_day_of_week%20(1).png


