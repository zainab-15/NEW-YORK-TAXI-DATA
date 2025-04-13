# NEW-YORK-TAXI-DATA

## New York Taxi Data Analysis

This project explores the New York City Yellow Taxi trip data for September 2015, aiming to understand taxi usage patterns and factors influencing demand. Through exploratory data analysis (EDA) and regression modeling, we seek insights into pickup/drop-off hotspots, peak hours, and trip durations.

## Project Overview

Public transportation is vital in metropolitan areas like New York City. Taxis serve as a crucial mode of conveyance, often preferred by the public for their convenience. This project delves into the NYC Yellow Taxi data to:
	•	Identify areas with the highest pickup and drop-off frequencies.
	•	Determine peak hours for taxi usage. ￼
	•	Analyze trip durations and distances. ￼
	•	Understand factors influencing taxi demand. ￼

## Repository Structure

The repository comprises the following key files:
	•	EDA.ipynb: Notebook performing exploratory data analysis, including data cleaning, visualization, and initial insights.
	•	Linear_KNN_Regression.ipynb: Applies Linear and K-Nearest Neighbors regression models to predict trip durations.
	•	Multiple_Linear_Regression.ipynb: Implements multiple linear regression to model trip duration based on various features.
	•	geo_export_*.{shp,shx,dbf,prj}: Geospatial files representing NYC taxi zones, useful for mapping and spatial analysis.

## Technologies Used
	•	Programming Language: Python
	•	Libraries:
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn
	•	GeoPandas
	•	IPython Widgets

## Data Source

The dataset used is the NYC Yellow Taxi Trip Data for September 2015, which includes:
	•	Pickup and drop-off timestamps
	•	Pickup and drop-off locations
	•	Trip distances
	•	Fare amounts
	•	Passenger counts

This data is publicly available through the NYC Taxi & Limousine Commission.

## Key Insights

Through our analysis, we aim to uncover:
	•	The most frequented pickup and drop-off locations.
	•	Time periods with the highest taxi demand.
	•	Average trip durations and distances.
	•	Factors that significantly impact trip duration and fare.



	1.	Install the required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn geopandas ipywidgets

	2.	Run the notebooks:
Open the Jupyter notebooks (.ipynb files) in your preferred environment to explore the analysis and models.



Note: This project is an initial exploratory analysis and serves as a foundation for more advanced modeling and predictive analytics.
