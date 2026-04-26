# 🌍 Climate Data Analysis for COP32

##  Project Overview
This project analyzes climate data from multiple African countries to assess climate patterns, detect extreme events, and evaluate vulnerability for informed decision-making at COP32.

The analysis focuses on:
- Temperature trends
- Rainfall variability
- Extreme weather events
- Cross-country climate comparison

---

##  Objectives
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Identify outliers and extreme climate events
- Analyze time series trends
- Compare climate patterns across countries
- Provide data-driven insights for climate finance prioritization

---

##  Dataset
The dataset includes daily climate observations for:
- Ethiopia
- Kenya
- Nigeria
- Sudan
- Tanzania

### Features:
- `T2M` – Average Temperature  
- `T2M_MAX` – Maximum Temperature  
- `T2M_MIN` – Minimum Temperature  
- `PRECTOTCORR` – Precipitation  
- `RH2M` – Relative Humidity  
- `WS2M` – Wind Speed  

---

##  Data Preprocessing
- Converted `YEAR` and `DOY` into datetime format  
- Extracted monthly features  
- Replaced missing values (`-999` → NaN)  
- Removed duplicate records  
- Standardized datasets across all countries



---

##  How to Run

1. Clone the repository:
```bash
git clone "https://github.com/hiwiy/climate-challenge-week0.git"
cd climate-project

2. #Create virtual environment:
python -m venv venv
venv\Scripts\activate

3.Install dependencies:
pip install -r requirements.txt

4.Run the notebook:
Open in VS Code or Jupyter Notebook


Report

The full analysis report is available as a PDF in the repository.

Conclusion

This project demonstrates how climate data analysis can support informed policy decisions and prioritize climate adaptation investments across regions.


Author

hiwiy
10 Academy – KIAM Program




