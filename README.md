🍽️ Zomato Kolkata Restaurant Analytics & Performance Optimization

📌 Project Overview

This project is an end-to-end Data Analytics and Machine Learning analysis of Zomato restaurant data for Kolkata. The objective is to analyze restaurant performance, understand factors influencing customer ratings, simulate business improvement scenarios, and build a predictive model for restaurant ratings.

The project demonstrates real-world data handling**, feature engineering,exploratory data analysis (EDA), performance recalculation, and machine learning modeling, along with business-driven insights.
🎯 Objectives

* Perform end-to-end data analytics on real-world restaurant data
* Explore the relationship between ratings, cost, customer engagement, and delivery availability
* Engineer meaningful features from raw data (ratings, votes, cost categories)
* Create a custom performance score for restaurant ranking
* Simulate business scenarios such as **home delivery enablement** and **cost optimization**
* Build a machine learning model to **predict restaurant ratings**

🗂 Dataset

Source: Zomato Kolkata Restaurants dataset
Key Attributes:

  * Dinner Ratings
  * Delivery Ratings
  * Dinner Reviews
  * Delivery Reviews
  * Average Cost
  * Home Delivery Availability

🔧 Data Processing & Feature Engineering

* Standardized column names for consistency
* Cleaned and converted string-based ratings (e.g., `4.2/5`, `NEW`) into numeric values
* Combined **dinner and delivery ratings** into a single unified `rating`
* Created:

  * `votes` (combined dinner + delivery reviews)
  * `cost_category` (Low / Medium / High / Premium)
  * `Home_Delivery_Flag` (binary feature)
* Handled missing values and ensured numeric consistency

 📊 Exploratory Data Analysis (EDA)

The project includes:

* **Univariate Analysis:** Rating distribution
* **Bivariate Analysis:** Cost vs Rating, Home Delivery vs Rating
* **Multivariate Analysis:** Pair plots and correlation heatmap
* **Outlier Analysis:** Boxplots across cost categories
* **Location & Cuisine insights**

---

## ⭐ Performance Scoring & Recalculation

* Designed a **weighted Performance Score** using:

  * Ratings (50%)
  * Customer engagement via reviews (30%)
  * Home delivery availability (20%)
* Simulated business scenarios:

  * **Revised Rating:** Impact of enabling home delivery
  * **Optimized Rating:** Impact of cost optimization
* Identified underperforming restaurants for improvement recommendations

---

## 🤖 Machine Learning

* Built a **Linear Regression model** to predict restaurant ratings
* Features used:

  * Average Cost
  * Customer Engagement (Votes)
* Model evaluated using **Mean Absolute Error (MAE)**

---

## 📈 Dashboard (Power BI / Tableau – Design Ready)

* KPI cards (Average Rating, Cost, Delivery Availability)
* Cost vs Rating scatter plot
* Location-wise performance
* Cuisine popularity
* Restaurant performance ranking table

---

## 🛠 Tech Stack

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Visualization:** Power BI / Tableau (design)
* **Environment:** Jupyter Notebook

---

## 💡 Key Insights

* Medium-cost restaurants tend to receive higher ratings
* Home delivery availability positively impacts customer ratings
* High cost does not guarantee high performance
* Customer engagement (reviews) strongly correlates with ratings

---

## 📌 Conclusion

This project showcases a **complete analytics workflow**, from raw data cleaning to business-driven insights and predictive modeling. It reflects practical skills required for **Data Analyst, Business Analyst, and Entry-Level Data Science roles**.
Dashboard-
<img width="995" height="662" alt="image" src="https://github.com/user-attachments/assets/76b23252-8fb7-49b7-be52-c6fd207eadd1" />
<img width="949" height="630" alt="image" src="https://github.com/user-attachments/assets/b862ee60-52a2-494d-9973-4b21d5bf5aa2" />




