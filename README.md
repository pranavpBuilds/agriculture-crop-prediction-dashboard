# 🌾 Agriculture Crop Prediction Dashboard

An interactive Power BI dashboard designed to analyze agricultural and environmental conditions associated with different crops. The dashboard transforms crop, soil, and climatic data into meaningful visual insights to support data-driven agricultural analysis and crop suitability assessment.

---

## 📌 Project Overview

Agriculture is highly influenced by environmental and soil conditions such as temperature, humidity, rainfall, soil pH, and nutrient availability.

This project uses agricultural data containing soil and environmental parameters for different crops and presents the information through an interactive Power BI dashboard.

The dashboard allows users to explore crop distributions, environmental conditions, rainfall patterns, soil nutrients, and crop-wise comparisons through interactive filters and visualizations.

The primary objective is to make agricultural data easier to understand and provide a visually engaging platform for exploring crop-related patterns.

---

## 🎯 Objectives

- Analyze agricultural and environmental parameters associated with different crops.
- Understand how soil nutrients vary across crops.
- Compare rainfall, temperature, humidity, and soil pH conditions.
- Identify patterns in crop-wise environmental requirements.
- Build an interactive and visually engaging Power BI dashboard.
- Enable users to explore the dataset using interactive filters and slicers.
- Present agricultural information in a simple and understandable form.

---

## 📊 Dashboard Features

### 🌱 Crop Analysis
- Crop distribution across the dataset
- Crop-wise comparisons
- Crop-specific environmental conditions

### 🌦️ Environmental Analysis
- Average temperature
- Average rainfall
- Average humidity
- Soil pH distribution
- Relationship between temperature and humidity

### 🧪 Soil Nutrient Analysis
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Crop-wise nutrient comparison

### 🎛️ Interactive Filtering

The dashboard includes interactive controls for exploring the data based on:

- Crop
- Temperature
- Rainfall
- Soil pH

Selecting different values dynamically updates the dashboard visualizations.

---

## 📈 Key Performance Indicators

The dashboard provides high-level agricultural metrics including:

- Total Records
- Total Crops
- Average Temperature
- Average Rainfall
- Average Humidity
- Average Soil pH

---

## 📊 Visualizations

The dashboard contains multiple visualizations, including:

- Crop Distribution Donut Chart
- Crop-wise Comparison Bar Chart
- Average Rainfall by Crop
- Soil Nutrient Comparison
- Temperature vs Humidity Scatter Plot
- Crop-wise Rainfall Analysis
- Soil pH Analysis
- Interactive KPI Cards

---

## 🗂️ Dataset

The project uses a publicly available agricultural crop dataset containing soil and environmental parameters.

### Major attributes include:

| Attribute | Description |
|---|---|
| N | Nitrogen content in soil |
| P | Phosphorus content in soil |
| K | Potassium content in soil |
| Temperature | Temperature in °C |
| Humidity | Relative humidity (%) |
| pH | Soil acidity/alkalinity |
| Rainfall | Rainfall measurement |
| Crop | Crop associated with the given conditions |

The dataset was cleaned and prepared before being imported into Power BI.

---

## 🧹 Data Preparation

The dataset was prepared before visualization by performing basic data-cleaning operations such as:

- Checking for missing values
- Checking for duplicate records
- Verifying data types
- Standardizing column names
- Checking numerical ranges
- Removing unnecessary fields where required
- Preparing categorical and numerical fields for visualization

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel / CSV**
- **Git**
- **GitHub**

---

## 📁 Project Structure

```text
Agriculture-Crop-Prediction
│
├── dashboard/
│   └── Agriculture_Crop_Prediction_Dashboard.pbix
│
├── data/
│   └── agricultural_dataset.csv
│
├── screenshots/
│   ├── dashboard_overview.png
│   ├── dashboard_crop_filter.png
│   └── dashboard_interactive.png
│
├── reports/
│
├── presentation/
│
└── README.md
