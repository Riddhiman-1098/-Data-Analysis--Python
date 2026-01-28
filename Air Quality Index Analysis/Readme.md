---

# 🌫️ Air Quality Analysis – Delhi

A data analysis project exploring Delhi's air quality using Python. It utilizes `pandas` for data processing, `plotly` for rich interactive visualizations, and `requests` for data fetching (if needed). The main goal is to analyze, compute, and visualize the Air Quality Index (AQI) trends and pollutant patterns across time.

---

## 📌 Introduction

This project analyzes air quality data from Delhi, focusing on pollutants such as PM2.5, PM10, NO₂, CO, and others. The analysis leverages historical data from `delhiaqi.csv` to uncover patterns and trends in air quality levels over time.

---

## 📂 Files Included

| File                     | Description                                                   |
| ------------------------ | ------------------------------------------------------------- |
| `analyze_air_quality.py` | Python script to process, analyze, and visualize the AQI data |
| `delhiaqi.csv`           | Dataset containing air quality readings and timestamps        |
| `README.md`              | Project overview and setup instructions                       |

---

## 📦 Prerequisites

Before running the script, ensure you have the following Python libraries installed:

```bash
pip install pandas plotly requests
```

---

## 🚀 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/your-username/air-quality-delhi.git
cd air-quality-delhi
```

2. **Place the dataset**

Ensure `delhiaqi.csv` is located in the project directory.

3. **Run the script**

```bash
python analyze_air_quality.py
```

---

## 🧪 Features and Functionality

The script performs several key tasks:

* ✅ **AQI Calculation**
  Uses `calculate_aqi()` and `calculate_overall_aqi()` to determine AQI for each pollutant and overall AQI values.

* 📊 **Data Analysis**

  * AQI distribution by levels (Good, Moderate, Poor, etc.)
  * Pollutant-wise concentration analysis
  * Correlation heatmaps between pollutants
  * Hourly average AQI visualization
  * AQI trends by day of the week

* 📈 **Interactive Visualizations (Plotly)**

  * Time series plots
  * Pie charts for pollutant distribution
  * Heatmaps for correlation
  * Line charts for AQI trends

---

## 🛠 Methodology

1. **Data Import**

   * `delhiaqi.csv` loaded using `pandas`.

2. **Data Cleaning**

   * Handles missing or inconsistent data entries for accurate insights.

3. **AQI Calculation**

   * Custom functions compute AQI values based on pollutant-specific thresholds.

4. **Exploratory Data Analysis**

   * Detailed statistical and visual analysis of the pollutants and AQI metrics.

5. **Visualization**

   * Utilizes `plotly.express` and `plotly.graph_objects` to build interactive, high-quality graphs.

---

## 📊 Sample Visuals

*Note: Visuals will appear after script execution if run in Jupyter Notebook or saved as HTML/PNG.*

### AQI Distribution

![AQI Distribution Example]((https://github.com/Riddhiman-1098/-Data-Analysis--Python/blob/d31d73a11539be60088400783910da2e932238dc/Air%20Quality%20Index%20Analysis/Images/AQI%20Category%20Distribution%20Over%20Time.png))

### Pollutant Correlation Heatmap

![Pollutant Correlation]([images/pollutant_correlation_heatmap.png](https://github.com/Riddhiman-1098/-Data-Analysis--Python/blob/d31d73a11539be60088400783910da2e932238dc/Air%20Quality%20Index%20Analysis/Images/Correlation%20Between%20Pollutants.png))

### Hourly AQI Trends

![Hourly Trends]([images/hourly_trends.png](https://github.com/Riddhiman-1098/-Data-Analysis--Python/blob/d31d73a11539be60088400783910da2e932238dc/Air%20Quality%20Index%20Analysis/Images/Hourly%20Average%20AQI%20Trends%20in%20Delhi%20(Jan%202023).png))

---

## 📌 Conclusion

This project offers comprehensive insights into Delhi’s air pollution landscape. The results can assist:

* Environmental scientists in understanding pollutant behavior
* Policymakers in creating data-driven pollution control measures
* Citizens in awareness and prevention of pollution-related health issues

---

## 👨‍💻 Contributors

* **Riddhiman Mukhopadhyay**

---

## 🙋‍♂️ Want to Contribute?

Feel free to fork this repository and submit pull requests with improvements, new visualizations, or updated datasets!

---

### 📁 Optional: Suggested Image Files

To fully utilize the visual elements in the README, save screenshots with these filenames:

* `aqi_distribution_example.png`
* `pollutant_correlation_heatmap.png`
* `hourly_trends.png`

Place them in a folder named `/images` in your project root.


