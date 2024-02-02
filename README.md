# Apartment Rental Data Analysis and Modeling

## Project Overview

This GitHub repository contains a comprehensive analysis and modeling project focused on apartment rental data in Poland, with a particular emphasis on Warsaw. The project aims to provide valuable insights for individuals seeking apartments for rent and landlords looking to optimize rental prices. The analysis is divided into three main projects, each addressing specific aspects:

### Project 1: Exploratory Data Analysis (EDA) - Warsaw Apartment Prices

In this project, I conducted exploratory data analysis on apartment rental prices in Warsaw using data provided by Krzysztof Jamroz. The dataset includes various features such as apartment size, number of rooms, location coordinates, and more. The key steps and technologies used in this analysis include:

#### Technologies and Libraries Used:
- Python
- Jupyter Notebooks
- pandas for data manipulation
- seaborn and matplotlib for data visualization
- numpy for numerical operations
- missingno for visualizing missing data patterns
- folium for interactive map creation

#### Project Steps:
1. **Data Import**: Loaded apartment rental data from CSV files for November 2023, December 2023, and January 2024.
2. **Data Cleaning**: Handled missing values, converted categorical variables to numerical ones, and dropped irrelevant columns.
3. **Exploratory Data Analysis (EDA)**: Explored various aspects of the dataset, including distribution of apartment prices, correlations between features, and geographical patterns.
4. **Visualization**: Created visualizations such as histograms, heatmaps, and scatter plots to better understand the data.
5. **Interactive Map**: Integrated an interactive map using folium to visualize apartment prices based on location.

### Project 2: Interactive Tableau Map - Warsaw Apartment Prices

This project focuses on creating an interactive map using Tableau to provide a user-friendly interface for exploring apartment prices in Warsaw. The Tableau map complements the EDA conducted in Project 1, allowing users to interactively explore rental prices based on different parameters.

#### Technologies and Tools Used:
- Tableau for data visualization
- Data exported from Project 1

#### Project Steps:
1. **Data Export**: Used the cleaned and analyzed data from Project 1.
2. **Tableau Map Creation**: Developed an interactive map in Tableau to visualize apartment prices based on location, size, and other relevant factors.
3. **User Interface**: Enabled users to dynamically explore and filter apartment prices using the Tableau interface.

### Project 3: Predictive Modeling - Apartment Rental Price Prediction

In this project, I built a predictive model using a Random Forest Regressor to estimate apartment rental prices across Poland. The model takes various features into account, providing a tool for landlords to set optimal rental prices and potential tenants to estimate expected costs.

#### Technologies and Libraries Used:
- Python
- Jupyter Notebooks
- pandas for data manipulation
- seaborn and matplotlib for data visualization
- scikit-learn for machine learning
- numpy for numerical operations

#### Project Steps:
1. **Data Import**: Loaded apartment rental data from CSV files.
2. **Data Cleaning**: Applied similar data cleaning steps as in Project 1.
3. **Feature Engineering**: Converted categorical variables to numerical ones, handled missing values, and removed outliers.
4. **Machine Learning Model**: Implemented a Random Forest Regressor to predict apartment rental prices.
5. **Model Evaluation**: Assessed the model's performance and identified key features influencing rental prices.

## Repository Structure

- **Project_1_EDA_Warsaw_Apartment_Prices.ipynb**: Jupyter Notebook containing the code and analysis for the exploratory data analysis in Warsaw.
- **Project_2_Tableau_Map_Warsaw_Apartment_Prices.twbx**: Tableau Workbook file for the interactive map project.
- **Project_3_Rental_Price_Prediction.ipynb**: Jupyter Notebook with the code for building the Random Forest Regressor model.

Feel free to explore the code, visualizations, and findings in each project to gain insights into apartment rental prices in Poland. If you have any questions or suggestions, please don't hesitate to reach out!
