# Capstone-Project-EDA---Hotel-Booking-Analysis

# Exploratory Data Analysis (EDA) of Hotel Bookings

## Problem Statement

The hotel industry faces several challenges hindering operational efficiency and strategic decision-making. These challenges include difficulties in accurately predicting booking cancellations, leading to revenue loss and operational disruptions. Additionally, there is a lack of comprehensive insights into temporal booking patterns, hindering effective resource management. Incomplete guest demographic analysis limits personalized services, impacting guest satisfaction and loyalty. Challenges in understanding room preferences and changes result in inefficient room allocation strategies and potential guest dissatisfaction. The absence of a robust customer segmentation strategy further complicates targeted marketing and service customization. The overarching goal of this project is to address these challenges through a thorough Exploratory Data Analysis (EDA) of hotel bookings, utilizing a dataset with features such as 'hotel', 'is_canceled', 'lead_time', 'arrival_date_year', and others.

The outcomes aim to provide actionable insights for the hotel industry, facilitating improved operational efficiency, enhanced guest experiences, and strategic decision-making for optimized overall business performance.

## Basic Summary of the Dataset

- The dataset contains 36 fields (columns) and 119,390 entries (rows). Out of these entries, 31,994 are duplicate rows, which were dropped to remove noise from the data.
- The fields 'country', 'agent', and 'company' contain null values, with 'company' having the maximum number of missing values.
- The 'children' field has only 4 null values, which were replaced with 0.

## Variables Description

### is_canceled:
- Binary variable indicating whether a booking was canceled (1) or not (0).
- Provides insights into cancellation patterns within the dataset.

### lead_time:
- Number of days between the booking date and the arrival date.
- Offers information on the planning horizon for reservations.

### arrival_date_year:
- Year of arrival for the booking.
- Helps in analyzing booking trends over different years.

### stays_in_weekend_nights:
- Number of weekend nights (Saturday and Sunday) the guest stays.
- Provides insights into weekend stay patterns of guests.

### stays_in_week_nights:
- Number of weekday nights (Monday to Friday) the guest stays.
- Provides information on the duration of weekday stays.

### adults, children, babies:
- Number of adults, children, and babies included in the booking.
- Helps in understanding the composition of guests in terms of age groups.

### is_repeated_guest:
- Binary variable indicating whether the guest is a repeated guest (1) or not (0).
- Offers insights into the proportion of repeat guests.

### previous_cancellations, previous_bookings_not_canceled:
- Count of previous cancellations and bookings not canceled by the guest.
- Contribute to understanding the guest's historical booking behavior.

### booking_changes:
- Number of changes made to the booking before arrival.
- Provides insights into the flexibility and adaptability of bookings.

### agent, company:
- Numerical identifiers for the booking agent and the company.
- Help in identifying the entities associated with the booking.

### days_in_waiting_list:
- Number of days the booking was in the waiting list before it was confirmed.
- Provides insights into demand and waiting times for reservations.

### adr:
- Average Daily Rate, representing the average rental income per paid occupied room per day.
- Offers insights into pricing strategy and revenue generation.

### required_car_parking_spaces:
- Number of car parking spaces requested by the guest.
- Provides information on the parking needs of guests.

### total_of_special_requests:
- Total number of special requests made by the guest (e.g., extra beds, specific room preferences).
- Offers insights into guest preferences and customization requirements.

## Summary of Key Findings

### 1. Hotel Type and Bookings
- City hotels have the highest number of bookings, indicating higher demand compared to resort hotels.
- Opportunities exist for targeted strategies and resource allocation based on hotel type.

### 2. Booking Trends Over Years
- 2016 had the highest number of bookings, followed by 2017, while 2015 had the least.
- Understanding peak booking years allows for optimized strategies and resource allocation.

### 3. Seasonal Booking Patterns
- August and July experience the highest demand, with a consistent linear growth from March to May.
- Adjusting staffing levels and offering discounts during off-peak seasons can optimize resource allocation.

### 4. Meal Preference Analysis
- BB meals have the highest demand, while FB meals show minimal interest.
- Opportunities exist for menu optimization and targeted marketing based on meal preferences.

### 5. Country-wise Booking Distribution
- Portugal (PRT) leads with the highest number of bookings, while other countries exhibit varied booking trends.
- Identifying growth opportunities in countries with high bookings is essential for targeted strategies.

### 6. Market Segment Analysis
- The online TA market segment dominates, highlighting high demand and opportunities for targeted marketing.
- Understanding distribution channels and repeat guest behavior informs personalized service offerings.

### 7. Deposit Type Preferences
- The majority of customers prefer bookings without any deposit, indicating a preference for flexibility.
- Opportunities exist for offering flexible reservation terms to attract more customers.

### 8. Room Type Preferences and Assignments
- Discrepancies exist between customer preferences and actual room assignments, emphasizing the need for improved accuracy.
- Addressing room assignment mismatches can enhance customer satisfaction and loyalty.

### 9. Customer Type Analysis
- Transient customers lead with the highest demand, followed by transient-party bookings.
- Opportunities exist for targeted marketing and service enhancement based on customer types.

### 10. Parking Space Requirements
- The majority of customers do not require parking space, suggesting potential resource optimization.
- Balancing resources and investments in parking facilities is crucial to align with actual demand.

### 11. Booking Trends Over Time
- Understanding peak booking days and monthly booking trends allows for optimized marketing strategies and resource allocation.
- Addressing challenges during off-peak months is essential to prevent negative growth.

## Conclusion

The Exploratory Data Analysis (EDA) of hotel bookings provides valuable insights into booking patterns, guest preferences, and market trends. Leveraging these insights can inform strategic decisions for enhanced operational efficiency, improved guest experiences, and optimized overall business performance in the hotel industry.
