# Black Friday Sales Data — Exploratory Data Analysis & Insights

This repository contains an end-to-end **Exploratory Data Analysis (EDA)** project on the Black Friday sales dataset. The goal is to extract actionable insights, visualize customer buying behavior, and uncover patterns that can inform retail marketing and inventory strategies.

## 🛍️ Project Objective

- **Understand purchasing trends** during the Black Friday period.
- **Analyze customer demographics** and their spending behavior.
- **Identify key features** that influence sales value.
- **Build visual narratives** to support data-driven retail decisions.

## 📊 Dataset Overview

- The dataset contains transaction records from an e-commerce retailer during Black Friday sales.
- Key fields include:
  - `User_ID`, `Product_ID`
  - Customer demographics (Gender, Age, City Category)
  - Purchase amount
- Dataset size: ~550k transactions

## 🧠 Key Technologies Used

| Task | Tools & Libraries |
|------|------------------|
| Data Wrangling | Python, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistical Summary | Pandas profiling / manual aggregates |
| Reporting | Jupyter Notebook |

## 🔍 Analysis Workflow

1. **Data Cleaning**
   - Identify and handle missing values
   - Check and correct data types
   - Remove duplicates and anomalies

2. **Exploratory Analysis**
   - Distribution of purchase amounts
   - Customer segmentation by age, gender, and city
   - Product category analysis

3. **Feature Exploration**
   - Correlation analysis
   - Cross-tabulations and group aggregations
   - Visual trends across categories

4. **Visualization & Insights**
   - Bar plots, histograms, box plots
   - Heatmaps and relationship charts
   - Trend identification and narrative building

## 📌 Key Insights

- **Top spending segments** based on demographics
- Seasonal or category-based purchasing patterns
- High impact features on purchase value
- Customer behavior trends informing upsell/cross-sell strategies

## 📁 Repository Structure
Black-Friday-DataAnalysis/
│
├── data/
│ ├── train.csv
│ └── test.csv
│
├── notebooks/
│ ├── BlackFriday_EDA.ipynb
│ └── Visualizations.ipynb
│
├── reports/
│ └── figures/
│
├── requirements.txt
├── README.md
└── LICENSE
