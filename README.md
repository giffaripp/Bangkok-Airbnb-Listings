# Bangkok-Airbnb-Listings
# 1. Project Overview

This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus is to find the most promising location or district to rent a property for Airbnb Listings in Bangkok Metropolitan.

Key Objectives:
* Objective 1: Analyze the average price of Airbnb listings by district in the Bangkok Metropolitan Area.
* Objective 2: Analyze the average occupancy rate of Airbnb listings by district in the Bangkok Metropolitan Area.
* Objective 3: Identify the most promising district for Airbnb rental properties in the Bangkok Metropolitan Area.

# 2. Data Sources
* Dataset 1 - Airbnb Listing Bangkok.csv

# 3. Technologies Used
* Programming Language: Python, Pandas, and Numpy
* Visualization: Matplotlib, Seaborn, Plotl, and Looker Studio
* Interactive Dashboard: Looker Studio
* Version Control: GitHub
* Environment: Jupyter Notebook

# 4. Project Structure
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as PowerPoint, PDF, LaTeX, etc.
|   ├── slide          <- Generated PowerPoint
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

# 5. Summary of Finding
## 5.1 Business Insight
### Most Promising District
* Watthana, Khlong Toei, and Bang Rak are the most promising districts for Airbnb property investment. These areas combine high average nightly prices with strong occupancy rates, indicating high demand and willingness to pay among travelers.
### Affordable Prices but Low Demand District
* Outer districts (e.g., Lat Krabang, Nong Chok, and Bang Khun Thian) show low occupancy despite affordable prices. Recommend targeted marketing campaigns (long-stay offers, proximity to airports/universities) to improve visibility and bookings.
### Price Optimiztion
* Price optimization is key — listings with moderate prices (฿1,500–฿2,500/night) show higher occupancy consistency than both low and luxury listings. Suggest implementing dynamic pricing strategies based on seasonality and local demand.
### Price and Occupancy correlation.
Neighbourhoods with high potential scores reflect a balance between revenue (price) and utilization (occupancy). Investors should prioritize districts scoring above 0.80 in potential score as optimal zones for short-term rental expansion.
## 5.2 Actionable Recommendation
### Prioritize property investment in high-potential districts
* Focus expansion in most promising district, which consistently show high average prices and occupancy rates. These districts offer the best balance between revenue and utilization, making them ideal for new listings or property acquisitions.
### Implement dynamic pricing strategies
Use demand-based pricing tools to automatically adjust nightly rates according to season, events, and occupancy trends. This approach maximizes revenue during peak seasons (e.g., Songkran, New Year) and increases occupancy during low-demand periods.
# 6. Data Visualization
Data visualization for this project displayed by dashboard analysis using Looker Studio. 
https://lookerstudio.google.com/reporting/07705b3d-1a5b-45c2-94e7-0131d1f3ad0c
# 7. Conclusion
The analysis successfully identified key districts with the highest potential for Airbnb property investment in the Bangkok Metropolitan Area. Overall, the findings reinforce that pricing strategy, location selection, and operational quality are the most influential factors for Airbnb success.
This project demonstrates how data analysis can transform raw listings data into actionable insights to support smarter investment and management decisions in the hospitality and property sectors.

