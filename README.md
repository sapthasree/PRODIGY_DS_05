# Project Title: Traffic Accident Analysis — Patterns in Road, Weather, and Time

## Problem Definition
Road accidents pose major safety concerns. This project analyzes US traffic accident data to identify patterns related to time, weather, and location, aiming to assist in preventive safety measures.

## Dataset Overview
- **Source**: Kaggle Notebook
- **Link**: https://www.kaggle.com/code/harshalbhamare/us-accident-eda
- **Dataset**: US Accidents (2016–2020)
- **Attributes**:
  - `Start_Time`, `End_Time`, `City`, `State`
  - `Weather_Condition`, `Visibility`, `Humidity`, `Temperature`
  - `Severity`, `Traffic_Signal`, `Sunrise_Sunset`, etc.

## Objectives
- Identify accident peaks by time and day
- Study weather and road impact on severity
- Detect accident-prone areas using geospatial tools
- Visualize patterns for policymaking

## Tools and Libraries Used
- `Pandas`, `NumPy` – data manipulation
- `Matplotlib`, `Seaborn`, `Plotly` – visualizations
- `Folium` – map-based geospatial plotting
- `datetime` – time-based operations

## Steps Followed

### 1. Data Exploration & Cleaning
- Load and preview data
- Handle missing values and duplicates
- Convert date-time fields

### 2. Time-Based Analysis
- Identify peak hours and days
- Compare weekdays vs weekends
- Analyze seasonal and yearly patterns

### 3. Weather & Road Conditions
- Analyze accidents by weather type
- Study impact of visibility, humidity, and traffic lights

### 4. Geospatial Analysis
- Map accident locations using `Folium`
- Create heatmaps to find hotspots
- Analyze accidents by state/city

### 5. Severity Distribution
- Visualize severity levels
- Identify cities with high severity incidents

## Output
- Heatmaps of accident hotspots
- Time-wise accident charts
- Weather-related severity insights
- High-risk states and cities

## Conclusion
This analysis supports data-driven decisions for traffic safety, enabling authorities to:
- Improve emergency preparedness
- Install weather-responsive alerts
- Upgrade infrastructure in danger zones

## Key Insights
- Peak accidents during morning and evening rush hours
- Rain, fog, and poor visibility increase accident rates
- California, Florida, and Texas are top accident-reporting states
- Fridays and winter months show higher accident volumes
