# Tableau-Projects
## 1. British Airways Review Visualization

Project Overview

This project involves creating an interactive dashboard using Tableau. The dashboard displays British Airways (BA) reviews, allowing users to dynamically filter and explore various metrics such as overall ratings, food ratings, entertainment ratings, and more. The interactive features include filtering by date, traveler type, seat type, aircraft, and continent. Each visual acts as a dynamic filter to help users drill down into specific data points of interest.

### Data Sources
1. British Airways Reviews (ba_reviews.csv)
Columns:
Author: Reviewer’s name or identifier
Date: Date of the review
Place: Location where the review was made
Rating: Overall rating
Seat Comfort: Comfort rating of the seat
Cabin Staff Service: Rating of the cabin staff service
Food Beverages: Rating of the food and beverages
Ground Service: Rating of the ground service
Value for Money: Value for money rating
Entertainment: Rating of the entertainment provided
2. Countries (countries.csv)
Columns:
Country: Country name
Region: Region or continent of the country
### Dashboard Features
Metric Selection:

Users can select which metric to display from a list including overall rating, cabin staff service, entertainment, food, ground service, seat comfort, and value for money.
Filters:

Date Filter: Filter reviews by specific dates.
Traveler Type Filter: Filter by traveler type (e.g., business, couple, family).
Seat Type Filter: Filter by seat type (e.g., business class, economy class).
Aircraft Filter: Filter by specific aircraft models.
Continent Filter: Filter by continent.

Interactive Map: Displays average ratings by country with a color gradient. Users can click on countries to filter the data accordingly.
Summary Metrics: Displays key metrics such as average overall rating, cabin staff service, entertainment, food, ground service, seat comfort, and value for money.
Monthly Trend Chart: Shows the average selected metric over time.
Aircraft Performance Chart: Displays the average selected metric by aircraft, alongside the number of reviews for each aircraft.

## 2. Covid data death and spread Visualization

Project Overview

This project focuses on creating visualizations using Tableau, combining them into a comprehensive dashboard. The dataset used is related to COVID-19, with various queries run in SQL to extract meaningful insights. The goal is to make the project easy to visualize and draw insights to strategize the replication of Covid 19 and understand the Covid prone zones and Countries. 
### Data Sources
1. COVID-19 Dataset (covid_data.csv)
Columns:
Date: Date of the record
Country: Country name
New Cases: Number of new COVID-19 cases
Total Cases: Total number of COVID-19 cases
New Deaths: Number of new COVID-19 deaths
Total Deaths: Total number of COVID-19 deaths
New Recoveries: Number of new recoveries
Total Recoveries: Total number of recoveries

### Dashboard Features
Interactive Map:

Displays total COVID-19 cases by country with a color gradient.
Users can click on countries to filter the data.
Trend Analysis:

Line chart showing new COVID-19 cases over time.
Area chart showing new recoveries over time.
Bar Chart:

Displays total deaths by country.
Allows comparison between different countries.
Filters:

Date Filter: Filter data by specific date ranges.
Country Filter: Filter data by specific countries.
