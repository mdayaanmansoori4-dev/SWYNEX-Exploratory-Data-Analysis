# Exploratory Data Analysis: NYC Airbnb 2019

**Author:** Mohd Aayan

## Dataset
AB_NYC_2019_cleaned.csv — cleaned in Task 1 (48,870 listings, 16 columns)

## Tools
Python, pandas, matplotlib, Jupyter Lab

## Insights

1. **Manhattan is by far the most expensive borough** — averages 196.89 USD/night, nearly 60% higher than Brooklyn (124.45 USD) and more than double the Bronx (87.58 USD).

2. **Entire homes dominate listings and command the highest prices** — over half of all listings (25,398) are entire homes, averaging 211.82 USD/night, more than double a private room.

3. **Over a third of listings are inactive** — 17,530 listings (36%) show 0 days of availability, suggesting many listings are paused or rarely rented.

4. **Mid-priced listings get the most reviews, not the cheapest ones** — overall correlation between price and reviews is nearly zero, but listings priced 51–100 USD average the most reviews (26.1), dropping off sharply above 200 USD.

5. **Listing volume and price don't move together across top neighbourhoods** — Williamsburg has the most listings (3,917) but ranks only 6th in price; Midtown has the fewest listings in the top 10 but the highest average price (282.74 USD).

## Files
- `data/AB_NYC_2019_cleaned.csv` — cleaned dataset (from Task 1)
- `eda.ipynb` — full analysis notebook with charts and explanations