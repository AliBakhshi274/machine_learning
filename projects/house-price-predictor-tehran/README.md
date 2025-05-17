# Tehran House Price Prediction

This project aims to predict the price of residential apartments in Tehran using real-world data and machine learning techniques. The dataset contains approximately 4,000 real entries collected from various listings.

## Dataset Features

- `Area`: Property size in square meters
- `Room`: Number of bedrooms
- `Parking`: Availability of parking
- `Warehouse`: Availability of storage room
- `Elevator`: Availability of elevator
- `Address`: Approximate location in Tehran (some entries may be missing)
- `Price`: Price in Iranian Toman
- `Price(USD)`: Price in USD

## Project Workflow

1. **Data Cleaning**
   - Remove invalid or missing values (e.g., unrealistic areas, missing addresses)
   - Detect and remove outliers using IQR (Interquartile Range)
   - Handle skewness in numerical features
   - Normalize or scale data if needed

2. **Exploratory Data Analysis (EDA)**
   - Scatter plots, histograms, and box plots
   - Distribution analysis

3. **Modeling**
   - Linear regression
   - Polynomial regression
   - Model evaluation using metrics like MAE, and R²

4. **Prediction**
   - Predict housing prices on new or unseen data

## Tools & Libraries

- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## How to Run

```bash
# Activate your virtual environment
conda env create -f environment.yml