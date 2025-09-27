# 🍽️ Zomato Restaurant Data Analysis Using Python  

## 📖 Overview  
This project performs **Exploratory Data Analysis (EDA)** on the Zomato restaurant dataset to uncover useful business insights. The analysis focuses on:  

- Which types of restaurants are most popular  
- How online ordering impacts ratings and votes  
- The relationship between cost, ratings, and restaurant type  

---

## 🔧 Steps Performed  

### 1. Data Cleaning  
- Removed **null values** and **duplicates**  
- Converted **cost column** into numeric format  
- Cleaned **categorical variables** (e.g., restaurant type, online orders)  

### 2. Exploratory Data Analysis (EDA)  
- **Univariate Analysis** → Restaurant types, votes distribution, ratings  
- **Bivariate Analysis** → Cost vs Rating, Online vs Offline orders  
- **Multivariate Analysis** → Correlation between numerical features  

### 3. Data Visualization  
Created meaningful visualizations with **Matplotlib** and **Seaborn**, including:  
- Bar plots for restaurant types  
- Line plots for vote trends  
- Box plots for cost vs rating  
- Heatmaps for feature correlation  

---

## 📊 Key Visualizations  
- **Distribution of Restaurant Types** (Bar Plot)  
- **Restaurant Votes Trend** (Line Plot)  
- **Online vs Offline Orders** (Bar & Box Plots)  
- **Cost for Two vs Rating** (Box Plot)  
- **Correlation Heatmap** between features  

---

## 💡 Insights  
- **Dining restaurants dominate** Zomato listings.  
- Most restaurants have **ratings between 3.0 – 4.0**.  
- Restaurants with **online ordering receive more votes** than offline-only ones.  
- **Cost-effective restaurants** are more common than premium ones.  
- Interestingly, **offline orders tend to have slightly higher ratings** than online orders.  

---

## 🛠️ Tools & Libraries  
- **Python**  
- **NumPy, Pandas** → Data cleaning & manipulation  
- **Matplotlib, Seaborn** → Data visualization  


# Run the notebook
jupyter notebook Zomato_EDA.ipynb
