# NYC Airbnb Data Analysis

## Overview
**Airbnb.com** has changed the game when it comes to short-term rentals, making it easier than ever to find a cozy place to stay. With millions of users worldwide, it offers diverse properties, from entire homes to shared rooms, across different price ranges and locations.

This project dives into Airbnb data for **New York City**.
From historic brownstones to luxurious Manhattan penthouses, the Big Apple's vibrant rental market offers endless possibilities, making it one of the platform's most dynamic markets.

## What we did and discovered
- **Outliers & Data Cleaning**: We identified extreme price values, including listings priced at $100,000 per night and others at $10, some categorized as “Entire home/apt”, highly unrealistic for NYC. These were removed to ensure accurate analysis.
- **Impact of Local Law 18 (2023)**: Our data reveals a striking pattern - 30 days is the most common minimum stay requirement. This aligns with NYC’s Local Law 18, which mandates that:
  - Hosts must register with the city for stays under 30 days.
  - They must be physically present in the property during short stays.
  - Guests must have full access to the property.
  - To bypass these restrictions, many hosts have set 30-day minimums, effectively shifting their listings into the medium-term rental market. This demonstrates how local policies can reshape an entire city's rental dynamics.
- **Interactive Map**: A visual representation of Airbnb listings across NYC, showcasing price distribution and neighborhood trends.
- **Pricing & Availability Analysis**: We explored how prices vary across boroughs, examining factors like room type, number of reviews, and availability throughout the year.
- **Guest Ratings & Reviews**: Analyzed rating distributions and correlations between price, location, and guest satisfaction.

This project provides a look into NYC’s Airbnb market, highlighting key trends that shape both host strategies and guest experiences.

[Check out the notebook](https://github.com/juliakuczynska/nyc_airbnb_analysis/blob/main/nyc_airbnb.ipynb)
