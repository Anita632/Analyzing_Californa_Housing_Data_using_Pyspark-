#  Analyzing California Housing Data using PySpark

##  Project Overview
This project uses **PySpark** to analyze the **California Housing Dataset** and uncover insights into housing trends, pricing patterns, and demographic influences.  
The goal is to understand how location, income, population, and housing characteristics impact **median house values** across California.

---

##  Objectives
The primary objectives of this analysis are to:

- Investigate relationships between housing characteristics and house values  
- Identify pricing patterns and trends across regions  
- Examine the impact of demographic factors on housing prices  

---

##  Problem Statements
This project answers the following analytical questions:

1. Identify top regions by **median house value**
2. Analyze **median income distribution** by housing age buckets
3. Examine **income vs house value correlation**
4. Detect outliers in **rooms per household**
5. Compute **bedrooms-to-rooms ratio** by region
6. Calculate **population density** using latitude–longitude bins
7. Measure **year-to-year growth** in median house value
8. Split house values into **deciles** and analyze feature averages
9. Compare **younger vs older houses** on price per room
10. Perform **regression residual analysis** to detect over/undervalued regions
11. Analyze **temporal trends** in income and housing prices
12. Compute **affordability index** (income-to-house-value ratio)
13. Apply **K-Means clustering** and profile clusters
14. Find **nearest neighboring blocks** and compare price differences
15. Compute **spatial moving averages** along longitude
16. Compare house prices across **population density buckets**
17. Analyze **price elasticities** using correlations
18. Create **histogram of housing median age**
19. Measure **price dispersion** using variance per income decile
20. Detect **border vs interior block effects**

---

##  Dataset
The analysis is based on the **California Housing Dataset** derived from the **1990 U.S. Census**.

Each record represents a **block group** and includes:
- Latitude & Longitude  
- Median house age  
- Total rooms & bedrooms  
- Population & households  
- Median income  
- Median house value  

---

##  Methodology
The analysis is performed using **PySpark** for scalable data processing.

Key steps include:
- Using **Spark DataFrames** for transformations and aggregations  
- Applying **statistical functions** for descriptive analysis  
- Collecting aggregated data from Spark for visualization  
- Creating plots using **Matplotlib** and **Seaborn**  

---

## Getting Started

### 🔧 Prerequisites
- Python **3.7+**
- Apache Spark
- PySpark

---
## Install Dependencies 
pip install pyspark pandas matplotlib seaborn

## Usage

Run the main Jupyter Notebook or Python script

Download the California Housing dataset

Place the dataset in the directory referenced in the code

 ## Tags

PySpark Apache Spark Big Data Data Analysis California Housing
Exploratory Data Analysis Data Science Python Data Visualization
