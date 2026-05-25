# Flight-Data-Analysis
Data science school project using Python and Jupyter to analyze flight booking data and predict airline ticket prices with machine learning.

## Project Structure
``` 
flight-price-analysis/
│
├── data/
│   └── flights.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_visualization.ipynb
│   ├── 03_regression_models.ipynb
│   ├── 04_classification_models.ipynb
│   └── 05_model_optimization.ipynb
|
├── report/
│   └── final_report.ipynb
|
├── images/
├── models/
├── requirements.txt
├── README.md
└── LICENSE
```

## The main objectives of this project are:

- Analyze factors influencing flight ticket prices
- Build predictive models to estimate flight prices
- Study how different variables affect ticket pricing
- Compare different machine learning algorithms
- Perform model evaluation and optimization

## Research Questions

This study aims to answer the following questions:

- Does the price vary depending on the airline company?
- How is the price affected when tickets are booked 1 or 2 days before departure?
- Does the ticket price change based on departure and arrival time?
- How does the price vary with different source and destination cities?
- How does the ticket price differ between Economy and Business class?

## Dataset Description

The dataset was collected using web scraping (Octoparse) from the Ease My Trip website. It contains flight booking information between major metropolitan cities in India.

- Total records: 300,261
- Number of features: 11
- Data collection period: 50 days (11 February to 31 March 2022)
- Source: Ease My Trip (secondary data)
