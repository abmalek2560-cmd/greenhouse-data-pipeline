# greenhouse-data-pipeline
Python-based data processing and statistical analysis pipeline for the Greenhouse Shrivan Iran Dataset, featuring environmental monitoring, trend visualization, and correlation studies
# 🌿 Greenhouse Environmental Monitoring & Data Analysis

This repository contains a comprehensive data processing and statistical analysis pipeline for the **Greenhouse Shrivan Iran Dataset**. The project explores internal and external environmental conditions, temperature differences, relative humidity variations, and sensor-reading patterns using Python in Google Colab.

---

## 📊 Dataset Overview
* **Total Records:** 130,195 rows
* **Time Span:** December 19, 2023 – May 25, 2024
* **Parameters Analyzed:** 
  * Inside and Outside Temperature (`MeanInsideTemp`, `OutsideTemp`)
  * Internal and External Relative Humidity (`AVGHumidityInside`, `HumidityOutside`)
  * Sensor Readings (`L1`, `WS1`, and coded variables `F`, `H`, `W`)

---

## 📈 Key Findings & Highlights
* **Temperature Analysis:** The average inside greenhouse temperature was **21.32°C**, compared to an outside average of **8.78°C**, maintaining an average daily temperature difference of **12.13°C**.
* **Humidity Dynamics:** Mean inside relative humidity was recorded at **63.90%**, while outside relative humidity averaged **74.21%**.
* **Statistical Correlations:** 
  * Strong positive correlation between outside and inside temperature ($r = 0.8591$).
  * Positive association between daily mean light readings (`L1`) and inside temperature ($r = 0.6955$).
  * Negative association between inside temperature and inside relative humidity ($r = -0.6683$).

---

## 🛠️ Tech Stack & Libraries
* **Python**
* **Pandas & NumPy** (Data cleaning & manipulation)
* **Matplotlib & SciPy** (Visualization & Pearson correlation analysis)
* **Google Colab** (Development environment)

---

## 📉 Generated Visualizations
The analysis pipeline automatically generates and saves the following key plots:
1. `Figure_2_Inside_vs_Outside_Temperature.png` - Daily Mean Temperature Comparison
2. `Figure_3_Temperature_Difference.png` - Daily Inside-Outside Temperature Difference
3. `Figure_4_Inside_vs_Outside_Humidity.png` - Relative Humidity Trends
4. `Figure_5_L1_vs_Inside_Temperature.png` - Light Sensor vs. Inside Temperature Scatter Plot
5. `Figure_6_Inside_Temperature_vs_Humidity.png` - Temperature vs. Humidity Relationship
6. `Figure_7_Outside_vs_Inside_Temperature.png` - External vs. Internal Temperature Regression Analysis
7. `Figure_8_Daily_Mean_WS1.png` - Wind Speed Sensor Trends
8. `Figure_9_Monthly_Temperature_Comparison.png` - Monthly Average Temperature Trends
9. `Figure_10_Monthly_Humidity_Comparison.png` - Monthly Average Humidity Trends

---

## 🚀 How to Run the Code
1. Clone the repository or open the notebook in Google Colab.
2. Upload your dataset (`greenhouse_dataset.csv`).
3. Run the cells sequentially to reproduce the data cleaning, statistical checks, and visualizations.

---

## 📜 License
This project is open-source and available for academic and research purposes.
