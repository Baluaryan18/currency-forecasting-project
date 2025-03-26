# 🌍 Currency Analysis & Forecasting Project

This project provides a comprehensive analysis of historical currency exchange rates relative to the Euro (EUR), utilizing forecasting models, volatility analysis, and investment strategies. It covers data preprocessing, economic event impacts, interactive dashboards, and forecasting using ARIMA.

---

## 📊 Key Modules

### 1. Data Preprocessing
- Cleaned and standardized over 400,000 exchange rate records
- Removed missing entries and ensured daily frequency per currency

### 2. Exploratory Data Analysis (EDA)
- Focus on key currencies (USD, INR, GBP, JPY, etc.)
- Z-score based anomaly detection and volatility plots

### 3. Volatility Analysis
- Daily returns and rolling 30-day volatility
- Comprehensive volatility ranking for 170+ currencies

### 4. Currency Comparison & Valuation
- Normalized values for visual comparison
- Radar, line, and area charts to show strength over time

### 5. Forecasting Models
- ARIMA forecasting for top 10 impactful currencies
- Exportable 180-day predictions and Prophet-ready CSVs

### 6. Currency Converter Tool
- Converts EUR to any currency using historical exchange rates
- Accepts date and amount as input

### 7. Economic Event Analysis
- Aligns exchange rate data with events like 2008 crash, COVID, Brexit
- Annotated plots highlight impact on currency trends

### 8. Strategy & Investment Insight
- Risk-return profiles and hedging insights
- Visual dashboards and summaries for decision making

---

## 🧠 Deliverables

- `data/` → Cleaned datasets & ARIMA forecasts
- `visualizations/` → HTML interactive dashboard
- `notebooks/` → Jupyter notebooks and tools
- `report/` → Final PDF summary report

---

## Getting Started

### 1. Cloned this repository:
```bash
git clone https://github.com/yourusername/currency-forecasting-project.git
cd currency-forecasting-project
```

### 2. Installed dependencies:
```bash
pip install -r requirements.txt
```

### 3. Explore:
- Run notebooks in `notebooks/`
- View interactive dashboard: `visualizations/interactive_currency_strength.html`
- Review PDF report: `report/currency_analysis_report.pdf`

---

## Dependencies

```txt
pandas
numpy
matplotlib
seaborn
plotly
statsmodels
fpdf
```

---


## Acknowledgments

- Created using real-world foreign exchange datasets
- Powered by Python, ARIMA, and Prophet forecasting
