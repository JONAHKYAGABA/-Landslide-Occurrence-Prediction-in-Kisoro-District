# 🌍 Landslide Occurrence Prediction in Kisoro District

This project analyzes and predicts landslide occurrences in Kisoro, Uganda, using meteorological and vegetation index data. It combines exploratory data analysis, correlation heatmaps, visual trend inspection, and a logistic regression classifier for binary prediction of landslide events.

---

## 📊 Project Summary

- 📈 Analyzes key environmental variables (e.g., rainfall, humidity, temperature, NDVI)
- 🔁 Visualizes patterns over time using Altair and Matplotlib
- 🔍 Computes correlation heatmaps to study variable interactions
- 🤖 Trains and evaluates a **logistic regression model** for landslide prediction
- ✅ Implements stratified 10-fold cross-validation
- 💾 Saves the trained model using `joblib`

---

## 📁 Dataset

**Input File:**  
`landslide_kisoro.xlsx` — includes columns such as:

- `DATES`: Observation date
- `RELATIVE HUMIDITY`
- `RAINFALL INTENSITY`
- `MAX TEMP`
- `MIN TEMP`
- `WETSPELL`
- `NDVI`
- `OCCURANCE`: Binary label (1 = Landslide, 0 = No Landslide)

---

## 🔍 Features Used

```text
['RELATIVE HUMIDITY', 'RAINFALL INTENSITY', 'MAX TEMP', 
 'MIN TEMP', 'WETSPELL', 'NDVI']
