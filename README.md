# Value at Risk (VaR) Analysis Project

A comprehensive financial risk analysis project that calculates and visualizes Value at Risk (VaR) for a portfolio of major technology stocks using Python.

## 📊 Project Overview

This project performs a detailed analysis of portfolio risk using statistical methods and historical data. It analyzes the daily returns of major technology stocks (Apple, Microsoft, Google, Amazon) and calculates various risk metrics including Value at Risk (VaR) using different methodologies.

## 🎯 Key Features

- **Data Acquisition**: Downloads real-time stock data using Yahoo Finance API
- **Statistical Analysis**: Calculates mean, variance, skewness, and kurtosis of stock returns
- **Risk Metrics**: 
  - Parametric VaR (Normal Distribution)
  - Historical VaR
  - Portfolio risk assessment
- **Visualization**: 
  - Return distribution histograms
  - Correlation heatmaps
  - Statistical distribution plots
- **Statistical Testing**: 
  - One-sample t-test for portfolio returns
  - Distribution fitting (Normal vs Student's t)
  - Bootstrapping for confidence intervals

## 🛠️ Tech Stack

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **yfinance**: Financial data download
- **SciPy**: Statistical analysis and scientific computing

## 📋 Requirements

- Python 3.7+
- Jupyter Notebook

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/var-analysis-project.git
cd var-analysis-project
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

Or install the packages manually:
```bash
pip install pandas numpy matplotlib seaborn yfinance scipy
```

## 📖 Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook PiyushSingh_var.ipynb
```

2. Run the cells sequentially to perform the analysis:
   - Cell 1: Install dependencies
   - Cell 2: Import libraries
   - Cell 3: Download stock data and calculate returns
   - Cell 4: Visualize return distributions
   - Cell 5: Calculate summary statistics
   - Cell 6: Portfolio analysis
   - Cell 7: VaR calculations
   - Cell 8: Correlation analysis
   - Cell 9: Statistical testing
   - Cell 10: Distribution fitting and bootstrapping

## 📁 Project Structure

```
var-analysis-project/
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
├── .gitignore               # Git ignore rules
├── PiyushSingh_var.ipynb    # Main analysis notebook
└── Piyush_Singh_VaR_Report.pdf  # Analysis report
```

## 🔬 Analysis Details

### Stocks Analyzed
- **AAPL** - Apple Inc.
- **MSFT** - Microsoft Corporation
- **GOOGL** - Alphabet Inc.
- **AMZN** - Amazon.com Inc.

### Time Period
- **Duration**: 1 year (365 days)
- **Data Frequency**: Daily closing prices

### Methodology

1. **Log Returns Calculation**: Uses logarithmic returns for better statistical properties
2. **Equal Weight Portfolio**: Each stock weighted at 25%
3. **VaR Calculation**:
   - Parametric VaR assumes normal distribution
   - Historical VaR uses actual historical percentiles
4. **Statistical Tests**: 
   - T-test to determine if returns are significantly different from zero
   - Distribution fitting to compare normal vs t-distribution
   - Bootstrapping for robust confidence intervals

## 📈 Sample Results

The analysis provides insights such as:
- Portfolio average daily return and standard deviation
- 95% VaR estimates (both parametric and historical)
- Correlation matrix showing relationships between stocks
- Statistical significance of portfolio returns
- Distribution parameters and confidence intervals

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Piyush Singh**
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Acknowledgments

- Yahoo Finance for providing stock data via yfinance API
- The open-source Python data science community

## ⚠️ Disclaimer

This project is for educational and research purposes only. The analysis and results should not be considered as financial advice. Always consult with a qualified financial advisor before making investment decisions.

## 📞 Contact

For questions or suggestions, please open an issue in the GitHub repository.