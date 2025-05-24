# 🍽️ HelloFresh – Food Demand Forecasting (Real Data)

This project forecasts weekly recipe demand for HelloFresh-style meal delivery, using real-world historical order data. It demonstrates how time series models like Facebook Prophet and ARIMA can help logistics teams plan inventory and reduce food waste.

---

## 📌 Problem Statement

HelloFresh needs to accurately forecast recipe demand each week to:

- Avoid food overstocking or shortages
- Optimize delivery logistics and kitchen planning
- Reduce waste and improve customer satisfaction

---

## 📊 Dataset

We use a real dataset inspired by the [Meal Demand Forecasting dataset from Kaggle](https://www.kaggle.com/datasets/fabiendaniel/meal-demand-forecasting), cleaned and focused on one high-demand meal:

- `week`: Weekly time index (2015–2016)
- `meal_id`: ID of the meal
- `num_orders`: Total orders for that meal in the week

---

## 🧠 Models Used

### 🔮 Facebook Prophet
- Automatic trend detection
- Handles seasonality well
- Easy to interpret

### 🔁 ARIMA (AutoRegressive Integrated Moving Average)
- Classical time series model
- Works well with structured, stationary data

---

## 🧪 Evaluation Metrics

| Model   | MAE   | RMSE  |
|---------|-------|--------|
| Prophet | 5.00  | 5.91   ✅ Best |
| ARIMA   | 16.52 | 17.94  ⚠️ Higher error |

> Prophet performed better on this dataset due to its flexibility with trends and smaller data volume.

---

## 📈 Visualizations

- Actual vs predicted orders
- Prophet forecast chart
- ARIMA forecast comparison

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Matplotlib
- Facebook Prophet
- pmdarima (ARIMA)
- Google Colab

---

## 📁 Project Structure


