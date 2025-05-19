# 🌍 COVID-19 Data Analysis

This project analyzes global COVID-19 data to uncover trends in infections, deaths, and vaccinations across countries and continents.

## 📌 Project Objective

The aim is to explore a real-world COVID-19 dataset to:
- Understand global and regional patterns in cases and deaths.
- Evaluate vaccination distribution.
- Provide visual insights into the impact of the pandemic.

---

## 📂 Dataset

The dataset used in this project (`owid-covid-data.csv`) includes:
- Total and daily COVID-19 cases
- Total and daily deaths
- Total vaccinations
- ICU patients
- Population aged 65+
- Country and continent classifications

---

## 🔍 Data Processing

1. **Data Cleaning**
   - Removed unnecessary columns unrelated to the core analysis (e.g., economic metrics).
   - Converted date strings to datetime format.
   - Filled missing values with 0 for consistency.
   - Filtered down to key columns for focused analysis.

2. **Feature Selection**
   - Selected relevant fields:
     - `continent`, `location`, `total_cases`, `new_cases`
     - `total_deaths`, `new_deaths`, `total_vaccinations`
     - `icu_patients`, `aged_65_older`

---

## 📊 Key Insights

### 🌐 Top Continents by Total Vaccinations
Identified which continents administered the most vaccines during the pandemic.

### 🏳️ Top Countries by Total Vaccinations
Highlighted the countries with the largest vaccination efforts.

### 🚨 Top Countries by New Daily Cases
Compared which countries had the highest spikes in daily cases.

### ⚰️ COVID-19 Fatalities
- Analyzed both continents and countries with the highest number of total deaths.
- Provided a view of pandemic severity and impact across regions.

---

## 📈 Visualizations

Visualized data using bar charts to compare:
- 💉 Total vaccinations by continent and country
- 🦠 New daily COVID-19 cases by country
- ☠️ Total deaths by continent and country

All plots were generated using `matplotlib`.

---

## 🧾 Conclusion

This analysis highlights the global variation in COVID-19 spread, response, and outcomes. It offers a visual and statistical understanding of:
- Which areas faced the greatest health challenges
- Where vaccination efforts were strongest
- How death rates varied by region

The results provide valuable insights for public health professionals, researchers, and policymakers.

---

## 📁 Files Included

- `Covid-Data-Analysis.ipynb` – Jupyter notebook with the full analysis
- `owid-covid-data.csv` – Source dataset (can be downloaded from [Our World in Data](https://ourworldindata.org/coronavirus-source-data))

---

## 📌 Requirements

- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook

Install dependencies using:
```bash
pip install pandas matplotlib
```

---

## ✅ How to Run

1. Clone this repository
2. Open `Covid-Data-Analysis.ipynb` in Jupyter Notebook or VS Code
3. Run all cells to reproduce the analysis

---

## 📬 Contact

For questions or suggestions, feel free to open an issue or reach out via GitHub.
