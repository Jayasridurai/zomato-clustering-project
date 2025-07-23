# Zomato Clustering and Sentiment Analysis Project

## Project Overview

This project focuses on analyzing customer reviews from Zomato to uncover meaningful business insights using **data visualization, feature scaling, sentiment-based clustering**, and **KMeans clustering**. The primary goal is to segment restaurants based on their cost and review behavior and help both customers and the company make better decisions.

##  Problem Statement

The aim is to analyze the sentiment of customer reviews and segment Zomato restaurants into meaningful clusters. This helps customers find suitable restaurants and enables Zomato to understand areas needing improvement and growth. The project uses review length, cost, and rating to derive insights and identify patterns.

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn (StandardScaler, KMeans)
- Jupyter Notebook

## Key Steps Performed

1. **Data Cleaning:** Removed duplicates, handled nulls, and transformed key features.
2. **Feature Engineering:** Derived `Review_Length_Log` and scaled features like `Cost`.
3. **Exploratory Data Analysis (EDA):** Visualized trends and relationships.
4. **Clustering:** Used KMeans clustering and Elbow Method to find the optimal K.
5. **Post-Clustering Analysis:** Interpreted results using scatter plots and cluster group means.

## Insights

- Cluster 1: High-cost restaurants with long reviews and better ratings.
- Cluster 2: Low to mid-range cost restaurants with moderate review activity.
- Businesses can use this segmentation to target customers better.
- Customers benefit by finding cost-effective and well-reviewed places.

## Project Structure
├── Zomato_Clustering_Analysis.ipynb # Main analysis notebook
├── dataset.csv # Dataset used (if shared)
├── README.md # Project overview and details

## Future Improvements

- Integrate sentiment analysis using NLP techniques.
- Add geolocation data for city-wise recommendations.
- Build a recommendation system based on review patterns.

## Conclusion

This project demonstrates how data-driven insights can help businesses and consumers make informed choices. Clustering and EDA techniques are powerful tools for segmenting the market and improving service offerings.

