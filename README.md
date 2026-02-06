# Investment Comparison Tool

A Jupyter notebook for comparing and analyzing different investment types including stocks/ETFs, real estate, and bonds/fixed income.

## Features

- **Stock/ETF Analysis**: Historical performance, returns, volatility, and Sharpe ratios
- **Real Estate Analysis**: Cash flow, appreciation, and ROI calculations for rental properties and REITs
- **Bond/Fixed Income Analysis**: Yield calculations and compound interest projections
- **Comprehensive Comparison**: Side-by-side comparison of all investments with risk vs return visualization

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Launch Jupyter:
```bash
jupyter notebook investment_comparison.ipynb
```

## Usage

The notebook is organized into sections:
1. **Stocks/ETFs**: Automatically fetches historical data and calculates metrics
2. **Real Estate**: Define property details and rental income
3. **Bonds**: Configure bond parameters and calculate returns
4. **Comparison**: View all investments side-by-side with visualizations
5. **Custom**: Add your own investments for analysis

Simply run each cell in order to see the analysis. You can customize the investments by modifying the dictionaries in each section.

## Customization

Edit the investment parameters in each section:
- Change stock tickers in the `stocks` dictionary
- Adjust real estate properties in `real_estate_investments`
- Modify bond details in the `bonds` list

## Output

The notebook provides:
- Performance metrics tables
- Normalized price charts
- Risk vs return scatter plots
- Summary statistics and rankings
