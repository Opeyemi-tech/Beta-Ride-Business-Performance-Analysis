# Beta Ride Taxi Service - Power BI Capstone Project
## Project Overview
This project analyzes operational and revenue data from Beta Ride, a taxi service, to uncover insights that can help improve service delivery, optimize resource allocation, and boost revenue generation. The analysis focuses on trip demand patterns, driver performance, payment methods, and external conditions such as weather and time of day.

## Data Source:
The analysis uses a cleaned and prepared dataset from Bete-Ride Taxi services through @mydataclique (A data community) and it contains the following key fields:
trip_id, date, day_of_week, month,
trip_distance, total_amount,
payment_type, weather_condition, driver_id, trip_purpose

## Tool Used
- Power BI, Power Query

## Data Cleaning and Preparation Process
- Using Power Query, the following transformations were applied:
- Extracted Month, Day, Hour from trip timestamps
- Created custom sorting columns for day and month
- Categorized trip time into Morning Peak, Evening Peak, and Off-Peak
- Calculated total revenue, average trip distance, and MoM growth

## Goal of the Analysis
Beta Ride wants to:
- Identify trends in revenue and growth
- Understand customer demand and trip patterns
- Analyze the impact of traffic and weather on rides
- Optimize their operations for better efficiency and profits

## Data Analysis
### 1. Revenue & Growth
<img width="604" alt="Total Revenue" src="https://github.com/user-attachments/assets/d578abb6-4ab2-419d-afcc-68db020cd841" />

### 2. Trip Demand
<img width="599" alt="Trip Demand" src="https://github.com/user-attachments/assets/d7bf9618-b42b-45b6-ab2b-29a50116916c" />

## 3. Operational Insights
<img width="599" alt="Operational Insights" src="https://github.com/user-attachments/assets/08adde32-0100-4719-97cd-de7e80d2630b" />

#### Revenue:
  - Distribution Across Peak Periods: Off-peak hours generate the highest revenue ($12.37K, 62.67%), followed by evening peak ($4.11K, 20.95%) and morning peak ($3.23K, 16.38%).
##### This suggests that most trips and revenue are occurring outside of traditional peak commuting hours.

#### Trips by Weather Condition:
  - The highest number of trips occurred under "Moderate" and "Good" weather conditions, while fewer trips happened in "Bad" weather.

##### Bad weather negatively affects demand, potentially due to safety concerns.

#### Payment Preferences:
  - Card (52%) and Cash (48%) payments are nearly balanced.
  ##### - This shows the importance of maintaining both options for convenience.
  
#### Revenue Growth Trend:
  - Revenue rose month-over-month, reaching its peak in July.
  - Analyzing the factors behind this spike (seasonality, Revenue by Location: Airports, Downtown, and Midtown generate the highest revenue marketing, etc.) can facilitate replicating this success.

  - These areas likely experience the greatest trip demand, making them crucial zones for optimizing driver allocation.

## Recommendations
### Maximize Off-Peak Revenue Potential:
  - Since off-peak hours drive the most revenue, Beta-Ride should analyze why—perhaps business trips, late-night rides, or flexible work schedules.
  - Consider targeted promotions or driver incentives to further capitalize on this trend.


### Encourage More Peak-Hour Trips:
  - Since morning peak revenue is the lowest, Beta-Ride could offer discounts, ride-sharing options, or marketing campaigns to increase demand during peak hours.


### Weather-Based Pricing or Safety Incentives:  
  - Since trips drop in bad weather, Beta-Ride could implement surge pricing or offer raincoats, insurance, or safer vehicles to encourage rides.


### Enhance Digital Payment Adoption:
  - To increase card usage, offer discounts for cashless payments to streamline transactions and improve safety.

### Boost Driver Efficiency & Training: 
  - Identify top-performing drivers and analyze their behaviors (routes, customer service, trip frequency).
  - Train underperforming drivers to improve trip numbers and revenue per driver.

### Optimize Operations in High-Revenue Areas:
  - Increase vehicle availability in Downtown, Midtown, and Airports, ensuring there are always enough drivers to meet demand.

## Challenges:
During the Beta Ride Power BI project, I faced multiple challenges. These included aligning trip data with external factors like weather and peak operating times to identify actionable trends. Crafting advanced DAX measures for key performance indicators, such as driver efficiency and peak-hour revenue, required extensive research and learning. Furthermore, maintaining data quality and creating an intuitive, interactive dashboard for a non-technical audience necessitated a methodical approach to data modeling and visual communication. By continuously exploring Power BI resources, applying DAX functions practically, and refining the dashboard iteratively, I managed to overcome these obstacles and produce a comprehensive and user-friendly analytical solution.








