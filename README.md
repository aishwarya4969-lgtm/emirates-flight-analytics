# emirates-flight-analytics# 

I built a clean, dark-themed dashboard to look at passenger trends and flight data for Emirates. Instead of using standard white charts, I styled the visual grids using a deep slate blue background and neon cyan markers so the metrics jump out instantly.

The main goal here was to take an airline operations dataset and turn it into clear visual panels that show a clean business story.


#Key Insights

Growth Came with Chaos: Capacity jumped over 60% (from ~3,400 to 5,500+), booming after 1958. However, operational volatility doubled by 1960. Pushing the fleet harder made scheduling far more unpredictable and prone to delays.

The 50% Summer Surge: The airline handles two totally different demand levels. Occupancy spikes by 50% in June, July, and August (near 500 passengers) compared to quiet winter baselines (~320).

The 350-Passenger Sweet Spot: The vast majority of flights carry between 325 and 375 passengers. While a few outlier routes push toward 600, these high-density, mid-sized routes are the airline's real bread and butter


## How I built it:
* **Python & Pandas:** For organizing the data, filtering out missing information, and renaming columns to match Emirates' KPIs.
* **Matplotlib & Seaborn:** For designing the charts and overriding the default settings to give it a custom UI appearance.
* **Google Colab:** The code runs completely in the cloud, bypassing network bottlenecks by utilizing pre-packaged library environments.


