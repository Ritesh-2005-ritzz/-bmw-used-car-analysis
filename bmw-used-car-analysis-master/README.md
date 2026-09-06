# BMW Used Car Market Analysis 🚗

Exploratory data analysis of 10,781 real BMW used car listings from the UK market using Python and Pandas.

## Project Overview

This project analyses a real-world dataset of BMW used car listings to uncover what factors drive resale value — including mileage, fuel type, transmission, year of manufacture, and fuel efficiency across models.

## Dataset

- **Source:** [100,000 UK Used Car Dataset](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes) — Kaggle
- **File used:** `bmw.csv`
- **Size:** 10,781 listings, 9 columns
- **Columns:** model, year, price, transmission, mileage, fuelType, tax, mpg, engineSize
- **Missing values:** None

## Questions Answered

1. Which BMW models appear most in the used market?
2. How does price drop as mileage increases?
3. Which fuel type holds resale value better?
4. How does year of manufacture affect price?
5. Manual vs Automatic — which costs more?
6. Which model has the best fuel efficiency?

## Key Findings

- **3 Series dominates** the used market with 2,443 listings — nearly double the next model
- **Mileage and price have a -0.61 correlation** — strong negative relationship, more miles = significantly lower price
- **Hybrid BMWs hold value best** at £27,169 average vs £21,779 for Diesel
- **Newer models command far higher prices** — 2020 models average £35,377 vs £5,995 for 1996
- **Semi-Automatic is the most expensive** transmission type on average
- **5 Series is the most fuel efficient** at 62.1 mpg, X7 is the least at 31.8 mpg

## Charts

| Chart | Description |
|---|---|
| `01_model_counts.png` | Bar chart of listings per model |
| `02_price_vs_mileage.png` | Scatter plot of price vs mileage |
| `03_price_by_fuel.png` | Average price by fuel type |
| `04_price_by_year.png` | Average price trend by year |
| `05_price_by_transmission.png` | Average price by transmission type |
| `06_mpg_by_model.png` | Fuel efficiency by model |

## Tools Used

- Python 3
- Pandas — data loading, cleaning, groupby, aggregation
- Matplotlib — all charts saved as PNG
- OS — automated charts directory creation
- Jupyter Notebook — interactive analysis environment

## How to Run

```bash
git clone https://github.com/Navnith-7/bmw-used-car-analysis
cd bmw-used-car-analysis
pip install pandas matplotlib
jupyter notebook
```

Then open `analysis.ipynb` and run all cells.

## What's Next

This dataset is also ideal for a **price prediction model** using Scikit-learn (linear regression / random forest) — that will be the next project on my DS/ML roadmap.

## Author

**S Ritesh**  
AI & ML Engineering Student — New Horizon College of Engineering, Bengaluru  
[GitHub](https://github.com/Ritesh-2005-ritzz) • [LinkedIn](s-ritesh-b46162421)


