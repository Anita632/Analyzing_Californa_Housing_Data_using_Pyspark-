# Analyzing_Californa_Housing_Data_using_Pyspark
Project Overview
This project utilizes PySpark to analyze housing data from California, aiming to uncover insights into housing trends, pricing patterns, and demographic influences. The analysis is geared towards understanding the various factors that contribute to housing values and how they vary across different regions and demographics.

Objectives
The primary objectives of this analysis are to:

Investigate the relationships between housing characteristics and their corresponding values.
Identify patterns and trends in housing data over time.
Examine how demographic factors influence housing prices across different regions.
Problem Statements
Find the top regions or neighborhoods by median house value.
Analyze the distribution of median income by housing age bucket.
Examine the correlation between income and house value using income buckets.
Identify outliers in the "rooms per household" ratio.
Compute average "bedrooms per room" for each region.
Calculate population density (population per square unit) using latitude and longitude bins.
Measure year-to-year percentage growth in median house value per region.
Split house values into deciles and compute average features per decile.
Compare younger versus older houses in terms of price per room.
Perform regression residual analysis to find overvalued and undervalued areas.
Analyze temporal trends of income and house values over years.
Compute the "affordability index" (income-to-house-value ratio) per region.
Run K-Means clustering on features and profile each cluster.
Find nearest neighboring blocks and compare their house value differences.
Compute moving average of house values along longitude (spatial trend).
Compare house prices across low, medium, and high population density buckets.
Compare elasticities of house value with income and total bedrooms using correlations.
Create a histogram or bucket count of housing median age.
For each income decile, compute variance in house values to study price dispersion.
Compare border versus interior blocks within each region to detect "edge effects."
Dataset
The analysis is based on the California Housing dataset, which includes aggregated data from the 1990 census. Each record represents a block group and contains features such as geographic coordinates, median house age, total rooms, population, median income, and median house value.

Methodology
The analysis is conducted using PySpark to handle data manipulation and aggregation efficiently. The workflow includes:

Utilizing Spark DataFrames for robust, large-scale data processing.
Applying statistical functions to compute descriptive statistics.
Generating visualizations with libraries like Matplotlib and Seaborn after collecting aggregated data from Spark.
Getting Started
Prerequisites
Python (>=3.7)
Apache Spark
PySpark
Installation
Clone the repository to your local machine:

git clone https://github.com/smusab9152/Analyzing_Californa_Housing_Data_using_Pyspark.git
cd Analyzing_Californa_Housing_Data_using_Pyspark
Install the required Python packages:

pip install pyspark pandas matplotlib seaborn
Usage
To run the analysis, execute the main Jupyter Notebook or Python script. Ensure you have downloaded the California housing dataset and placed it in the appropriate directory as referenced in the code.

Tags
PySpark, Data Analysis, California Housing, Big Data, Apache Spark, Python, Data Visualization, Data Science, Exploratory Data Analysis
