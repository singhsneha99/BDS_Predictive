# Predicting Real Estate Prices with Alternative Data

This project aims to predict real estate prices in New York City using alternative data sources beyond typical housing data. Jupyter notebooks are provided to explore each data source and extract relevant features.

## Data Sources
- `citibike.ipynb`: Analyzes CitiBike ride data to identify highly trafficked areas. Could indicate desirable neighborhoods.
- `health_inspections.ipynb`: Processes restaurant health inspection data. Poor inspection results may lower home values. 
- `restaurants.ipynb`: Looks at new restaurant registrations by zipcode. More openings likely signals increased interest in area.
- `311_complaints.ipynb`: Checks 311 complaint data by type and location. Noise or sanitation issues may deter buyers.
- `evictions.ipynb`: Maps eviction notices to find less stable housing areas.    
- `MTA_bus.ipynb`: Examines bus ridership data for commuter accessibility clues.

## Methodology
The feature engineering from each notebook will be consolidated to train machine learning models to predict housing sale prices. Baseline models using only housing data will be compared to those with added alternative data features.

## Usage
1. Follow and run the data extraction/processing steps in each notebook
2. Combine engineered features into master dataset
3. Explore different ML models to predict housing sale price 
4. Evaluate predictions against test data

This alternative data approach can provide unique signals to improve real estate price modeling.
