# 📉 Unemployment in India - Data Analysis Project

This project focuses on exploring and visualizing **unemployment trends in India** using real-world data. The dataset includes unemployment rates, employment numbers, and labor participation rates by region, date, and area type (urban/rural).

## 🧠 Project Overview

- **Goal**: Analyze unemployment trends across regions and over time, discover patterns, and visualize key insights.
- **Dataset**: `Unemployment in India.csv` (from Kaggle or other government sources)
- **Tools & Libraries**:
  - `Pandas` for data handling
  - `Seaborn` and `Matplotlib` for data visualization
  - `NumPy` and `SciPy` (optional for advanced analysis)
  - Jupyter Notebook for coding and presentation

---

## 📊 Key Columns in Dataset

- `Region`: Indian states/UTs
- `Date`: Time of data recording
- `Frequency`: Monthly data
- `Estimated Unemployment Rate (%)`
- `Estimated Employed`
- `Estimated Labour Participation Rate (%)`
- `Area`: Urban or Rural

---

## ✅ Steps Performed

1. **Data Loading and Cleaning**
   - Loaded CSV using `pandas.read_csv()`
   - Removed extra spaces in column names using `.str.strip()`
   - Checked for nulls and cleaned the data

2. **Exploratory Data Analysis (EDA)**
   - Used `.describe()` and `.info()` to understand the structure
   - Visualized trends using `lineplot`, `boxplot`, `barplot`, and `heatmap`
   - Analyzed unemployment over time for each region and area type

3. **Visualizations Created**
   - **Unemployment over Time** for different regions
   - **Comparison by Area** (Urban vs Rural)
   - **State-wise trends** using groupby and aggregation
   - **Correlation Heatmap** for understanding relationships between columns

4. **Optional**: Trend detection using `.groupby()` and `.mean()`, and early experimentation with forecasting (future scope)

---

## 📈 Sample Visuals

- Line plots for unemployment rate over time
- Area-wise comparison of employment levels
- Heatmaps showing correlation between labor data points

