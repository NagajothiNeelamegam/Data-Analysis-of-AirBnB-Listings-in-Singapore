# Data Analysis of AirBnB Listings in Singapore

<img src="https://www.hostfully.com/wp-content/uploads/2020/04/950x800-2.png" alt="airbnb" style="width:600px;height:500px;">

Airbnb, Inc. is a San Francisco-based American company that operates an online platform for short-term accommodations and experiences. They offer listings in more than 220 countries and regions worldwide. Like many other industries, Airbnb was significantly affected by the COVID-19 pandemic. 

This project aims to conduct a comprehensive analysis of Airbnb property listings in Singapore, with a particular focus on the impact of the COVID-19 pandemic spanning four years from 2018 to 2022. Utilizing tools like Python and its packages, namely Plotly and Pandas for data analysis and visualization.

## Points to Analyze

The main points that are analyzed and focused on in this project are as follows:
- **Room type:** how the prices and ultimately the reviews (occupancy) varies by room type.
- **Location:** how each neighbourhood and by extension each region stacks up against one another in pricing and occupancy.
- **Trend:** how the occupancy trend looks like throughout the 4 years and the impact of the pandemic on occupancy rates

## Analysis

### **1. Room Type**

**Median Price by Room Type:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/price_roomtype_plot.png" alt="Median Price by Room Type" style="width:900px;height:350px;">

**Occupancy Share by Room Type:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/reviews_roomtype_plot.png" alt="Occupancy Share by Room Type" style="width:1000px;height:350px;">

- Room types are divided into four categories with varying degrees of space, amenities and luxury. As can be seen on the first chart above, the most expensive room type is the entire home/apartment type, but it is also the room type with the highest occupancy rate as can be seen on the second chart above. This is likely because AirBnB captures the more long term stay segment instead of the “vacation” segment of the market. A close second is the private room type, considering the balance between affordability and privacy this isn’t a surprise.

### **2. Location**

**Median Price by Neighbourhood:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/price_neighbourhood_plot.png" alt="Median Price by Neighbourhood" style="width:1000px;height:350px;">

**Median Price by Region:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/price_neighbourhood_group_plot.png" alt="Median Price by Region" style="width:1000px;height:350px;">

**Popular Listings Share by Region:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/popular_neighbourhood_group_plot.png" alt="Popular Listings Share by Region" style="width:1000px;height:350px;">

- There are many neighbourhoods in Singapore that are each apart of an even larger region (neighbourhood group) of which there are five. As usual the more touristy neighbourhoods like Marina South, Orchard and Southern Islands have the highest median listing prices as can be seen on the first chart above. These neighbourhoods are all apart of the Central Region which is why it is the most expensive region as can be seen on the second chart above. When we look at occupancy rates however, the North Region comes out on top as can be seen on the third chart above, this is because it offers a great balance between affordability and accessibility to the other more touristy and downtown areas.

### **3. Trend**

**Monthly Renting Trend:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/monthly_trend_plot.png" alt="Monthly Renting Trend" style="width:1000px;height:350px;">

**Yearly Renting Trend:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/yearly_trend_plot.png" alt="Yearly Renting Trend" style="width:1000px;height:350px;">

**Comparison of No. Active Listings Before and After 2020-01-23:**

<img src="https://github.com/farrellwahyudi/Data-Analysis-of-AirBnB-Listings-in-Singapore/blob/main/Images/active_listings_plot.png" alt="Comparison of No. Active Listings Before and After 2020-01-23" style="width:1000px;height:350px;">

- The Covid-19 Pandemic had a profound impact on AirBnB listings in Singapore. More than 500 listings (or around 38% of total listings) went inactive after the pandemic happened as can be seen on the third chart above. Occupancy rates across the country plummeted right after January 2020 as can be seen on the first chart above. The good news is that occupancy rates went shooting up again once the lockdowns ended. As can be seen on the first and second chart above, occupancy rates in 2022 have gone up to just below pre-pandemic levels across the country, suggesting resilience in the AirBnB market.

## Conclusion

In summary, this data analysis of Airbnb listings in Singapore paints a comprehensive picture of the market's response to the challenges posed by the COVID-19 pandemic. The study reveals intriguing insights into room types, highlighting how the entire home/apartment category, despite being the most expensive, attracted the highest occupancy rates, possibly due to its appeal to the long-term stay segment. The location analysis underscores the importance of affordability and accessibility, with the North Region emerging as a leader in occupancy rates. Most notably, the pandemic's impact was unmistakable, resulting in a significant number of inactive listings and a sharp drop in occupancy rates in early 2020. However, the resilience of the market shines through as occupancy rates rebounded impressively after lockdowns ended, almost reaching pre-pandemic levels by 2022. 

This analysis provides valuable insights for both hosts and travelers navigating the evolving landscape of short-term accommodations in Singapore.

<img src="https://images.squarespace-cdn.com/content/v1/55c63ae6e4b06ae6eeb73710/1617199804386-M1YEXHXOIZPIZHHSP5RX/Airbnb_Recognition_Cover_Medium.gif" style="width:500px;height:400px;" loop=infinite>
