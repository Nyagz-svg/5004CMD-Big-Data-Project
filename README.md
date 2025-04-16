# 5004CMD Big Data Programming Project

This repository contains my coursework for the Coventry University module **5004CMD – Big Data Programming (2024/25)**.

## Project Description
The project analyses large-scale mobility datasets to identify weekly travel patterns, compare serial vs parallel processing, and build predictive models of population mobility using Dask and Scikit-learn.

## Files
- `BigData_Analysis_Notebook.ipynb`: Full code for data cleaning, categorisation, processing, modelling, and visualisation.
- `Trips full data.csv`: Main dataset with weekly trip counts.
- `Trip by dataset.csv`: Detailed trip data by distance bands.
- `output_plot.png`: Sample plot from regression analysis.

## ⚙️ Requirements
- Python 3.9+
- `dask`, `pandas`, `matplotlib`, `scikit-learn`

## Result Summary
- R² = 0.9884 from linear regression
- Serial faster than parallel due to Dask setup overhead on small dataset

## How to Run
Open `BigData_Analysis_Notebook.ipynb` in Jupyter Notebook or VS Code and run each cell sequentially.

## Author
Daniel Olatude| Coventry University | 2024/25
