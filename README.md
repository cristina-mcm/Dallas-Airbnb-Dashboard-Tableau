# Dallas Airbnb Dashboard – 2026 Data Snapshot

## Project Overview

This project analyzes Airbnb listings and calendar availability in Dallas, Texas. The interactive Tableau dashboard explores listing locations, nightly prices, property sizes, and changes in reported availability over time.

The dataset is a snapshot collected on July 20, 2026.

## Dashboard

<img width="1512" height="1235" alt="Screenshot 2026-09-02 194727" src="https://github.com/user-attachments/assets/35babd84-9d1a-4f9a-be45-70dba8b9ed3a" />

[View the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/cristina.mcm/viz/AirbnbDallas2026Data/Dashboard1)

## Analysis

The dashboard examines:

- The geographic distribution of Airbnb listings across Dallas neighborhoods
- The number of listings by bedroom count
- Median nightly price by bedroom count
- The percentage of calendar days marked as available
- Differences in listing prices and availability across the Dallas market

## Key Findings

- One-bedroom properties dominate the market with 2,540 listings, followed by two-bedroom and three-bedroom properties.
- Median price generally increases with bedroom count, rising from $156 for one-bedroom properties to $2,282 for sixteen-bedroom properties. Categories with many bedrooms contain relatively few listings, so their prices may be less representative.
- Districts 6 and 13 have the highest average listing prices at over $500, while most other districts average approximately $220–$325.
- Calendar availability declines from about 77% in January to its lowest point of approximately 58% in July, before recovering to nearly 79% in December.

## Data Sources

The data was obtained from [Inside Airbnb](https://insideairbnb.com/get-the-data/) and includes:

- Detailed Dallas Airbnb listing information
- Daily calendar availability
- Dallas neighborhood boundaries in GeoJSON format

The listings and calendar tables were connected using the listing ID. The neighborhood GeoJSON file was connected to the listings data using the cleaned neighborhood field.

## Repository Contents

- `Data` – Dallas Airbnb listings, calendar data, and neighborhood boundaries
