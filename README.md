# Zomato_Data_Analysis


## Overview

**This project analyzes Zomato restaurant data to uncover trends related to ratings, cost distribution, online orders, and customer preferences.**


## Dataset

**1. Handling Missing Values:** Checked for and handled missing values in key columns.

**2. Cleaning the rate Column:** Converted ratings from a string format (e.g., "4.1/5") to a numerical float.


## Exploratory Data Analysis (EDA)

**1. Restaurant Types Distribution:**
                 Used a count plot to visualize the distribution of different types of restaurants.
                 
**2. Voting Distribution:**
              Grouped restaurants by type and plotted a line chart to analyze voting trends.  

**3. Rating Distribution:**
             Used a histogram and a KDE plot to visualize the distribution of ratings. 

**4. Online vs. Offline Order Ratings:**
                Used a boxplot to compare the ratings of restaurants that accept online orders vs. those that do not.

**5. Online vs. Offline Orders in Different Restaurant Types:**
                 Created a heatmap to analyze customer preferences for online/offline orders across different restaurant types.  

## Technologies Used 

**1. Python (Pandas, NumPy, Matplotlib, Seaborn)**

**2. Jupyter Notebook for data analysis and visualization**


## How to Run the Project

**Install required libraries:**
                             
                             pip install pandas numpy matplotlib seaborn

**Load the dataset into a Pandas DataFrame:**

                             import pandas as pd
                             Data = pd.read_csv("Zomato data.csv")

**Run the analysis scripts and generate visualizations**                             
                 

