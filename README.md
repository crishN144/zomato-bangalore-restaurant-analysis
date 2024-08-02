# Dining Data Delights: Zomato Bangalore Restaurant Analysis & Recommendation System

## Project Overview

This project conducts a comprehensive analysis of Bangalore's restaurant scene using Zomato data. It aims to provide insights for food enthusiasts, entrepreneurs, and data analysts through various analytical approaches.

### What Was Done

- **Data Cleaning and Preprocessing**: Handled missing values, standardized formats, and prepared the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Investigated patterns in cuisine popularity, pricing, and customer preferences.
- **Geospatial Analysis**: Created interactive maps to visualize restaurant distributions and cuisine hotspots.
- **Recommendation System**: Developed a user-friendly tool for suggesting top restaurants based on user preferences.
- **Multi-Criteria Decision Analysis (MCDA)**: Implemented a scoring system to identify Bangalore's best restaurants.

### Key Findings

- BTM has the highest concentration of restaurants, followed by Bannerghatta Road and Brigade Road.
- North Indian cuisine is the most offered, with Pasta being the most liked dish across restaurants.
- Online ordering correlates positively with higher ratings, suggesting its importance in customer satisfaction.
- The optimal price range for new restaurants is between 300-1200 INR for two people.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization (Matplotlib, Seaborn)
- Geospatial Analysis (Folium)
- Statistical Analysis
- Machine Learning (Recommendation System)
- Multi-Criteria Decision Analysis

## Dataset

### Description

[Download Dataset from Dropbox](https://www.dropbox.com/scl/fi/sjjj6sos7m3g45vkv7c5x/zomato.csv?rlkey=ypi0rhqoi3aef7uls0px4rupf&st=nzf5f10x&dl=0)


The dataset, sourced from Zomato, contains information about restaurants in Bangalore, India. It includes details such as restaurant names, locations, cuisines, ratings, and more.

### Key Attributes

| Attribute Name | Description | Data Type | Example Value |
|----------------|-------------|-----------|---------------|
| `name` | Name of the restaurant | String | Jalsa |
| `location` | Area of the restaurant | String | Banashankari |
| `cuisines` | Types of cuisine offered | String | North Indian, Mughlai, Chinese |
| `rate` | Restaurant rating | Float | 4.1 |
| `votes` | Number of customer votes | Integer | 775 |
| `approx_cost(for two people)` | Approximate cost for two people | Integer | 800 |
| `online_order` | Availability of online ordering | Boolean | Yes |
| `book_table` | Availability of table booking | Boolean | Yes |

## Visualizations

### 1. Impact of Table Booking Facility on Restaurant Ratings

<img width="545" alt="Impact of Table Booking Facility on Restaurant Ratings" src="https://github.com/user-attachments/assets/9ff51ba6-1c34-41fd-a723-418491e0bebe">

<p align="center"><strong>Effect of Table Booking Facilities on Restaurant Ratings</strong></p>


#### Description:
This bar graph illustrates the relationship between restaurant ratings and the availability of a table booking facility. The x-axis represents different rating levels, while the y-axis shows the number of restaurants with and without a booking table facility, represented by different colors (pink and purple). The stacked bar format highlights the proportion of ratings within each category.

**Conclusion**: The data suggests that restaurants offering a table booking facility tend to receive higher ratings compared to those without such a facility. This may indicate a positive correlation between the availability of booking options and customer satisfaction.

### 2. Geographic Distribution of Restaurants by City

![Number of Restaurants by City](https://github.com/user-attachments/assets/8450bba5-9269-4d9d-af0b-0b494034fe75)

<p align="center"><strong>Number of Restaurants by City</strong></p>

### Description:
To understand the geographic distribution of restaurants, we first sorted the data to find the number of restaurants listed in each city. The bar graph above illustrates the count of restaurants across various cities, with BTM leading, followed by Bannerghatta Road and Brigade Road.

In the subsequent part of our analysis, we visualize this data geographically using a heatmap. This helps identify clusters and the density of restaurants in different areas, highlighting key locations such as Victoria Layout and Koramangala, while confirming that BTM has the highest concentration of restaurants.

In part two of our objective, we will identify popular cuisines in different cities by examining the number of restaurants offering each cuisine. The following section will present the code snippet used to identify these popular cuisines.
