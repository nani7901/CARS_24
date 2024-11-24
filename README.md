# CARS_24
## Problem Statement
The used car market has evolved significantly in recent years, with shifting trends in car brand popularity, transmission preferences, and pricing dynamics. Understanding these changes is crucial for stakeholders like car dealerships, manufacturers, and consumers to make informed decisions. This project aims to analyze the second-hand car market using data scraped from Cars24.com. The focus is on gaining insights into car brand preferences, price fluctuations, transmission types, and market trends. By examining consumer preferences, regional variations, and industry shifts, the project aims to uncover actionable insights that could guide business strategies and future market developments.
## Project Overview
This project leverages web scraping, data cleaning, and exploratory data analysis (EDA) to study the second-hand car market, focusing on key aspects like car brand popularity, transmission trends, and price dynamics. The data has been collected from multiple locations across India, and includes a variety of features such as car brand, year of manufacture, transmission type, fuel type, price, and more. After scraping and merging the data into a single comprehensive dataset, several key trends and insights are derived to understand market shifts and consumer behavior.

## Key Insights
### Car Brand Popularity:

Maruti is the dominant brand in the used car market, followed by Hyundai and Toyota.
Some newer brands like KIA and MG have higher price points, but their market share is comparatively smaller.
### Transmission Trends:

There has been a shift from manual to automatic transmissions over the years, with consumers increasingly favoring automatic cars for convenience and comfort.
### Price Trends:

Newer cars, especially those manufactured in recent years, command higher prices.
There are outliers, where some older cars are priced higher, indicating special cases such as rare or high-demand models.
### Market Dynamics:

After 2017, there has been a noticeable decline in the number of newer cars available in the second-hand market, likely due to shifts in industry trends and economic factors.
### Consumer Insights:

Consumers are gravitating toward automatic transmissions and newer models, with Maruti and Hyundai remaining dominant in the budget-conscious segment.
### Objective
To analyze the second-hand car market trends in terms of car brand preferences, transmission types, and pricing over the years.
To provide insights into changing consumer behavior, helping businesses align with market demands and make data-driven decisions.
To understand the market dynamics and predict future trends in the second-hand car market.
## Libraries Used
BeautifulSoup (BS4): For scraping data from Cars24.com.
Requests: To send HTTP requests and retrieve web data.
Pandas: For data manipulation, cleaning, and merging.
NumPy: For numerical operations and data transformations.
Matplotlib & Seaborn: For data visualization and plotting insights.
## Data Collection and Processing
Web Scraping: Data was collected by scraping car listings from various locations on Cars24.com. The dataset includes key attributes like brand, price, fuel type, transmission type, and year of manufacture.
Data Merging: After scraping data from multiple locations, all CSV files were loaded, cleaned, and merged into a single comprehensive dataset.
## Exploratory Data Analysis (EDA):
I Used various EDA techniques to understand key trends in the used car market, with a focus on price variations, brand popularity, and transmission type trends.

### Merge Data: After scraping, you can merge all location-based data using the merge_data.py script.

### Perform EDA: Analyze the data and generate insights using the cars24_eda.ipynb Jupyter notebook.

### Visualizations
Price Distribution by Brand: A clear visual representation of how car prices vary by brand.
Transmission Type Analysis: Insights into the shift from manual to automatic transmissions over time.
Year of Manufacture vs. Price: A trend analysis showing how car prices are correlated with the year of manufacture.
## Conclusion
The project provides a comprehensive analysis of the second-hand car market, revealing significant insights about consumer preferences, brand dominance, and price trends. These findings can guide future business decisions in the automotive industry and help understand the evolving consumer behavior in the used car market.
