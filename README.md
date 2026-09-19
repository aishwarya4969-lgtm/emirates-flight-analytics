# emirates-flight-analytics# 

I built a clean, dark-themed dashboard to look at passenger trends and flight data for Emirates. Instead of using standard white charts, I styled the visual grids using a deep slate blue background and neon cyan markers so the metrics jump out instantly.

The main goal here was to take an airline operations dataset and turn it into clear visual panels that show a clean business story.

## What this dashboard tracks:
* **Yearly Passenger Trends:** A clean line chart showing how overall seat capacity has scaled up over the years.
* **Flight Density:** A distribution plot highlighting the baseline number of passengers on typical routes.
* **Peak Travel Seasons:** A month-by-month bar chart identifying exactly which times of the year see the highest customer traffic.
* **Fleet Stability:** A boxplot tracking how much flight numbers fluctuate, helping to spot patterns in travel consistency.

## How I built it:
* **Python & Pandas:** For organizing the data, filtering out missing information, and renaming columns to match Emirates' KPIs.
* **Matplotlib & Seaborn:** For designing the charts and overriding the default settings to give it a custom UI appearance.
* **Google Colab:** The code runs completely in the cloud, bypassing network bottlenecks by utilizing pre-packaged library environments.

The entire project runs natively in the browser and updates directly to GitHub in a couple of clicks without downloading anything locally.
