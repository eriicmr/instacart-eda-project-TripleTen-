# 🛒 Instacart Customer Behavior Analysis – Sprint 3 Project  

This project applies **Exploratory Data Analysis (EDA)** to a modified version of the Instacart dataset.  
The goal is to clean the data, explore customer shopping patterns, and create visualizations that provide insights into **ordering habits, product demand, and reordering behavior**.  

---

## 📌 Project Overview  

The analysis is divided into three main stages:  

1. **Data Overview & Preparation**  
   - Loaded and inspected five CSV files (`orders`, `products`, `order_products`, `aisles`, `departments`)  
   - Handled missing values, duplicates, and corrected data types  
   - Documented preprocessing decisions and reasoning  

2. **Exploratory Analysis (Part A & B – Required)**  
   - Verified logical ranges in `order_hour_of_day` and `order_dow`  
   - Visualized ordering patterns by hour, day of week, and time between orders  
   - Compared ordering habits on different days (e.g., Wednesday vs. Saturday)  
   - Identified the top 20 most frequently purchased products  
   - Explored customer order distribution (number of orders per customer)  

3. **Advanced Analysis (Part C – Optional/Bonus)**  
   - Distribution of items per order  
   - Top 20 most frequently reordered products  
   - Proportion of repeat orders per product and per customer  
   - First items most often added to carts  

Each step included **visualizations** with clear titles, labeled axes, and legends.  

---

## 🛠️ Tools & Technologies  
- Python 3.x  
- Jupyter Notebook  
- Libraries:  
  - `pandas` (data cleaning & manipulation)  
  - `numpy` (numerical operations)  
  - `matplotlib`, `seaborn` (data visualization)  

---

## 📂 Dataset  

Files used:  
- `instacart_orders.csv` — order-level information (user, time, day, order sequence)  
- `products.csv` — product IDs and names  
- `order_products.csv` — mapping between orders and purchased products  
- `aisles.csv` — aisle categories  
- `departments.csv` — department categories  

Data was adapted from the original [Instacart Kaggle dataset (2017)](https://www.kaggle.com/c/instacart-market-basket-analysis).  

---

## 🎯 Key Learning Outcomes  
- Practiced **data preprocessing**: handling missing values, duplicates, and inconsistent types  
- Developed **EDA skills** by asking business-driven questions and validating assumptions  
- Strengthened ability to communicate insights through **visualizations and commentary**  
- Gained experience working with **relational datasets** across multiple CSV files  

---

## 🚀 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/eriicmr/instacart-eda-project.git
