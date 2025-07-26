# Realtime_Weather_API_Dashboard
🌦️ Real-Time Weather Dashboard (Power BI)

This project is a real-time interactive weather analytics dashboard built in Power BI, leveraging a weather API to provide dynamic updates on environmental conditions across selected Indian cities.

📌 Objective

The primary objective of this project is to:
Fetch real-time weather data from a weather API.
Perform data cleaning, transformation, and modeling using Power Query and DAX.
Deliver an intuitive and visually appealing dashboard in Power BI that presents real-time insights about weather conditions, environmental metrics, and forecasted trends.

⚙️ Tech Stack

Power BI
Weather API (Used to fetch real-time weather data)
DAX (For creating calculated columns, measures, and KPIs)
Conditional Formatting & Custom Visuals – For enhanced UI (e.g., weather icons, AQI status lights).

📊 Dashboard Features

✅ General Weather Information:
Displays the current temperature, weather conditions (e.g., rain, sun), and selected city names (e.g., Ajmer, Bhubaneswar, Hyderabad).
Shows wind speed, humidity, pressure, visibility, UV index, and precipitation.

🌦️ 7-Day Weather Forecast:

A dynamic line graph that plots temperature trends over the week.
Shows daily high temperatures and icons indicating weather type (rain, sun, clouds, etc.).

☁️ Air Quality Index (AQI):

Visualizes pollutants such as:
PM10
O3 (Ozone)
CO (Carbon Monoxide)
NO2 (Nitrogen Dioxide)
SO2 (Sulfur Dioxide)
PM2.5
Categorized by color codes (Green = Good, Yellow = Moderate, Red = Poor).

🌄 Sunrise & Sunset:

Real-time display of sunrise and sunset timings per selected city.

🌧️ Chance of Rain:

Horizontal bar chart showing percentage probability of rainfall for the upcoming 7 days.

🔍 Key Insights

Real-time monitoring of weather allows users to plan activities based on environmental conditions.
Air quality indicators help raise awareness about pollution levels in different cities.
Rain probability and temperature trends help in forecasting weekly patterns.
This dashboard can be particularly helpful for travelers, planners, logistics, and environmental agencies.

📈 Data Pipeline

API Integration – Real-time weather data is fetched using a REST API.
Data Cleaning – Unnecessary fields are removed, and data types are standardized in Power Query.
Data Modeling – Fact and dimension tables created, and DAX measures calculated.
Visualization – Charts, cards, and indicators are built using native Power BI visuals.

📬 Contact

For any queries or suggestions, feel free to reach out via GitHub issues or pull requests .


