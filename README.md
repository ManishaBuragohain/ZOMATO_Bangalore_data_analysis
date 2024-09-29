# Zomato Data Analysis

This project involves cleaning and analyzing Zomato restaurant data in Bangalore to explore various insights about cuisines, restaurant types, customer preferences, and pricing patterns.

## Table of Contents:
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Visualizations](#visualizations)
- [Conclusions](#conclusions)
- [Future Work](#future-work)

 # Introduction

 The Zomato dataset contains information about various restaurants, including their location, cuisines, online order availability, table booking options, customer ratings, and approximate costs. The main objective of this analysis is to gain insights into customer preferences, popular cuisines, and pricing trends across different areas.

 # Dataset
 # Source :  
 The dataset is obtained from Zomato.
 ## Attributes:
- Restaurant details like name, location, and type.
- Cuisines offered.
- Ratings and votes.
- Availability of online orders and table bookings.
- Approximate cost for two people.
## Data Cleaning:
- Removed missing or null values in critical columns such as `rate`, `cost_for_two`, and `votes`.
- Converted ratings into numeric format.
- Handled inconsistent cuisine listings and standardized them.
- Removed duplicates to avoid biased results.
- Fixed inconsistent formats in the `approx_cost` column by converting it to numerical format.
## Visualizations:
- **Top Cuisines**: Shows the most popular cuisines based on customer preferences.
- **Average Cost for Two by Location**: A bar chart displaying the average cost for two people across different locations.
- **Restaurant Types Distribution**: Highlights the distribution of restaurant types like casual dining, quick bites, etc.
- **Ratings vs Online Order**: A boxplot that compares ratings of restaurants offering online orders versus those that don’t.
- **Votes by Restaurant**: A bar chart showing the total number of votes each restaurant received.
## Conclusions:
- North Indian and Chinese cuisines are the most popular across multiple locations.
- Casual dining restaurants tend to have higher average costs compared to cafes and quick bites.
- Locations like Banashankari and Basavanagudi offer diverse cuisine options, catering to a wide range of preferences.
- Higher customer ratings are often associated with restaurants that provide both online orders and table booking services.
## Future Work:
- Perform sentiment analysis on customer reviews to gain insights into customer satisfaction.
- Explore the correlation between restaurant ratings and the average cost for two people.
- Analyze time-based trends to identify seasonal preferences in cuisine.
- Use clustering techniques to categorize restaurants based on customer ratings, votes, and pricing.

## PREVIEW
![image](https://github.com/user-attachments/assets/e7bf40b9-28d0-4895-be05-96cc851dda2e)
![image](https://github.com/user-attachments/assets/fe9997ec-2f45-4664-ad22-f222c2f7eef0)



