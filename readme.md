# Netflix and Airbnb data analysis

Two notebooks from the AICTE and VOIS data analytics programme (October 2025). Certificates are in this repo too.

## Netflix (`VaikhashiA_NetflixDataAnalysisSourcecode.ipynb`)

Cleaned the Netflix titles dataset and kept titles released between 2008 and 2021, which left 7,779 records. Then:

- Movies vs TV shows by release year. Movies peak at 1,498 titles in 2019, TV shows at 697 in 2020.
- Top 10 genres. International Movies (2,437), Dramas (2,108) and Comedies (1,472) lead.

## Airbnb (`VaikhashiA_Airbnbsourcecode.ipynb`)

The Airbnb Open Data file has 102,599 listings and 26 columns. I cleaned the price column and looked at:

- listings by room type and by neighbourhood group
- the 10 most expensive neighbourhoods on average
- room type vs price
- hosts with the most listings
- review scores for verified vs unverified hosts

## Running it

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

The datasets aren't in the repo. Netflix: [Kaggle, Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows). Airbnb: the Airbnb Open Data CSV on Kaggle.
