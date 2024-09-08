# Hotel Booking Analysis

## Project Overview
This project focuses on analyzing hotel bookings for two types of hotels: City Hotel and Resort Hotel. The dataset includes 119,390 rows and 32 columns, providing detailed booking information such as booking date, stay duration, number of guests, and availability of parking spaces. Through Exploratory Data Analysis (EDA), we aim to uncover significant patterns and insights about hotel bookings, which can help improve the business decision-making process.

## Problem Statement
Have you ever wondered about the best time to book a hotel room or the ideal stay duration to get the best rates? How likely is a hotel to receive special requests? This dataset helps answer these questions by analyzing booking details for City Hotels and Resort Hotels.

## Business Objective:
The goal is to analyze the data on bookings for both hotel types and identify key factors that influence the booking process. This analysis will provide valuable insights into customer preferences, booking trends, and cancellation patterns, helping the business make data-driven decisions to optimize hotel performance.


## Dataset:
The dataset includes various features related to hotel bookings, such as:

**Hotel Type:** City Hotel or Resort Hotel
**Booking Information:** Lead time, arrival dates, length of stay, etc.
**Guest Information:** Number of adults, children, and babies
**Booking Status:** Cancellations, special requests, and repeated guests
**Revenue:** The average daily rate (ADR) to assess hotel performance

## Data Collection & Cleaning
### Data Collection:

Initial exploration using head(), tail(), info(), describe(), and columns() functions.
Identification of important columns like hotel, is_canceled, lead_time, arrival_date_year, arrival_date_month, etc.

### Data Cleaning:

Identified and removed 87,396 duplicate rows from the dataset.
Handled missing values by dropping columns with excessive null values, such as the company column, and filling others using appropriate methods (fillna()).
Created new features like total_people (sum of adults, children, and babies) and total_stay (sum of weekend and weekday stays).

## Exploratory Data Analysis (EDA)

### Univariate Analysis
**Hotel Preference:** City Hotel has more bookings compared to Resort Hotel.
**Seasonality: **July and August witness the highest number of bookings.
**Room Preference:** Room Type A is the most booked room category.

### Bivariate Analysis
**Cancellation Rate:** City Hotel has a higher cancellation rate, especially among first-time guests.
**Lead Time & Cancellations: **Longer lead times tend to result in higher cancellation rates.
**Customer Retention:** Corporate guests have a higher retention rate than TA/TO (Travel Agents/Tour Operators).
Multivariate Analysis
**Revenue vs. Length of Stay:** As the average daily rate (ADR) increases, guests tend to stay for fewer days.
**Guest Origin:** Most guests are from Portugal and Great Britain.

## Data Visualization
Multiple charts were created to derive meaningful insights, including:

**Bar charts** to visualize booking distributions across months and room types.
**Heatmaps** to examine correlations between variables like ADR, lead time, and cancellations.
**Pie charts** to visualize the proportion of City Hotel vs. Resort Hotel bookings.
Each visualization helped in understanding the relationship between different features and how they impact hotel bookings.

## Key Insights
**City Hotel** is the preferred choice among travelers, contributing to higher revenue compared to Resort Hotel.
**July and August** are peak booking months.
**Room Type A** is the most popular room category.
**Cancellation Rate** is high, with City Hotel having the largest percentage of cancellations.
**Corporate Guests** tend to be repeat customers, while guests booking through TA/TO tend to cancel more frequently.
**Booking Duration** decreases as the ADR increases, suggesting that customers aim to minimize costs with shorter stays.

## Conclusion
**City Hotel** appears to be more profitable and preferred by guests compared to Resort Hotel.
**Understanding booking trends**, such as seasonality and cancellation rates, can help hotels optimize their resources and marketing efforts.
**Revenue Management** can be improved by adjusting prices and promotions according to the season and customer types.

## Recommendations
**Optimize Booking Channels:** Hotels should focus on reducing cancellations from TA/TO bookings by offering incentives for confirmed reservations.
**Increase Marketing Efforts:** During peak booking months, hotels can raise prices or offer premium services.
**Customer Retention Programs:** Corporate guests should be given loyalty programs or special discounts to encourage repeat bookings.
