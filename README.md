# This file details all current Projects in this folder
# Project 1
# MovieLens Recommender System 🎬

A collaborative filtering recommender system built on the **MovieLens 100k dataset** using the **Surprise library (SVD algorithm)**.  
It demonstrates how to preprocess rating data, train/evaluate models, and generate personalized movie recommendations.

## 📊 Dataset
- **u.data** → user, movie, rating, timestamp  
- **u.item** → titles, release year, genres  
- Users: 943 | Movies: 1682 | Ratings: 100,000  

Source: [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/)

## ⚙️ Tools & Libraries
- Python 3.11  
- pandas, numpy, scipy  
- scikit-surprise  

## 🚀 How It Works
1. Load and preprocess MovieLens ratings and movies  
2. Build dataset with Surprise `Reader` and `Dataset.load_from_df`  
3. Train/test split (80%/20%)  
4. Train **SVD** recommender  
5. Evaluate with **RMSE**  
6. Generate top-5 movie recommendations for a user  

## 📈 Results
- Test RMSE: **0.936**  
- Example top-5 recommendations for User 1:
  - Rear Window (1954) → 4.88  
  - L.A. Confidential (1997) → 4.80  
  - A Close Shave (1995) → 4.75
 
  - # Project 2
  - # Nebraska 2025 Expenditures Data Analysis

This project analyzes the public expenditures data for the State of Nebraska in the year 2025. The objective is to understand spending patterns across departments and categories, and to surface key trends and notable expenses.

## Project Overview
- Data sourced from the official Nebraska government website.  
- Focus on cleaning and preparing the dataset for analysis.  
- Exploration of expenditure distribution by department and transaction type.  
- Visualization of top spending departments and monthly spending trends.  
- Identification of unusually large expenses for further investigation.

## What I Did
- Loaded the raw dataset and performed thorough data cleaning, including handling missing values, converting data types, and removing duplicates.  
- Aggregated total expenditures by department and by transaction type to understand spending allocation.  
- Created visualizations to highlight the major spending departments and observe monthly fluctuations in spending.  
- Highlighted some of the largest individual expenses to draw attention to significant outliers.

## Key Takeaways
- A small number of departments account for the majority of the overall spending.  
- Spending patterns fluctuate month-to-month, likely influenced by budget cycles and fiscal policies.  
- Certain large, singular expenses stand out and may warrant detailed examination.

---

## How to Run
1. Download the dataset from the official Nebraska government source or use the provided file in the `data/` folder.  
2. Run the analysis notebook (`Nebraska_Expenditures_2025.ipynb`) to reproduce the cleaning, analysis, and visualizations.  
3. Ensure Python dependencies such as pandas, matplotlib/seaborn are installed.

## Future Work
- Dive deeper into specific departments with notable spending.  
- Analyze year-over-year trends beyond 2025.  
- Automate report generation for continual monitoring of expenditures.  
- Share insights with stakeholders to inform budget decisions.

---

## License
This project uses public Nebraska government data released for research and analysis purposes.

---

👨‍💻 Author: Anthony Schomer

# Project 3  
Supermarket Sales Data Analysis 🛒

An exploratory data analysis project that examines supermarket sales data to reveal store performance, customer traffic patterns, and sales trends. The analysis includes data cleaning, visualization, and insightful summaries to support business decision-making.

## Project Overview  
- Dataset contains daily sales transactions from multiple supermarket locations.  
- Focus on data preparation, exploratory data analysis (EDA), and visualization of sales and customer metrics.  
- Identify sales trends, top-performing stores, and anomalies in the data.

## What I Did  
- Loaded and cleaned raw dataset: handled missing values, data types, and duplicates.  
- Conducted EDA to explore feature distributions and relationships.  
- Created visualizations illustrating sales performance, customer counts, and store metrics over time.  
- Highlighted anomalies and outliers to identify potential data issues or business events.

## Key Takeaways  
- Larger stores with more inventory tend to have higher sales and customer visits.  
- Sales exhibit seasonal and weekly patterns, with variability across stores.  
- Customer traffic is strongly correlated with daily sales volumes.  
- Anomalous sales days were flagged for further investigation.

---

## How to Run  
1. Download or place the dataset file `supermarket_sales.csv` in the `data/` folder.  
2. Run the notebook `Supermarket_Sales_Analysis.ipynb` to reproduce the cleaning, analysis, and visualizations.  
3. Install dependencies: pip install pandas numpy matplotlib seaborn
## Future Work  
- Incorporate time series forecasting for sales prediction.  
- Extend analysis to product-level sales and inventory optimization.  
- Build machine learning models for customer segmentation.  
- Develop interactive dashboards for real-time sales monitoring.

---

## License  
This project uses publicly available supermarket sales data for educational and analytical purposes.

---

👨‍💻 Author: Anthony Schomer
