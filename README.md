# Airbnb Singapore Listings - Dashboard

## Problem Statement

The objective of this dashboard is to furnish Airbnb Singapore with comprehensive insights into the spectrum of available accommodation types across the region, coupled with their average pricing and occupancy rates throughout the year 2022. The primary goal is to discern the key factors influencing occupancy rates and identify any underserved regions. This information is crucial for strategic host recruitment efforts, specifically targeting regions with untapped potential, ultimately aiming to maximize revenue for Airbnb Singapore.

## Tools Used
1. Python: For Data Cleaning and Transformation tasks, including reverse geocoding, handling of outlier values, data type conversion and error detection
2. Power BI: For data visualization purposes

# Snapshot of Dashboard

![db_1](https://github.com/Pearlyn-B/portfolio/assets/80374547/d31ed80e-cf8e-424b-8e8d-7ad364c4be41)

# Insights

Following inferences can be drawn from the dashboard;

### [1] Central Region's Competition Dynamics:
The central region emerges as highly competitive, hosting the majority of listings (80.68%). Interestingly, despite the abundance of listings, it exhibits the lowest average occupancy rate. This inverse relationship between the number of listings and occupancy rates suggests that high competition in the central region may be impacting hosts' success, resulting in lower occupancy rates.

### [2] Underserved Potential in North-East and East Regions:
The North-East and East regions, with only 3.44% and 5.38% of the listings respectively, present an untapped opportunity. Despite their relatively high average prices, both regions boast the top 2 highest occupancy rates. To meet the demand, Airbnb Singapore should consider targeted host recruitment efforts in these underserved areas, potentially leveraging location-based marketing.

### [3] Drivers of Occupany Rate:
![kf_1](https://github.com/Pearlyn-B/portfolio/assets/80374547/fd46a84e-2207-4318-ba2e-346ead913bea)
- Listing Count:
The key influencer chart highlights a crucial trend where hosts with a listing count of 100-140 achieve a 53.34% increase in occupancy rates, indicating their proficiency in delivering high-quality services that enhance guest satisfaction. The substantial inventory not only builds a strong brand identity that earns customer trust but also allows for a diversified portfolio that caters to a wider customer audience across different locations and property type, effectively managing risks from seasonal shifts and market dynamics. However, having more than 140 listings does not automatically equate to higher occupancy rates, implying a threshold beyond which quantity may dilute the quality of the guest experience, suggesting a strategic pivot towards enhancing service quality may be more beneficial.

- Pricing Strategy:
Although the listing count has a significant impact on occupancy rates, pricing also plays a role. Maintaining competitive pricing within the $49 - $213 range is also associated with a higher occupancy rate.
