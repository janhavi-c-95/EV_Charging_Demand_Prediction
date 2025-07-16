# 🔋 EV Adoption Forecasting

Forecasting electric vehicle (EV) adoption to support infrastructure planning and sustainability initiatives.

---

## 📘 Overview

As electric vehicle (EV) adoption accelerates, cities and states must anticipate infrastructure needs—especially charging stations. This project builds a forecasting model to predict EV adoption in Washington State using historical vehicle registration data from 2017 to 2024.

Using time series and machine learning models, the project provides forecasts of EV growth to assist urban planners, policy makers, and utility providers in long-term infrastructure development.

---

## 📦 Dataset

- **Source**: Washington State Department of Licensing (DOL)
- **Date Range**: January 2017 – February 2024
- **Frequency**: Monthly
- **Granularity**: By County and Vehicle Type

### Key Features:
| Column | Description |
|--------|-------------|
| `Date` | Monthly registration date |
| `County` | County where the vehicle is registered |
| `State` | State where the vehicle is registered |
| `Vehicle Primary Use` | Passenger or Truck |
| `Battery Electric Vehicles (BEVs)` | Fully electric vehicle count |
| `Plug-In Hybrid Electric Vehicles (PHEVs)` | Hybrid EVs count |
| `Electric Vehicle Total` | Sum of BEVs and PHEVs |
| `Non-Electric Vehicle Total` | All non-EVs |
| `Total Vehicles` | All registered vehicles |
| `Percent Electric Vehicles` | Percentage of EVs among total vehicles |

---

## 🎯 Project Goals

- Clean and preprocess the EV dataset
- Explore historical trends in EV adoption
- Engineer relevant time-based and categorical features
- Build a regression-based forecasting model
- Predict EV adoption trends in the future
- Visualize and interpret forecast results

---
