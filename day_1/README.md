# Software Engineering for Data Scientists

This training is designed to help Data Scientists gain valuable skills in Software Engineering.

## 1. Description

### 1.1 Business case

The demo project used to make you practice the training's concepts is about predicting future sales for a **fictive retail company named ACME Inc.**

Based on historical data, our ML model must be able to predict the sales volume for a given product, **for the coming week.**

### 1.2 Data

The `data/` directory contains fake data representing ACME Inc.'s sales on a 3-year period.
 
- `products.csv` contains a list of 100 products, sold in different stores,
- `sotres.csv` contains a list of 10 stores which sell the aforementioned products,
- `transactions.csv` contains more than 1 million data points from May 2016 to May 2019, listing how many units of a given product where sold in a given store on a given day.

`NOTE`

> This data is totally fake. Consequently, the evaluation metrics values are meaningless. The goal is not to improve them!


## 2. Training workflow

A Jupyter Notebook `notebook.ipynb` has been created, and is available in the root directory. 

This notebook contains R&D code that implements a full Data Science workflow, from data ingestion, to data processing, to feature engineering, to model fitting.

The notebook code is light-years away from being "production ready"! It is hard to read, hard to understand, and trying to maintain this code and make it evolve in a production environment would be close to impossible.

**The goal of this training is to create a viable software project based on this draft notebook.**


