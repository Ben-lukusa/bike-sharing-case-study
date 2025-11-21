# bike-sharing-case-study
How do annual members and casual riders use Cyclistic bikes differently? 

This project analyzes Cyclistic’s (Divvy’s) 2019–2020 bike-share data using R. The goal is to understand rider behavior and identify opportunities to convert casual riders into annual members

Tools that I used :
•	R / Posit Cloud
•	tidyverse
•	lubridate
•	janitor
•	ggplot2

Data Cleaning Steps:
Merged 2019 + 2020 datasets
Standardized column names
Fixed type mismatches (character, numeric, datetime)
Created engineered variables:
ride_length (minutes)
day_of_week
Removed invalid ride lengths (≤0 or ≥1440 minutes)

Key Insights:
Members vs Casual Ride Patterns
Members → Weekday commuters
Casuals → Weekend leisure riders
Casuals take much longer rides
Hourly Patterns
Members peak around 7–9AM and 4–6PM
Casual riders peak midday and weekends
Station-Level Patterns
Tourist/destination stations used more by casual riders
Transit and downtown stations used more by members

My Recommendations: 
Weekend-to-Member Campaign
Commuter-focused membership perks
Personalized in-app cost-savings nudges


If you'd like to discuss the project, collaborate, or review the analysis, feel free to reach out!
