

# 🐦 Bird Species Observation Analysis

## 📌 Project Overview

This project focuses on analyzing bird species observation data across two different habitats: **Forest and Grassland**. The goal is to uncover patterns in species distribution, environmental impact, and biodiversity using data analysis and visualization techniques.

The project combines **Python-based data analysis** with an **interactive Power BI dashboard** to provide meaningful ecological insights.

---

## 🎯 Objectives

* Analyze bird species diversity across habitats
* Identify dominant and rare species
* Study the impact of environmental factors (temperature, humidity)
* Detect sampling bias in observation data
* Build an interactive dashboard for better decision-making

---

## 📊 Dataset Description

The dataset contains real-world bird observation records with features such as:

* Common Name & Scientific Name
* Habitat (Forest / Grassland)
* Date & Time of observation
* Temperature and Humidity
* Disturbance level
* Watchlist status

Total Records: **17,000+**
Total Features: **30+**

---

## 🧹 Data Preprocessing

The following steps were performed:

* Merged multiple datasets into a single dataset
* Converted date columns into datetime format
* Handled missing values
* Removed duplicate records
* Standardized categorical values
* Created new derived features (Month, etc.)

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Habitat Analysis

* Observations are distributed across both Forest and Grassland
* Indicates biodiversity presence in both environments

### 🔹 Species Diversity

* Total of **120+ unique species** observed
* Some species dominate while others are rare

### 🔹 Monthly Trend

* Peak observations in **May and June**
* Decline observed in July

### 🔹 Top Species

* Species like *Northern Cardinal* and *Carolina Wren* are highly observed
* Shows uneven species distribution

### 🔹 Environmental Impact

* Bird activity is highest in moderate temperature ranges (10°C–25°C)
* Higher humidity levels correlate with increased observations

### 🔹 Disturbance Impact

* Slight disturbance has minimal effect
* Serious disturbance reduces bird observations significantly

### 🔹 Watchlist Analysis

* Around **2.2% species are under watchlist**
* Important for conservation insights

---

## 📊 Power BI Dashboard

An interactive dashboard was built to visualize insights effectively.

### 🔹 Features:

* KPI Cards (Total Observations, Species, Watchlist %)
* Monthly Trend Analysis
* Habitat Comparison
* Top Species Visualization
* Environmental Impact Charts
* Disturbance Analysis
* Interactive Filters (Habitat, Month, Species)

---

## 📸 Dashboard Preview

![Dashboard](PowerBidashboard.png)

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Matplotlib
* Power BI
* Google Colab

---

## 📁 Project Structure

```
bird-species-analysis/
│
├── Bird_Species_Analysis.ipynb
├── final_bird_data.csv
├── report.pdf
├── dashboard.png
└── README.md
```

---

## 🔍 Key Insights

* Bird activity peaks during moderate environmental conditions
* Both habitats support biodiversity but patterns differ
* Few species dominate the ecosystem
* Environmental and disturbance factors significantly impact observations
* Sampling bias may influence interpretation

---

## 🚀 Conclusion

This project demonstrates how data analysis and visualization can uncover meaningful ecological patterns and support environmental decision-making.

---

## 📌 Future Improvements

* Add more years of data for trend analysis
* Build predictive models (ML)
* Deploy dashboard as a web app

---

## 🙋‍♂️ Author

Ankit Yadav
MCA Student | Aspiring Data Analyst

---
