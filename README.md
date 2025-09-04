# 📊 Amazon Electronics Sales Analysis – 2025

## 📌 Project Overview
This project analyzes **42,000+ Amazon Electronics products** dataset to uncover what drives sales, ratings, and discounts.  
It covers **data cleaning, EDA, insights generation, and business recommendations**.

---

## 📂 Dataset Description
- **File 1:** `amazon_products_sales_data_cleaned.csv` → Ready-to-use dataset  
- **File 2:** `amazon_products_sales_data_uncleaned.csv` → Raw dataset for cleaning practice  

### Key Features:
- `product_title` – Full name of product  
- `product_rating` – Avg rating (out of 5)  
- `total_reviews` – Number of reviews  
- `purchased_last_month` – Units sold last month  
- `discounted_price`, `original_price`, `discount_percentage` – Pricing details  
- `is_best_seller`, `has_coupon`, `is_sponsored` – Tags impacting sales  
- `product_category` – Category of product  

---

## 🛠️ Workflow

1. **Data Cleaning (Uncleaned File)**  
   - Handled missing values  
   - Standardized column names  
   - Filled numeric with median, categorical with mode  

2. **Feature Engineering**  
   - Discount Amount  
   - Deep Discount Flag (>40%)  
   - Rating Buckets (Low / OK / Good / Top)  
   - Log transformation of Reviews  

3. **EDA (Exploratory Data Analysis)**  
   - Category-wise purchases  
   - Discount bands vs sales  
   - Best Seller & Coupon impact  
   - Ratings vs Reviews scatter  
   - Sponsored vs Organic performance  

4. **Insights & Business Takeaways**  

---

## 📊 Visualizations
- Bar plots for category sales & discounts  
- Scatter plot for rating vs reviews  
- Bar plots for Best Seller, Coupons, Sponsored items  

---

## 📝 Key Insights
- Products in **30–40% discount band** show the highest average purchases.  
- **Best Seller + Coupon** products drive ~1.6× higher sales.  
- Beyond **4.6 rating**, reviews matter more than ratings.  
- Mobile Accessories & Laptops dominate purchases.  
- Sponsored products outperform organic listings.  

---

## 📌 Executive Summary

| Business Question                  | Key Finding                                                   |
|------------------------------------|---------------------------------------------------------------|
| Which categories sell the most?    | Mobile Accessories & Laptops dominate purchases.             |
| Which discount range drives sales? | 30-40% discount band shows the highest average purchases.     |
| Do Best Seller tags matter?        | Best Seller products drive ~2x higher sales.                 |
| Do Coupons influence purchases?    | Products with coupons sell ~1.5x more on average.            |
| Ratings vs Reviews – what matters? | Beyond 4.6 rating, number of reviews impacts sales more.     |

---

## 🚀 Next Steps
- Build a **sales forecasting model** (time-series or regression).  
- Develop a **recommendation system** (ratings + reviews).  
- Apply **NLP on product titles** for automatic category prediction.  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **GitHub** for project showcase  

---

👨‍💻 Developed by **Akash Kumar Tiwari (MCA 2023–2025, SRM University)**  

