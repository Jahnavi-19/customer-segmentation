# Customer Segmentation using Clustering
# Project Overview
This project aimed to perform customer segmentation and market basket analysis using the Online Retail dataset. The goal was to leverage customer purchasing data to identify key customer segments and product purchasing patterns, enabling more effective marketing strategies. It required not only analyzing data to uncover meaningful insights but also engineering a clean, structured dataset to ensure efficient analysis and model performance. The entire pipeline, from data cleaning to segmentation and association rule mining, involved both analytical and engineering processes.
# Objective
The primary objective of the project was to understand customer behavior by dividing customers into distinct segments based on purchasing patterns and to identify product combinations frequently bought together. This was achieved by applying RFM (Recency, Frequency, Monetary) analysis, K-Means clustering, and Apriori algorithms. Alongside these analyses, the project also involved creating a scalable, clean data pipeline for future analysis, ensuring the dataset was prepared, transformed, and structured for optimal performance across multiple analytical techniques.
# Key Features and Techniques Used
* Customer Segmentation: Implemented RFM (Recency, Frequency, Monetary) analysis to categorize customers based on purchasing behavior, aiding in targeted marketing.
* Clustering: Utilized the K-Means algorithm to identify distinct customer groups, optimizing customer engagement and retention strategies.
* Market Basket Analysis: Applied the Apriori algorithm to discover associations between products, enhancing cross-selling and inventory management strategies.
* Data Cleaning and Preprocessing: Conducted thorough data cleaning to remove duplicates and handle missing values, ensuring high-quality datasets for analysis.
* Visualization: Employed libraries like Matplotlib and Seaborn for data visualization to better understand customer behaviors and trends.
# Tools and Technologies
* Programming Language: Python 3.8
## Libraries:
* Data Manipulation: Pandas, NumPy
* Visualization: Matplotlib, Seaborn
* Machine Learning: K-Means
* Environment: Jupyter Notebook (via Anaconda)
# Results and Insights
* Identified four customer segments based on purchasing behaviors, improving targeted marketing efforts
* Determined that November had the highest sales, with peak customer activity on Thursdays
* Found that 11 AM - 1 PM was the prime sales period
* UK customers contributed the most orders and revenue, while customers from Netherlands, Australia, and Singapore were identified as valuable segments
* Key products included lunch bags, dolls, and candles, informing future inventory decisions
# Conclusion
The project successfully performed customer segmentation, classification, and RFM analysis, revealing distinct purchasing patterns across five to six customer clusters. The Light GBM model effectively identified potential target customers. Market Basket Analysis highlighted associations among products, particularly among teacups, indicating opportunities for product variation to enhance sales
