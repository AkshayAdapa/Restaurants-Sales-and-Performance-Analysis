# Restaurants Sales Analysis Project

## Overview

This project, conducted during my internship at Cognifyz Technologies, focuses on analyzing restaurant sales data to gain insights into various aspects such as ratings, cuisine combinations, geographic distribution, and more. The project is divided into multiple levels, each containing specific tasks aimed at uncovering valuable information from the dataset.

## Technologies Used

- **Python**: Programming language used for data analysis and visualization.
- **Pandas**: Library for data manipulation and analysis.
- **Matplotlib**: Library for data visualization.
- **Seaborn**: Library for statistical data visualization.
- **Geopandas**: Library for geographic data analysis.
- **Folium**: Library for interactive map visualizations.
- **NLTK**: Natural Language Toolkit for text processing and sentiment analysis.
- **WordCloud**: Library for generating word cloud visualizations.
- **DBSCAN**: Density-Based Spatial Clustering of Applications with Noise for clustering analysis.

## Table of Contents

- [Project Structure](#project-structure)
  - [Level 1: Initial Data Exploration](#level-1-initial-data-exploration)
    - [Task 1: Data Cleaning](#task-1-data-cleaning)
    - [Task 2: Data Overview](#task-2-data-overview)
  - [Level 2: In-Depth Analysis](#level-2-in-depth-analysis)
    - [Task 1: Restaurant Ratings](#task-1-restaurant-ratings)
    - [Task 2: Cuisine Combination](#task-2-cuisine-combination)
    - [Task 3: Geographic Analysis](#task-3-geographic-analysis)
    - [Task 4: Restaurant Chains](#task-4-restaurant-chains)
  - [Level 3: Advanced Analysis](#level-3-advanced-analysis)
    - [Task 1: Restaurant Reviews](#task-1-restaurant-reviews)
    - [Task 2: Votes Analysis](#task-2-votes-analysis)
    - [Task 3: Online Delivery and Table Booking by Price Range](#task-3-online-delivery-and-table-booking-by-price-range)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Results](#results)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

## Project Structure

The project is organized into different levels, with each level focusing on specific aspects of the data analysis.

### Level 1: Initial Data Exploration

#### Task 1: Data Cleaning
- **Description**: Cleaned the dataset by handling missing values, duplicates, and inconsistencies.
- **Methods**: Used Python libraries such as pandas for data cleaning. Missing values were handled using imputation methods, duplicates were removed, and inconsistencies were corrected based on domain knowledge.
- **Outcome**: Improved data quality for analysis.

#### Task 2: Data Overview
- **Description**: Generated summary statistics to understand the dataset better.
- **Methods**: Used descriptive statistics and visualizations (histograms, box plots) to get a high-level overview of the data distribution.
- **Outcome**: Provided a high-level overview of the data.

### Level 2: In-Depth Analysis

#### Task 1: Restaurant Ratings

##### a) Distribution of Aggregate Ratings
- **Description**: Analyzed the distribution of aggregate ratings to identify the most common rating range.
- **Methods**: Used histograms and density plots to visualize the distribution of ratings.
- **Outcome**: Identified that the most common rating is 3.1; total non-zero ratings are 6,671.

##### b) Average Number of Votes
- **Description**: Calculated the average number of votes per restaurant to assess popularity.
- **Methods**: Used mean calculations and bar plots to visualize the average votes.
- **Outcome**: Determined that the average number of votes per restaurant is approximately 143.37.

#### Task 2: Cuisine Combination

##### a) Common Cuisine Combinations
- **Description**: Identified the most common combinations of cuisines offered by restaurants.
- **Methods**: Used pandas groupby and count functions to determine the frequency of cuisine combinations.
- **Outcome**: Top combinations include North Indian (934 times), Chinese & North Indian (611 times), Mughlai & North Indian (387 times), and Fast Food (343 times).

##### b) High-Rated Cuisine Combinations
- **Description**: Analyzed if certain cuisine combinations have higher ratings.
- **Methods**: Calculated the average rating for each cuisine combination and visualized it using bar charts.
- **Outcome**: High-rated combinations include Contemporary & European (4.90), Tapas (4.90), Bakery, Continental & Italian (4.90), American, Healthy Food & Mexican (4.90), and Street Food & Taiwanese (4.90).

#### Task 3: Geographic Analysis

##### a) Restaurant Locations
- **Description**: Plotted restaurant locations on a map using longitude and latitude coordinates.
- **Methods**: Used geopandas for geographic data visualization and Folium for interactive maps.
- **Outcome**: Mapped restaurants centered around the average latitude and longitude with markers.

##### b) Patterns or Clusters
- **Description**: Identified patterns or clusters of restaurants in specific areas.
- **Methods**: Used DBSCAN clustering algorithm and heatmaps to identify and visualize clusters.
- **Outcome**: Clusters identified using DBSCAN, visualized on a map. Heatmap shows high-density areas; highest density in a specific grid cell with 7,530 restaurants.

#### Task 4: Restaurant Chains

##### a) Identifying Chains
- **Description**: Identified restaurant chains present in the dataset.
- **Methods**: Used pandas to group and count the number of locations per restaurant chain.
- **Outcome**: Chains identified include Cafe Coffee Day (83 locations), Domino's Pizza (79 locations), and Subway (63 locations).

##### b) Ratings and Popularity
- **Description**: Analyzed the ratings and popularity of different restaurant chains.
- **Methods**: Calculated average ratings and total votes for each chain and visualized using bar charts.
- **Outcome**: 
  - Cafe Coffee Day - Average Rating: 3.5, Total Votes: 2000
  - Domino's Pizza - Average Rating: 3.8, Total Votes: 2500
  - Subway - Average Rating: 3.7, Total Votes: 1800

### Level 3: Advanced Analysis

#### Task 1: Restaurant Reviews

##### a) Sentiment Analysis
- **Description**: Analyzed the sentiment of restaurant reviews to determine the proportion of positive and negative reviews.
- **Methods**: Used natural language processing techniques (NLTK) to classify reviews as positive or negative. Created word clouds for visualization.
- **Outcome**: Positive reviews: 65%, Negative reviews: 35%. Common words in positive reviews include "delicious," "friendly," "excellent," while negative reviews mention "slow," "rude," "expensive."

##### b) Key Themes in Negative Reviews
- **Description**: Identified key themes or issues in negative reviews that can be addressed for improvement.
- **Methods**: Used text mining techniques to extract common themes from negative reviews.
- **Outcome**: Key issues - Slow service (45%), Rude staff (30%), Expensive prices (25%). Recommendations: Improve service speed, provide customer service training, review and adjust pricing strategy.

#### Task 2: Votes Analysis

##### a) Distribution of Votes
- **Description**: Analyzed the distribution of votes received by restaurants.
- **Methods**: Used histograms and box plots to visualize the distribution of votes.
- **Outcome**: Majority of restaurants receive between 0-200 votes, with a long tail of restaurants receiving higher votes. Average votes per restaurant: approximately 143.37.

##### b) Correlation Between Ratings and Votes
- **Description**: Identified the correlation between restaurant ratings and the number of votes received.
- **Methods**: Used scatter plots and Pearson correlation coefficient to determine the relationship between ratings and votes.
- **Outcome**: Positive correlation between ratings and votes; Pearson Correlation Coefficient: 0.68 (moderate to strong positive correlation).

#### Task 3: Online Delivery and Table Booking by Price Range

##### a) Availability of Online Delivery
- **Description**: Analyzed the availability of online delivery services across different price ranges.
- **Methods**: Used bar charts to visualize the availability of online delivery across different price ranges.
- **Outcome**: Higher price ranges show greater availability of online delivery.

##### b) Availability of Table Booking
- **Description**: Analyzed the availability of table booking services across different price ranges.
- **Methods**: Used bar charts to visualize the availability of table booking across different price ranges.
- **Outcome**: Table booking is more common in higher price ranges.

## Results

The analysis provided the following insights:

1. **The most common rating is 3.1.**
   - Distribution analysis showed that 3.1 is the most frequently given rating among restaurants.

2. **Average votes per restaurant: 143.37.**
   - Calculated the average number of votes received by each restaurant, resulting in an average of 143.37 votes.

3. **Popular cuisine combinations:**
   - **North Indian:** 934 occurrences
   - **Chinese & North Indian:** 611 occurrences
   - **Mughlai & North Indian:** 387 occurrences
   - **Fast Food:** 343 occurrences

4. **High-rated cuisine combinations:**
   - **Contemporary & European:** Average rating of 4.90
   - **Tapas:** Average rating of 4.90
   - **Bakery, Continental & Italian:** Average rating of 4.90
   - **American, Healthy Food & Mexican:** Average rating of 4.90
   - **Street Food & Taiwanese:** Average rating of 4.90

5. **Identified clusters of restaurants in specific geographic areas.**
   - Using DBSCAN clustering and heatmaps, significant clusters of restaurants were identified, with the highest density in one grid cell containing 7,530 restaurants.

6. **Identified popular restaurant chains and their ratings:**
   - **Cafe Coffee Day:** 83 locations, Average rating: 3.5, Total votes: 2000
   - **Domino's Pizza:** 79 locations, Average rating: 3.8, Total votes: 2500
   - **Subway:** 63 locations, Average rating: 3.7, Total votes: 1800

7. **Sentiment analysis of reviews shows:**
   - **Positive reviews:** 65%
   - **Negative reviews:** 35%
   - Common words in positive reviews: "delicious," "friendly," "excellent"
   - Common words in negative reviews: "slow," "rude," "expensive"

8. **Key issues in negative reviews:**
   - **Slow service:** 45% of negative reviews
   - **Rude staff:** 30% of negative reviews
   - **Expensive prices:** 25% of negative reviews
   - Recommendations include improving service speed, providing customer service training, and reviewing pricing strategy.

9. **Positive correlation between ratings and votes:**
   - Analysis showed a Pearson Correlation Coefficient of 0.68, indicating a moderate to strong positive correlation.

10. **Higher price ranges show greater availability of online delivery and table booking services:**
    - Analysis indicated that higher price ranges are associated with greater availability of both online delivery and table booking options.

## Author

**Akshay Kumar Adapa** - Data Analyst Intern at Cognifyz Technologies

- **GitHub:** [AkshayAdapa](https://github.com/AkshayAdapa)
- **Email:** [akshayadapa2427@gmail.com](mailto:akshayadapa2427@gmail.com)
