# India Air Quality Index (AQI) & Estimated Pollutant Levels

## 📌 Overview
This repository contains Air Quality Index (AQI) data for major Indian cities, sourced from the **Central Pollution Control Board (CPCB)**. Since the CPCB dataset only provides AQI values, pollutant concentrations (PM₂.₅, PM₁₀, NO₂, SO₂, CO, and O₃) have been **mathematically estimated** using reverse engineering techniques. 

This dataset is valuable for **air pollution analysis, trend forecasting, and AI modeling**.

## 📂 Dataset Files
The repository includes AQI and estimated pollutant levels for the following cities:
- `Delhi_AQI_Dataset.csv`
- `Mumbai_AQI_Dataset.csv`
- `Bangalore_AQI_Dataset.csv`
- `Chennai_AQI_Dataset.csv`
- `Hyderabad_AQI_Dataset.csv`

Each file contains:
| Column | Description |
|---------|------------|
| `City` | Name of the city |
| `Date` | Date of recorded AQI |
| `AQI` | Air Quality Index (as per CPCB) |
| `PM2.5` | Estimated Fine Particulate Matter (µg/m³) |
| `PM10` | Estimated Coarse Particulate Matter (µg/m³) |
| `NO2` | Estimated Nitrogen Dioxide (ppb) |
| `SO2` | Estimated Sulfur Dioxide (ppb) |
| `CO` | Estimated Carbon Monoxide (ppm) |
| `O3` | Estimated Ozone (ppb) |

## 🔍 Provenance
### **Source**
- The **AQI values** were sourced from the **CPCB official website**.
- The **pollutant concentrations** were estimated using **mathematical models** based on AQI-to-pollutant relationships.

### **Collection Methodology**
- The base dataset from **CPCB** was processed to extract **AQI values**.
- A reverse-engineering approach was applied to **estimate pollutant levels** using derived formulas.
- The calculated data was then rounded off and structured into CSV files.

## ⚠️ Disclaimer
- **Estimated pollutant values are derived using calculations and may not be 100% accurate**.
- This dataset is for **research and analytical purposes only**.
- For precise pollutant levels, refer to official **CPCB monitoring stations**.

## 📜 License
This dataset is shared under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. 

**You are free to:**
- Share — Copy and redistribute the data in any format.
- Adapt — Modify, remix, and build upon the data.

✅ **Attribution Required:** Please credit the **CPCB** for the original AQI data and this repository for pollutant estimations.

## 🚀 How to Use
- Download the dataset and load it into Python (Pandas), Excel, or any data analysis tool.
- Use it for **visualizations, trend analysis, machine learning models, or policy research**.

## 📫 Contact
If you have any questions, feel free to open an issue or reach out!
