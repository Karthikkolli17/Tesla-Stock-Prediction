# Tesla Stock Prediction

A machine learning project that predicts Tesla (TSLA) stock prices using time series analysis.

## What this project includes

- Historical TSLA close-price data retrieval using Yahoo Finance
- Time series preprocessing and stationarity checks
- Forecasting experiments and comparative evaluation
- Visual analysis of trends and model outputs

## Repository contents

- `TimeSeriesProjectCode.ipynb` - end-to-end notebook for data retrieval, analysis, and forecasting
- `requirements.txt` - Python dependencies for running the notebook

## Quick start

1. Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run Jupyter and open the notebook:

```bash
jupyter notebook
```

4. Open `TimeSeriesProjectCode.ipynb` and run cells in order.

## Notes

- This project is notebook-first and intended for exploratory analysis.
- Internet access is required for data retrieval through `yfinance`.

## Roadmap

- Convert reusable notebook functions into Python modules/scripts
- Add a model comparison summary table with standardized metrics
- Export forecast plots and key metrics as versioned artifacts

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Author
Karthik Kolli - [@Karthikkolli17](https://github.com/Karthikkolli17)
