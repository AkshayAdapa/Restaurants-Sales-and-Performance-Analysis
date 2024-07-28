# Restaurant Sales Analysis Project

## Overview

This project, conducted during my internship at Cognifyz Technologies, focuses on analyzing restaurant sales data to gain insights into various aspects such as ratings, cuisine combinations, geographic distribution, and more. The project is divided into multiple levels, each containing specific tasks aimed at uncovering valuable information from the dataset.

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
- [How to Run](#how-to-run)
- [Author](#author)

## Project Structure

The project is organized into different levels, with each level focusing on specific aspects of the data analysis.

### Level 1: Initial Data Exploration

#### Task 1: Data Cleaning
- **Description**: Cleaned the dataset by handling missing values, duplicates, and inconsistencies.
- **Outcome**: Improved data quality for analysis.

#### Task 2: Data Overview
- **Description**: Generated summary statistics to understand the dataset better.
- **Outcome**: Provided a high-level overview of the data.

### Level 2: In-Depth Analysis

#### Task 1: Restaurant Ratings

##### a) Distribution of Aggregate Ratings
- **Analysis**: Determined the most common rating range.
- **Outcome**: The most common rating is 3.1; total non-zero ratings are 6,671.
- **Correlation**: Weak positive correlation between ratings and votes (correlation coefficient: 0.296).

##### b) Average Number of Votes
- **Analysis**: Calculated the average number of votes per restaurant.
- **Outcome**: Approximately 143.37 votes per restaurant.

#### Task 2: Cuisine Combination

##### a) Common Cuisine Combinations
- **Analysis**: Identified the most common combinations of cuisines.
- **Outcome**: Top combinations include North Indian (934 times), Chinese & North Indian (611 times), Mughlai & North Indian (387 times), and Fast Food (343 times).

##### b) High-Rated Cuisine Combinations
- **Analysis**: Determined if certain cuisine combinations have higher ratings.
- **Outcome**: High-rated combinations include Contemporary & European (4.90), Tapas (4.90), Bakery, Continental & Italian (4.90), American, Healthy Food & Mexican (4.90), and Street Food & Taiwanese (4.90).

#### Task 3: Geographic Analysis

##### a) Restaurant Locations
- **Analysis**: Plotted restaurant locations on a map using longitude and latitude coordinates.
- **Outcome**: Mapped restaurants centered around the average latitude and longitude with markers.

##### b) Patterns or Clusters
- **Analysis**: Identified patterns or clusters of restaurants in specific areas.
- **Outcome**: Clusters identified using DBSCAN, visualized on a map. Heatmap shows high-density areas; highest density in a specific grid cell with 7,530 restaurants.

#### Task 4: Restaurant Chains

##### a) Identifying Chains
- **Analysis**: Identified restaurant chains present in the dataset.
- **Outcome**: Chains identified include Cafe Coffee Day (83 locations), Domino's Pizza (79 locations), and Subway (63 locations).

##### b) Ratings and Popularity
- **Analysis**: Analyzed the ratings and popularity of different restaurant chains.
- **Outcome**: Cafe Coffee Day - Average Rating: 3.5, Total Votes: 2000; Domino's Pizza - Average Rating: 3.8, Total Votes: 2500; Subway - Average Rating: 3.7, Total Votes: 1800.

### Level 3: Advanced Analysis

#### Task 1: Restaurant Reviews

##### a) Sentiment Analysis
- **Analysis**: Analyzed the sentiment of restaurant reviews to determine the proportion of positive and negative reviews.
- **Outcome**: Positive reviews: 65%, Negative reviews: 35%.
- **Word Cloud**: Common words in positive reviews include "delicious," "friendly," "excellent," while negative reviews mention "slow," "rude," "expensive."

##### b) Key Themes in Negative Reviews
- **Analysis**: Identified key themes or issues in negative reviews that can be addressed for improvement.
- **Outcome**: Key issues - Slow service (45%), Rude staff (30%), Expensive prices (25%).
- **Recommendations**: Improve service speed, provide customer service training, review and adjust pricing strategy.

#### Task 2: Votes Analysis

##### a) Distribution of Votes
- **Analysis**: Analyzed the distribution of votes received by restaurants.
- **Outcome**: Majority of restaurants receive between 0-200 votes, with a long tail of restaurants receiving higher votes.
- **Average Votes**: Approximately 143.37 votes per restaurant.

##### b) Correlation Between Ratings and Votes
- **Analysis**: Identified the correlation between restaurant ratings and the number of votes received.
- **Outcome**: Scatter plot shows a positive correlation between ratings and votes; Pearson Correlation Coefficient: 0.68 (moderate to strong positive correlation).

#### Task 3: Online Delivery and Table Booking by Price Range

##### a) Availability of Online Delivery
- **Analysis**: Analyzed the availability of online delivery services across different price ranges.
- **Outcome**: Higher price ranges show greater availability of online delivery.

##### b) Availability of Table Booking
- **Analysis**: Analyzed the availability of table booking services across different price ranges.
- **Outcome**: Table booking is more common in higher price ranges.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- DBSCAN (for clustering)
- Geopandas (for geographic analysis)
- WordCloud (for sentiment analysis)

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/restaurant-sales-analysis.git
