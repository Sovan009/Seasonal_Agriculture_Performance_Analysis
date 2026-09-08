# Seasonal Agriculture Performance Analysis

A data analytics project investigating how agricultural performance — yield, resource usage, and economic outcomes — varies across India's three cropping seasons (**Kharif**, **Rabi**, and **Zaid**).

> **Program:** VOIS AICTE Batch 1, 2026–2027 — Major Project

**▶️ Open in Google Colab:** [Seasonal Agriculture Performance Analysis](https://colab.research.google.com/drive/166Zww49hSkp-s7VEAGbIVGXQI_g3Cd3q?usp=sharing)

---

## 📌 Overview

Agricultural performance is shaped by seasonal shifts in weather, soil conditions, resource availability, and market dynamics. This project analyzes a farm-level dataset spanning multiple Indian states, crops, and irrigation methods to uncover **meaningful seasonal patterns, relationships, and anomalies**, and translates those findings into evidence-based recommendations.

## 🎯 Problem Statement

Raw agricultural data does not, on its own, explain how performance changes from one season to another. This project analyzes the dataset to identify seasonal trends, relationships, and variations in agricultural outcomes, rather than performing a generic, unfocused exploration of the data.

## 🔑 Key Questions Addressed

The notebook is structured around the following questions, each with its own dedicated, headed section:

1. How does agricultural performance vary across seasons?
2. What major seasonal patterns can be observed?
3. Which characteristics change between seasons?
4. What differences exist between agricultural activities in different seasons?
5. Are there noticeable variations in resource usage across seasons?
6. Are there relationships between seasonal environmental conditions and agricultural performance?
7. How do economic outcomes vary across seasons?
8. Are some seasonal patterns consistent across different regions or categories?
9. Are there unusual or unexpected seasonal patterns?
10. What insights and recommendations can be derived from the observed differences? *(includes statistical validation via one-way ANOVA)*

## 🗂️ Dataset

**File:** `seasonal_agriculture_performance_dataset.csv`
**Size:** 4,000 farm records × 28 attributes

| Category | Attributes |
|---|---|
| Identifiers | Farm ID, State, District, Crop, Season |
| Environmental | Rainfall, Temperature, Humidity, Sunlight Hours |
| Soil & Inputs | Soil pH, Soil Moisture, Nitrogen/Phosphorus/Potassium, Fertilizer, Pesticide, Seed Quality |
| Production | Farm Area, Irrigation Method, Yield, Production |
| Economic | Market Price, Total Cost, Revenue, Profit |
| Resource Efficiency | Water Used, Water Efficiency, Disease/Pest Risk |

## 🛠️ Tech Stack

- **Language:** Python 3
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`

## 🚀 How to Run

**Option 1 — Google Colab (recommended)**
1. Open the [Colab notebook](https://colab.research.google.com/drive/166Zww49hSkp-s7VEAGbIVGXQI_g3Cd3q?usp=sharing).
2. Upload `seasonal_agriculture_performance_dataset.csv` to the Colab session (Files panel → Upload).
3. Run all cells in order (`Runtime` → `Run all`).

**Option 2 — Locally**
```bash
git clone https://github.com/<your-username>/Seasonal_Agriculture_Performance_Analysis.git
cd Seasonal_Agriculture_Performance_Analysis
pip install pandas numpy matplotlib seaborn scipy
jupyter notebook
```

## 📊 Methodology

1. **Data Cleaning** — group-wise median imputation for missing values, duplicate removal, categorical standardization, and range sanity checks.
2. **Exploratory Data Analysis** — season-wise distributions, correlation heatmaps, and cross-tabulations across states and crops.
3. **Statistical Testing** — one-way ANOVA to confirm whether observed seasonal differences in yield and profit are statistically significant.
4. **Insight Generation** — synthesis of findings into actionable, evidence-based recommendations for seasonal agricultural planning.

## 📁 Repository Structure

```
Seasonal_Agriculture_Performance_Analysis/
├── Seasonal_Agriculture_Performance_Analysis.py   # Full analysis script (Colab-ready)
├── seasonal_agriculture_performance_dataset.csv   # Dataset
├── Major_Project_Seasonal_Agriculture_Performance_Analysis.pdf  # Project brief
└── README.md                                      # Project documentation
```

## 👤 Author

**Sovan Kar**
B.Tech, Computer Science and Data Science — Techno Main Salt Lake

## 📄 License

This project is intended for academic purposes as part of the VOIS AICTE program.
