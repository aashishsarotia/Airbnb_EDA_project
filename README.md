# Airbnb New York EDA Project

### Project Overview
This project involves performing Exploratory Data Analysis (EDA) on a dataset of Airbnb listings in New York for the year 2024. The goal is to derive meaningful insights regarding pricing, availability, host listings, and neighborhood trends to better understand the Airbnb market. This analysis can help property owners, guests, and real estate professionals make data-driven decisions.

### Dataset
The dataset contains Airbnb listings in New York and includes a variety of information about each listing, such as:
- **ID and Name** of the listing
- **Host Information**: host name, host ID, and the number of listings per host
- **Location Details**: neighborhood group, neighborhood, latitude, and longitude
- **Room Type**: Entire home/apt, private room, shared room, etc.
- **Price and Availability**: nightly price, availability over the year, and number of reviews
- **Additional Features**: ratings, number of bedrooms, beds, and baths

### EDA Process

1. **Data Exploration**:  
   The dataset is explored to understand the structure, including checking for null values, duplicate entries, and potential outliers. Key insights into pricing, room types, and distribution across neighborhoods are derived.

2. **Data Cleaning**:  
   Unnecessary columns were removed, and missing values in relevant columns such as `reviews_per_month`, `beds`, `bathrooms`, and `license` were handled using imputation or exclusion, depending on the scenario.

3. **Data Analysis**:  
   - **Price Distribution**: The analysis shows a skewed distribution of prices, with most listings clustered at lower price ranges, but some extreme outliers are identified and explored.
   - **Room Type Comparison**: The data reveals trends across different room types. Entire homes/apartments tend to have higher prices compared to private or shared rooms.
   - **Neighborhood Insights**: Neighborhood groups like Manhattan and Brooklyn have the highest concentration of listings, with prices varying significantly depending on the area.
   - **Host Analysis**: Insights about hosts, such as the number of listings per host and the effect of super-hosts on pricing and reviews.

4. **Visualizations**:  
   Several visualizations were created to support the analysis:
   - Distribution of prices using histograms
   - Heatmaps for neighborhood-wise availability and pricing trends
   - Scatter plots to show relationships between price, location, and reviews
   - Box plots to understand price variations across room types

### Key Findings

- **Price Variations**: Significant price variation across neighborhoods, with Manhattan being the most expensive on average.
- **Host Activity**: A few hosts manage a large number of listings, showing the influence of professional property managers on the market.
- **Room Type Insights**: Entire homes command a higher price, but private rooms are more common in neighborhoods like Brooklyn and Queens.
- **Seasonal Availability**: Some listings have very limited availability, indicating seasonal trends or strategic bookings.

### Recommendations

Based on the analysis, here are some strategic recommendations for various stakeholders:

1. **For Hosts**:
   - **Dynamic Pricing**: Hosts can adopt dynamic pricing strategies, especially in areas like Manhattan, where prices fluctuate significantly. Higher prices can be set during peak seasons or when demand is high, while lower prices could attract more bookings during off-peak times.
   - **Increase Reviews**: Listings with more reviews tend to perform better. Encouraging guests to leave reviews through follow-ups or offering small incentives could improve visibility and trust, leading to more bookings.
   - **Leverage Professional Management**: Hosts with multiple listings should consider professional management services. These services can help optimize pricing, manage availability, and ensure a consistent guest experience, especially if managing over 10 listings.

2. **For New Airbnb Hosts**:
   - **Start in Less Competitive Areas**: New hosts could start in neighborhoods like Brooklyn or Queens, where competition is lower compared to Manhattan. Offering competitive pricing in these areas can help attract guests who are budget-conscious but still want to stay relatively close to tourist hotspots.
   - **Focus on Room Types**: If starting with a private room or shared room listing, it’s important to price competitively and offer unique amenities to stand out from the crowd.

3. **For Guests**:
   - **Book Early for Lower Prices**: Prices tend to increase as availability decreases closer to check-in dates, especially in high-demand neighborhoods. Booking well in advance can help guests secure better deals.
   - **Consider Alternative Neighborhoods**: Guests could explore neighborhoods outside of Manhattan, such as Brooklyn or Queens, for more affordable stays without sacrificing too much proximity to the city center.

4. **For Airbnb**:
   - **Improve Availability Information**: Airbnb could enhance its platform by offering clearer insights into seasonal availability trends, helping guests make informed decisions and encouraging bookings in underutilized periods.
   - **Incentivize Super Hosts**: Rewarding super hosts with better listing visibility or lower fees could further improve guest experiences, ensuring consistent quality across top-performing hosts.

### Technologies Used
- **Pandas**: For data manipulation and cleaning
- **Matplotlib and Seaborn**: For visualizations
- **Numpy**: For numerical computations
- **Jupyter Notebook**: For documenting and presenting the analysis

### Conclusion
This project provides an in-depth analysis of the Airbnb listings in New York, offering valuable insights into pricing dynamics, host behavior, and neighborhood trends. The recommendations provided can guide hosts, guests, and the platform itself in making data-driven decisions to improve the overall Airbnb experience.



