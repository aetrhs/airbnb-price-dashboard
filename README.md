# NYC Airbnb Price Dashboard

This project explores New York City Airbnb listings to help Airbnb hosts identify undersaturated, high-demand neighbourhoods and set prices for their properties. The final result is an interactive dashboard that combines spatial visualisations with pricing and saturation stats to highlight potentially high-revenue areas.

## Repository Structure

- `data/`  
  - Raw and cleaned CSV files (not tracked in git).
- `README.md` – project overview and reproduction instructions.  
- `.gitignore` – excludes large data files.
  
- `airbnb_cleaning.ipynb` – load raw data, clean columns, handle missing values and outliers, export cleaned dataset.  
- `airbnb_EDA.ipynb` – inspect structure, distributions and key relationships to understand the dataset.  
- `airbnb_analysis_FINAL.ipynb` – build visualisations for the dashboard.


## Data Source

The dataset comes from Kaggle: [Airbnb Open Data – New York City](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata/data). It contains listing-level information such as neighbourhood group, neighbourhood, latitude/longitude, room type, price and host listing count, which are used to analyse spatial pricing patterns and market saturation.

To reproduce the analysis:

1. Download the dataset from Kaggle.
2. Place the CSV file in the `data/` folder (e.g. `data/airbnb-data.csv`).
3. Create and activate a Python environment with the required libraries (`pandas`, `numpy`, `plotly`, etc.).
4. Run `airbnb_cleaning.ipynb`, then `airbnb_EDA.ipynb`, then `airbnb_analysis_FINAL.ipynb` in order.

