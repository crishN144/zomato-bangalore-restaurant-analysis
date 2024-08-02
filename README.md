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

<div align="center">
    <img width="545" alt="Impact of Table Booking Facility on Restaurant Ratings" src="https://github.com/user-attachments/assets/9ff51ba6-1c34-41fd-a723-418491e0bebe">
    <p><strong>Effect of Table Booking Facilities on Restaurant Ratings</strong></p>
</div>

#### Description:
This bar graph illustrates the relationship between restaurant ratings and the availability of a table booking facility. The x-axis represents different rating levels, while the y-axis shows the number of restaurants with and without a booking table facility, represented by different colors (pink and purple). The stacked bar format highlights the proportion of ratings within each category.

**Conclusion**: The data suggests that restaurants offering a table booking facility tend to receive higher ratings compared to those without such a facility. This may indicate a positive correlation between the availability of booking options and customer satisfaction.

### 2. Geographic Distribution of Restaurants by City

<div align="center">
    <img width="519" alt="Number of Restaurants by City" src="https://github.com/user-attachments/assets/8450bba5-9269-4d9d-af0b-0b494034fe75">
    <p><strong>Number of Restaurants by City</strong></p>
</div>

#### Description:
To understand the geographic distribution of restaurants, we first sorted the data to find the number of restaurants listed in each city. The bar graph above illustrates the count of restaurants across various cities, with BTM leading, followed by Bannerghatta Road and Brigade Road.

In the subsequent part of our analysis, we visualize this data geographically using a heatmap. This helps identify clusters and the density of restaurants in different areas, highlighting key locations such as Victoria Layout and Koramangala, while confirming that BTM has the highest concentration of restaurants.

In part two of our objective, we will identify popular cuisines in different cities by examining the number of restaurants offering each cuisine. The following section will present the code snippet used to identify these popular cuisines.

### 3. Most Popular Cuisines Offered by Restaurants

<div align="center">
    <img width="502" alt="Most Popular Cuisines Offered by Restaurants" src="https://github.com/user-attachments/assets/4e9542a4-3939-41fe-96e0-569d61cfcb1a">
    <p><strong>Top 10 Most Offered Cuisines by Restaurants</strong></p>
</div>

#### Description:
This bar graph highlights the top 10 most offered cuisines across restaurants. The x-axis represents different cuisine types, while the y-axis shows the number of restaurants offering each cuisine. The graph clearly indicates that 'North Indian' cuisine is the most popular, as most restaurants feature it.

<p>This bar graph illustrates restaurants' top 10 most offered cuisines. The x-axis represents different cuisine types, while the y-axis shows the number of restaurants that offer each cuisine. The graph reveals that 'North Indian' cuisine is the most frequently offered, indicating a high demand for this cuisine in the city.</p>

### 4. Most Liked Dishes According to Number of Restaurants

<div align="center">
    <img width="536" alt="Most Liked Dishes According to Number of Restaurants" src="https://github.com/user-attachments/assets/24c3bc25-59ab-4b30-88d6-286da9f165fe">
    <p><strong>Top Liked Dishes as Per Restaurant Listings</strong></p>
</div>

#### Description:
This bar graph displays the top 25 most liked dishes based on the number of restaurants offering them. The x-axis represents different dishes, while the y-axis indicates the number of restaurants that feature each dish. The graph highlights that 'Pasta' is the most liked dish, as it appears in the highest number of restaurant menus.

### 5. Distribution of Ratings in the Dataset

<div align="center">
    <img width="506" alt="Distribution of Ratings in the Dataset" src="https://github.com/user-attachments/assets/1e53f5c7-807d-4041-8359-10918827a411">
    <p><strong>Overview of Rating Frequencies in the Dataset</strong></p>
</div>

#### Description:
This histogram provides a visualization of the ratings distribution from the `df-recommendation` dataset. The x-axis represents the rating values, while the y-axis shows the count of occurrences for each rating.

**Findings**: 
- The distribution indicates that the highest rating in the dataset is approximately **3.6 out of 5**.
- There is a notable concentration of ratings around this value, suggesting that the majority of ratings are clustered near the mid-range of the scale.

### 6. Votes vs. Rating Analysis

<div align="center">
    <img width="509" alt="Votes vs. Rating Analysis" src="https://github.com/user-attachments/assets/11fb66b1-d69e-4180-acb6-ef50def110e6">
    <p><strong>Relationship Between Votes and Ratings</strong></p>
</div>

#### Description:
This scatter plot examines the relationship between the number of votes and the rating scores in the `df_recommendation` dataset. The x-axis represents the number of votes, while the y-axis shows the corresponding ratings.

**Findings**:
- The plot reveals that **buffet meals** receive the highest number of votes compared to other meal types.
- This suggests a strong correlation between meal type and the amount of feedback, with buffets being particularly popular among diners.


## Conclusion

This comprehensive analysis of Bangalore's restaurant scene using Zomato data has revealed several key insights:

1. **Geographic Insights**: BTM, Bannerghatta Road, and Brigade Road emerged as restaurant hotspots, offering potential opportunities for new establishments or targeted marketing.

2. **Cuisine Preferences**: North Indian cuisine dominates the market, while pasta stands out as the most liked dish. This information can guide menu planning for new and existing restaurants.

3. **Online Services Impact**: Restaurants offering online ordering tend to have higher ratings, emphasizing the importance of digital integration in today's food service industry.

4. **Pricing Strategy**: The optimal price range for restaurants appears to be between 300-1200 INR for two people, balancing affordability with quality perceptions.

5. **Customer Engagement**: Higher-rated restaurants generally have more customer votes, suggesting a correlation between perceived quality and customer interaction.

6. **Restaurant Types**: Quick Bites and Casual Dining are the most common restaurant types, reflecting Bangalore's fast-paced urban lifestyle.

These findings provide valuable insights for restaurant owners, food entrepreneurs, and market analysts, offering data-driven guidance for decision-making in Bangalore's competitive restaurant industry.

## How to Use

To explore and utilize this project:

1. **Clone the Repository**:
   ```
   git clone https://github.com/crishN144/zomato-bangalore-restaurant-analysis.git
   cd zomato-bangalore-restaurant-analysis
   ```

2. **Set Up the Environment**:
   - It's recommended to use a virtual environment:
     ```
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```
   - Install required dependencies:
     ```
     pip install -r requirements.txt
     ```

3. **Run the Analysis**:
   - Open Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - Navigate to and open `zomato_bangalore_analysis.ipynb`
   - Run the cells sequentially to reproduce the analysis

4. **Explore Interactive Features**:
   - Use the recommendation system by inputting your preferences when prompted
   - Interact with the Folium maps to explore geographic distributions

5. **Modify and Extend**:
   - Feel free to modify parameters, add new analyses, or apply the techniques to different datasets

## Future Work

To further enhance this project, the following future works are proposed:

**Sentiment Analysis on User Reviews**:
   - Implement natural language processing techniques to analyze the sentiment of user reviews.
   - Identify common themes in positive and negative feedback.
   - Correlate sentiment scores with restaurant ratings and popularity.



