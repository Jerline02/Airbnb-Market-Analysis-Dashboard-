# 🏡 Airbnb Market Analysis Dashboard 

## Project Overview
This project focuses on analyzing Airbnb listings in New York City using Power BI and Python. The goal is to uncover pricing trends, availability patterns, and neighborhood-based insights to assist hosts, travelers, and businesses in making data-driven decisions.

## Data Source
- Original dataset: [Airbnb Data Analysis – Kaggle](https://www.kaggle.com/datasets/ishitar094/airbnb-data-analysis)
- ✅ This project uses a cleaned version of the Airbnb dataset, which I prepared using Python for all analysis, visualizations, and dashboard development.

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Power BI (Interactive Dashboard)
- Jupyter Notebook
- GitHub

## Data Cleaning
- Removed missing or irrelevant fields like unnamed columns and empty reviews.
- Filled `reviews_per_month` with 0 where no reviews exist.
- Dropped rows missing critical fields such as `host_name` and `room_type`.
- Converted `last_review` to datetime format.

## Data Preparation
- Selected only relevant columns for dashboard use (e.g., price, room_type, location, etc.)
- Removed extreme price outliers for better visual clarity.
- Aggregated fields like `number_of_reviews` and availability.

## Exploratory Data Analysis (EDA)

### Key Questions Explored:
- Which room types are most commonly listed?
- What is the average price per room type?
- Which neighborhoods have the most listings?
- How does price vary by availability and location?
- Which hosts have the highest number of listings?

## Data Analysis (Favorite Insight)
My favorite part of the analysis was using a **Power BI scatter plot** to visualize the relationship between `availability_365` and `price`, filtered by room type. It showed that pricing doesn’t directly correlate with availability — a valuable insight for pricing strategies.

## Results & Findings
- Entire homes/apartments are the most listed room type.
- Prices are mostly below ₹1000 but can go as high as ₹10,000+.
- Manhattan and Brooklyn dominate in listing density and average prices.
- Many listings have 0 reviews, but engaged listings get 1–2 reviews/month.
- Listings are available throughout the year (up to 365 days).

## Recommendations
- Hosts in low-demand neighborhoods can lower prices or improve availability to increase bookings.
- Airbnb could introduce smarter review/feedback incentives to boost listing engagement.
- Use price bands to help budget vs. luxury travelers filter listings effectively.





