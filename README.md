# Apartment Rental Data Analysis and Modeling

## Project Overview

This GitHub repository focuses on analyzing apartment rental prices in Poland. The project aims to provide insights for potential renters to understand pricing factors and for landlords to set competitive rental prices. The repository includes three main projects:

1. Exploratory data analysis for apartment prices in Warsaw
2. Random Forest model for predicting prices of apartments for rent in Poland
3. An interactive map in Tableau with apartment prices in Warsaw

## Repository Structure:
.  
├── data  
│   ├── raw  
│   │   ├── apartments_rent_pl_2023_12.csv  
│   │   ├── apartments_rent_pl_2024_01.csv  
│   │   └── apartments_rent_pl_2023_11.csv  
│   └── processed  
│       ├── Poland_rent_cleaned.csv  
│       └── Warsaw_rent_cleaned.csv  
├── notebooks  
│   ├── Project2_Random Forest - predicting apartment prices.ipynb  
│   └── Project1_Apartments for rent in Warsaw EDA.ipynb  
└── tableau-visualizations  
    └── Project3_Apartment Rental Prices in Warsaw Map.twbx  

## Data Source:

[Apartment Prices in Poland - Kaggle](https://www.kaggle.com/datasets/krzysztofjamroz/apartment-prices-in-poland)

## Project 1: Exploratory Data Analysis (EDA) - Warsaw Apartment Prices

This project involves exploratory data analysis of apartment rental prices in Warsaw. The dataset includes features such as apartment size, number of rooms, location coordinates, etc.

### Technologies and Libraries Used:

- Python
- Jupyter Notebooks
- pandas, seaborn, and matplotlib for data manipulation and visualization
- numpy for numerical operations
- missingno for visualizing missing data patterns
- folium for interactive map creation

### Project Steps:

1. **Data Import**
2. **Data Cleaning**
3. **Exploratory Data Analysis (EDA)**
4. **Visualization**
5. **Interactive Map**

## Project 2: Predictive Modeling - Apartment Rental Price Prediction

This project involves building a predictive model using a Random Forest Regressor to estimate apartment rental prices across Poland.

### Technologies and Libraries Used:

- Python
- Jupyter Notebooks
- pandas, seaborn, and matplotlib for data manipulation and visualization
- scikit-learn for machine learning
- numpy for numerical operations

### Project Steps:

1. **Data Import**
2. **Data Cleaning**
3. **Machine Learning Model - Random Forest Regressor**
4. **Model Evaluation**

## Project 3: Interactive Tableau Map - Warsaw Apartment Prices

This project focuses on creating an interactive map using Tableau to provide a user-friendly interface for exploring apartment prices in Warsaw. The Tableau map complements the EDA conducted in Project 1, allowing users to interactively explore rental prices based on different parameters.

### Technologies and Tools Used:

- Tableau for data visualization
- Data exported from Project 1
