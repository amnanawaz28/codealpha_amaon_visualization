# codealpha_amaon_visualization
📊 Data Visualization — Amazon Sales Dataset
CodeAlpha Data Analytics Internship | Task 3

📌 Overview
This project transforms raw Amazon Sales data into compelling, story-driven visualizations using Python. The focus is on building a variety of chart types that reveal clear insights about product pricing, discounts, ratings, and categories.

📂 Dataset

Source: Amazon Sales Dataset — Kaggle
File: amazon.csv
Size: 1,465 products across multiple categories
Key Columns: product_name, category, actual_price, discounted_price, discount_percentage, rating, rating_count


🎨 Visualizations Built
#ChartType1Rating DistributionHistogram + KDE Curve2Top 10 Product CategoriesHorizontal Bar Chart3Discount Tier BreakdownDonut Chart4Avg Discount % by CategoryColor-Coded Bar Chart5Rating vs Reviews vs PriceBubble Chart6Actual vs Discounted PriceGrouped Bar Chart7Rating by Discount TierViolin Plot8Product Name TrendsWord Cloud9Feature RelationshipsCorrelation Heatmap10Full Summary4-Panel Dashboard

💡 Key Insights

Ratings are consistently high (3.8 – 4.5) across all discount tiers
Most products fall in the 40–60% discount range
Electronics categories have the highest median prices
Popular products (high review count) tend to maintain better ratings
Word cloud reveals USB, Wireless, and Smart as the most common product descriptors


🛠️ Tools & Libraries
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
WordCloud
Jupyter Notebook

▶️ How to Run

Clone this repository

bashgit clone https://github.com/amnanawaz28/codealpha_amaon_visualization

Install dependencies

bashpip install pandas numpy matplotlib seaborn wordcloud

Download amazon.csv from Kaggle and place it in the project folder
Open and run the notebook
