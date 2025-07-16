# Airbnb-investment-analysis
Using Los Angeles Airbnb data, I pinpointed top properties for my stakeholder to invest in. 

This project focuses on cleaning, exploring, and analyzing property-level listing data to extract actionable insights. The dataset represents real estate listings, and the notebook walks through structured steps to identify missing values, explore trends, and prepare the data for further modeling or business intelligence reporting.

Project Structure
Notebook: 
General market analysis.ipynb
Property level analysis.ipynb
Text EDA.ipynb (data cleaning for further sentiment analysis) 
Dataset: listing.csv

Features & Workflow
1. Data Import & Inspection
Loaded listing.csv into a pandas DataFrame.

Verified data types and structure.

2. Missing Data Handling
Standardized missing values (?, NULL, NA, "") to np.nan.

Assessed missingness across all columns using df.isnull().sum().

3. Exploratory Data Analysis (EDA)
Visualized data using Seaborn and Matplotlib.

Inspected distributions, correlations, and potential outliers.
