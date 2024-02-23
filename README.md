# Industrial-Human-Resource-Geo-Visualization

## Overview
- [Technologies] Technologies
- [Domain] Domain
- [Problem Statement] Problem Statement
- [Approach] Approach
- [Technologies Used] Technologies Used
- [Project Structure] Project Structure
- [Usage] Usage
- [Contributing] Contributing

## Technologies
- Exploratory Data Analysis (EDA)
- Data Visualization
- Natural Language Processing (NLP)

## Domain
Resource Management

## Problem Statement
In India, understanding the industrial distribution of the workforce is crucial for comprehending the economic landscape and employment trends across various sectors. The classification of main and marginal workers, categorized by sex and by section, division, and class, provides insights into the employment scenario. However, the existing data on this classification is outdated, raising the need for an updated analysis. This project aims to refresh information on the industrial classification of workers, other than cultivators and agricultural laborers, by sex and by section, division, and class. The goal is to provide accurate and relevant data for policy-making and employment planning.

## Approach
- Data Integration: Merge provided CSV data files to create a comprehensive DataFrame.
- Data Processing and Exploration: Conduct classical machine learning tasks, including data exploration, cleaning, and feature engineering.
- Natural Language Processing (NLP): Utilize NLP techniques to analyze various core industries, grouping business categories like Retail, Poultry, Agriculture, and Manufacturing.
- Model Building: Implement machine learning models to gain insights into the workforce distribution.
- Geo-Visualization: Develop an interactive map to visualize the industrial workforce distribution across different states.

## Technologies Used
- Python
- Streamlit
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Plotly

## Project Structure
- data: Contains CSV files for different states.
- app.py: Streamlit application for data exploration, cleaning, statistical metrics, feature engineering, and data visualization.
- requirements.txt: Lists all dependencies required for the project.

## Usage
- Data Exploration: Explore the loaded dataset, identify numerical columns, and visualize the distribution of selected columns.
- Data Cleaning: Clean the dataset, handle missing values, and normalize data.
- Statistical Metrics: View count of null values, mean values, median values, standard deviation, quantiles, and correlation matrix.
- Feature Engineering: Visualize the distribution of numerical variables, evaluate a linear regression model, and assess model metrics.
- Data Visualization: Choose a column and visualize it using either a histogram or a bar chart.

## Contributing
Contributions to enhance the functionalities or fix issues are welcome. Fork the repository, make your changes, and submit a pull request.
