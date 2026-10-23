# PandemicPulse

Exploratory analysis of the global COVID-19 pandemic in a Jupyter notebook ([`CovidAnalysis.ipynb`](CovidAnalysis.ipynb)), using pandas, Matplotlib and Seaborn.

## Data

The notebook loads the country-level time series straight from the [datasets/covid-19](https://github.com/datasets/covid-19) repository (`countries-aggregated.csv`): daily confirmed cases, deaths and recoveries per country. No download is needed.

## What's covered

**Part 1**
1. Loading and preprocessing (cleaning, date parsing)
2. Data exploration and cleaning
3. Global trends over time
4. Country-specific trends
5. Comparison of the top 10 most affected countries
6. Correlation between confirmed cases, deaths and recoveries

**Part 2: guided questions**
- Global trends of cases, deaths and recoveries
- Countries with the highest totals as of the latest date
- Trends in the top 5 countries
- Growth rates and 7-day moving averages
- Cumulative totals for the top 10 countries
- Recovery rates across countries
- Correlation heatmap
- Lockdown periods highlighted on case curves

Two questions, testing vs. cases and breakdown by continent, are sketched out but can't run because the dataset has no testing or continent data.

## Running

```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook CovidAnalysis.ipynb
```

You can also open it in Google Colab.
