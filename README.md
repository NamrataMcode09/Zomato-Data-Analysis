# 🍽 Zomato Data Analysis & Predictive Modeling

## 📌 Project Overview
This project was completed as part of my internship at **Cognify** and focuses on performing **Exploratory Data Analysis (EDA)** and **predictive modeling** on Zomato restaurant data. The goal was to understand customer behavior, discover insights across geographies and cuisine preferences, and predict aggregate restaurant ratings using machine learning.

---

## 🗃 Dataset
- **Source:** Zomato restaurant data (open dataset)
- **Size:** 9551 rows × 21 columns
- **Content:** Restaurant names, cuisines, location, votes, price range, delivery/table booking options, aggregate ratings, and more.

---

## 🧪 Project Structure

### 🔍 LEVEL 1: Data Exploration & Preprocessing
- Missing value treatment
- Data type conversions
- Handling class imbalance in target variable (ratings)

### 📊 LEVEL 2: Descriptive Analysis
- City-wise and cuisine-wise distribution
- Price range vs rating
- Votes and other numerical insights

### 🌍 LEVEL 3: Geospatial Analysis
- Restaurant distribution by city
- Location influence on rating (urban vs periphery)

### 🍽 LEVEL 4: Table Booking & Online Delivery
- Impact of services on ratings
- Frequency across pricing segments

### 💰 LEVEL 5: Price Range Analysis
- Relationship between price and satisfaction
- Distribution across rating text

### 🧠 LEVEL 6: Feature Engineering
- Created:
  - `Restaurant_Name_Length`
  - `Address_Length`
  - Binary features for booking/delivery
  - Label encoding for categorical variables

### 🤖 LEVEL 7: Predictive Modeling
- Models Tried:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor ✅ (Best)
- Evaluation Metrics:
  - R² Score
  - Mean Squared Error (MSE)

### ❤️ LEVEL 8: Customer Preference Analysis
- Most voted cuisines vs highest rated
- Urban taste vs niche followings

### 📈 LEVEL 9: Data Visualization
- Used Seaborn and Matplotlib
- Bar plots, scatter plots, heatmaps, and distribution plots

---

## 💡 Key Takeaways
- **Random Forest Regressor** gave the best performance in predicting aggregate ratings.
- **Votes, Price Range, Online Delivery**, and **City** were top predictors.
- Premium areas and higher-end services correlated with better ratings.

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

