# Electricity Peak Demand Forecasting

A time series forecasting project that predicts electricity peak demand using the Holt-Winters exponential smoothing method.

## Overview

This project implements Holt-Winters and SARIMAX forecasting techniques to predict electricity peak demand patterns. The Holt-Winters and SARIMAX methods are particularly effective for time series data that exhibits both trend and seasonal patterns, making them ideal for electricity consumption forecasting.

## Features

- **Time Series Analysis**: Comprehensive analysis of electricity demand patterns
- **Holt-Winters and SARIMAX Methods**: Implementation of exponential smoothing with trend and seasonal components
- **Peak Demand Prediction**: Forecasts electricity peak demand for planning and optimization
- **Data Visualization**: Visual representations of historical data and forecasts

## Repository Structure

```
electricity_peak_demand_forecasting/
├── Holt_winters.ipynb    # Main Jupyter notebook with analysis and forecasting
└── README.md             # Project documentation
```

## Requirements

```python
pandas
numpy
matplotlib
statsmodels
jupyter
```

## Installation

1. Clone this repository: 
```bash
git clone https://github.com/TReV-89/electricity_peak_demand_forecasting.git
cd electricity_peak_demand_forecasting
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib statsmodels jupyter
```

## Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `Holt_winters.ipynb` and run the cells sequentially to:
   - Load and explore the electricity demand data
   - Perform time series decomposition
   - Apply Holt-Winters forecasting
   - Visualize results and predictions

## Methodology

The project uses the **Holt-Winters Exponential Smoothing** method, which accounts for: 

- **Level**: The average value in the series
- **Trend**: The increasing or decreasing pattern in the data
- **Seasonality**:  Repeating patterns over fixed periods (daily, weekly, seasonal variations)

This triple exponential smoothing approach is well-suited for electricity demand data that typically shows:
- Daily patterns (higher demand during day, lower at night)
- Weekly patterns (weekday vs weekend usage)
- Seasonal patterns (higher in summer/winter due to climate control)

## Results

The notebook provides:
- Historical electricity demand analysis
- Forecasted peak demand values
- Model performance metrics
- Visualization of actual vs predicted values

## Applications

This forecasting model can be used for:
- **Grid Management**: Planning electricity generation and distribution
- **Capacity Planning**: Infrastructure investment decisions
- **Load Balancing**: Optimizing energy distribution
- **Cost Optimization**: Reducing operational costs through better demand prediction

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. 

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**TReV-89**

## Acknowledgments

- Electricity demand data sources
- Statsmodels library for Holt-Winters implementation
- Time series forecasting community

---

*For questions or suggestions, please open an issue in this repository.*
