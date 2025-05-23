# 🌾 Crop-Recommendation-System-Python-PowerBI
A Crop Recommendation System using Python (Random Forest Classifier) and Power BI for predicting suitable crops based on soil and weather conditions, with  data visualizations.


This project uses machine learning (Random Forest Classifier) to recommend the most suitable crop based on soil and environmental conditions, and presents results visually using a Power BI dashboard.

---

## 📁 Files Included

- `Crop_Recommendation.csv`: The original dataset used for model training. It contains features such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall, along with the corresponding crop label.
  
- `Crop_prediction.csv`: A CSV file containing model predictions on test data. It includes all input features and the recommended crop, and is used for visual analysis in the Power BI dashboard.
  
- `Crop Data Analysis.ipynb`: Jupyter Notebook used to perform:
  - Data preprocessing and cleaning
  - Exploratory Data Analysis (EDA)
  - Model training using Random Forest Classifier
  - Predictions on test data
  - Export of predicted results for Power BI

- `Crop recommendation PowerBI Dashboard.pbix`: A Power BI dashboard that includes:
  - Input condition filters (N, P, K, Temperature, Humidity, pH, Rainfall)
  - Predicted crop visualized by conditions
  - Dynamic visuals and slicers for better analysis

- `Analysis Report`: A summary report (PDF) highlighting the objective, methodology, key observations from the EDA, model performance, and insights derived from the dashboard.
---

## ⚙️ Tools Used

- **Python** (pandas, seaborn, scikit-learn, matplotlib)
- **Power BI** (for interactive dashboard)

---

## 📌 Purpose

To help farmers or agricultural analysts identify the most suitable crop to grow based on specific soil and climate data.

---

## 📊 Outcome

An integrated solution where:
- Python performs the core prediction using machine learning.
- Power BI makes it visually insightful and interactive.

---


