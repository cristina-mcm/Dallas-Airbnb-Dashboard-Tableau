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

## Data Sources

The data was obtained from [Inside Airbnb](https://insideairbnb.com/get-the-data/) and includes:

- Detailed Dallas Airbnb listing information
- Daily calendar availability
- Dallas neighborhood boundaries in GeoJSON format

The listings and calendar tables were connected using the listing ID. The neighborhood GeoJSON file was connected to the listings data using the cleaned neighborhood field.

## Repository Contents

- `Data` – Dallas Airbnb listings, calendar data, and neighborhood boundaries
