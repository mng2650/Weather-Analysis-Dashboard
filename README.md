# 🌦️ Weather Analysis Dashboard (MATLAB → JavaScript)

An interactive weather data analysis dashboard built in **HTML + JavaScript (Plotly.js)**, converted from an original MATLAB script.

This project simulates and analyzes long-term climate data (65 years / 780 months) with full statistical processing and visualization — all directly in the browser.

---

## 🚀 Features

* 📊 **Interactive Time Series Plots**

  * Mean temperature
  * Extreme maximum temperature
  * Extreme minimum temperature

* 🔄 **Random Data Generation**

  * Realistic seasonal patterns (sinusoidal)
  * Gaussian noise
  * Missing values (NaNs)

* 🧠 **Missing Data Handling**

  * Replaces missing values using **monthly averages**
  * Equivalent to MATLAB `nanmean` logic

* 📅 **Monthly Analysis (12 × 3 Subplots)**

  * Year-by-year breakdown for each month
  * Separate grids for:

    * Mean temperature
    * Max temperature
    * Min temperature

* 📈 **Trend Detection**

  * Linear regression (JavaScript equivalent of MATLAB `polyfit`)
  * Trend lines displayed on each monthly plot

* 📋 **Statistical Tables**

  * Monthly statistics include:

    * Minimum
    * Mean
    * Median
    * Mode
    * Maximum
    * Standard deviation

* ⚡ **Fully Interactive**

  * Zoom, pan, hover tooltips
  * Regenerate new datasets instantly

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* [Plotly.js](https://plotly.com/javascript/) for interactive charts

---

## 📂 Project Structure

```
├── index.html   # Main dashboard (everything runs here)
└── README.md    # Project documentation
```

---

## ▶️ How to Run

1. Download or clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-dashboard.git
   ```

2. Open the project folder

3. Double-click:

   ```
   index.html
   ```

✅ No installation required — runs entirely in your browser.

---

## 📊 Data Model

The simulated dataset mimics real climate behavior:

* **Length:** 780 months (~65 years)
* **Seasonality:** Sinusoidal annual cycle
* **Noise:** Random Gaussian variation
* **Missing Data:** ~5% randomly removed

---

## 🔬 MATLAB → JavaScript Mapping

| MATLAB Function | JavaScript Equivalent |
| --------------- | --------------------- |
| `plot`          | Plotly.js             |
| `nanmean`       | Custom function       |
| `polyfit`       | Linear regression     |
| `subplot`       | Grid layout + Plotly  |
| loops (`for`)   | JS loops / functions  |

---

## 🎯 Purpose

This project demonstrates how to:

* Translate MATLAB workflows into web-based tools
* Handle missing data in time series
* Perform statistical analysis in JavaScript
* Build interactive scientific dashboards

---

## 📈 Future Improvements

* Export results to CSV / Excel
* Adjustable simulation parameters (noise, missing rate)
* Real-world dataset integration
* Advanced models (polynomial regression, ARIMA, etc.)
* UI controls (sliders, filters)

---

## 📸 Preview

*(Add screenshots here if you want — GitHub will render them nicely)*

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 🙌 Acknowledgements

* Inspired by MATLAB-based climate data analysis workflows
* Visualization powered by Plotly.js

---

## 💡 Author

Your Name
Michael Nsengiyumva
