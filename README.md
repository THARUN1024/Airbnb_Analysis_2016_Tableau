Airbnb 2016 Data Analysis
Project Overview

This project analyzes Airbnb listing data from 2016 using Tableau for visualization and insights. The dataset includes listings and calendar data, which were processed and joined to provide a comprehensive view of Airbnb performance metrics such as:

Price per bedroom
Revenue trends
Price distributions across zip codes
The aim is to help stakeholders make data-driven decisions regarding pricing, property investments, and market analysis.

Datasets Used
1. Listings Dataset

Contains detailed information about each Airbnb listing, including:

Property details: ID, name, description, zipcode, property type, room type
Host information: Host ID, host name, host location
Pricing & amenities: Price, cleaning fee, square feet
Location data: Latitude, longitude, neighborhood
2. Calendar Dataset

Contains daily availability and pricing for each listing:

listing_id: Unique identifier for each property
date: Calendar date
available: Availability status (Yes/No)
price: Daily price of the listing
Data Preprocessing
Reviews dataset was excluded as it was not needed for this analysis.
Listings and calendar datasets were inner joined on listing_id for a unified analysis.
Key Insights & Findings
1. Average Price Per Bedroom

Analyzed how bedroom count affects price.
Observed trends:
1-bedroom properties: $96.2 (average price)
6-bedroom properties: $584.8
2. Price Distribution by Zip Code

Identified zip codes with the highest & lowest average prices.
Key findings:
Zip code 98177: Highest average price ($842).
Zip code 98122: Average price ($122.3).
3. Revenue Trends for the Year

Mapped weekly revenue trends for 2016.
Significant revenue spikes during peak seasons.
Technologies Used
Tools

Tableau – For data visualization and dashboard creation.
Dataset

Listings data
Calendar data (availability & pricing)
Visualizations
1️⃣ Average Price Per Bedroom

Bar chart showing the relationship between bedroom count & average price.
2️⃣ Price Per Zip Code

Choropleth map displaying average prices across zip codes.
3️⃣ Revenue for the Year

Line graph illustrating revenue trends throughout 2016.
