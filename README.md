# T-Bank Travel Product Analytics

Exploratory product analysis of the T-Bank Travel service based on the public DANO 2024 dataset.

## Project goal

Analyze customer and order data, identify behavioral patterns, segment users, formulate product hypotheses, and design an experiment for the most promising hypothesis.

## Dataset

The analysis is based on the public DANO 2024 dataset for the T-Bank Travel case.

- Source: https://dano.hse.ru/data2024
- Dataset size: 835,938 rows and 56 features
- Products analyzed: airline tickets and hotels

The raw dataset is not stored in this repository because of its size.  
The notebook downloads the original public dataset automatically from the DANO Google Drive source.

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Exploratory Data Analysis
- Customer Segmentation
- Product Hypotheses
- A/B Test Design

## Analysis

The project includes:

- data quality and structure checks;
- analysis of missing values, duplicates and data types;
- order and customer behavior analysis;
- separation of orders and potential customers;
- customer-level analytical dataset;
- segmentation of hotel and airline customers;
- analysis of incentive usage;
- comparison of customer characteristics;
- formulation and prioritization of product hypotheses;
- A/B test design for the selected hypothesis.

## Key results

- Analyzed 835,938 records with 56 features.
- Identified 786,885 orders and 49,053 potential customers.
- Built a customer-level dataset containing 96,019 unique users.
- Compared behavior across airline and hotel customer segments.
- Analyzed the relationship between customer characteristics and incentive usage.
- Formulated product hypotheses and designed an A/B test for the selected initiative.

## Repository structure

```text
product-analytics-tbank-travel/
├── images/          # Charts used in the analysis
├── notebooks/
│   └── tbank_travel_analysis.ipynb
├── .gitignore
└── README.md
