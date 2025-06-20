**EDA on Meteorological Data**
This project performs an exploratory data analysis (EDA) on meteorological data to uncover patterns, trends, and insights related to weather conditions. The dataset includes various weather metrics such as temperature, humidity, wind speed, and more, recorded over time.

**Project Overview**
The goal of this project is to analyze historical weather data to understand:

Temperature variations over time

Humidity and wind speed trends

Relationships between different weather variables

Frequency of different weather conditions (e.g., cloudy, rainy)
**
Dataset**
The dataset used in this analysis is weatherHistory.csv, which contains the following columns:

Formatted Date: Timestamp of the weather recording

Summary: Brief description of weather conditions

Precip Type: Type of precipitation (rain, snow, etc.)

Temperature (C): Temperature in Celsius

Apparent Temperature (C): Perceived temperature

Humidity: Relative humidity

Wind Speed (km/h): Wind speed in kilometers per hour

Wind Bearing (degrees): Wind direction

Visibility (km): Visibility distance

Loud Cover: (Not specified in the dataset)

Pressure (millibars): Atmospheric pressure

Daily Summary: Summary of daily weather conditions

Key Findings
Top Weather Conditions: The most common weather conditions were "Partly Cloudy," "Mostly Cloudy," and "Overcast."

Temperature Trends: Analysis revealed variations in temperature and apparent temperature across different times.

Missing Data Handling: The dataset had some missing values in the Precip Type column, which were filled with the most frequent value.

Libraries Used
Pandas: For data manipulation and analysis

NumPy: For numerical operations

Matplotlib & Seaborn: For data visualization

Kaggle API: For downloading the dataset

How to Run the Code
Install Required Libraries:

bash
pip install pandas numpy matplotlib seaborn kaggle
Download the Dataset:

Ensure you have the Kaggle API set up.

Download the dataset using:

bash
kaggle datasets download -d muthuj7/weather-dataset
Extract the ZIP file to access weatherHistory.csv.

Run the Jupyter Notebook:

Open the notebook EDA-on-meteorological-data.ipynb in Jupyter.

Execute the cells sequentially to perform the EDA.

Code Structure
Data Loading: The dataset is loaded using Pandas.

Data Cleaning: Missing values are handled, and data types are corrected.

Exploratory Analysis: Basic statistics, visualizations, and insights are generated.

Visualizations: Plots are created to illustrate trends and relationships.

Example Visualizations
Temperature vs. Apparent Temperature: A scatter plot showing the relationship between actual and perceived temperatures.

Humidity Distribution: A histogram displaying the frequency of different humidity levels.

Wind Speed Over Time: A line plot showing wind speed variations.

Challenges
Missing Data: Handling missing values in the Precip Type column.

Data Type Conversion: Converting columns like Formatted Date to datetime objects for better analysis.

Future Work
Time Series Analysis: Deeper analysis of trends over time.

Machine Learning: Predicting weather conditions based on historical data.

Geospatial Analysis: If location data is available, mapping weather patterns.

Acknowledgments
Dataset sourced from Kaggle: Weather Dataset.

Special thanks to the open-source community for tools and libraries used in this project.

