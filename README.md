## 🛍️ Objective  
Vrinda Store aims to create an annual sales report for 2022 to better understand customer behavior and drive increased sales in 2023.

---

## 🔍 Business Questions Addressed  
1. Compare sales and orders using a single chart  
2. Identify the month with the highest sales and order volume  
3. Determine whether men or women made more purchases in 2022  
4. Analyze the distribution of different order statuses  
5. List the top 5 states contributing to overall sales  
6. Explore the relationship between age and gender based on order volume  
7. Identify which sales channel contributed the most revenue  
8. Highlight the highest selling product category  

---

## 📊 Data Examination  
We analyzed whether the available data effectively addresses the business problems.

### 🔧 Data Cleaning  
- Gender column contained values like M, Male, Woman, W  
- All instances of "M" were standardized to "Men" for consistency

### 🧮 Data Processing  
```excel
Age Group = IF(E4>=50, "Senior", IF(E4>=30, "Adult", "Teenager"))  
Month     = TEXT(G2, "mmm")
```

### 📈 Data Analysis  
- Created pivot tables and dynamic pivot charts with auto-refresh  
- Applied number formatting (`00000000` → `0.00,, "M"`) to represent figures in millions  
- Top 10 states dynamically computed per month (e.g. January vs February may differ)

---

## 💡 Key Insights  
- **March** saw the highest sales and order volume  
- **Women** made more purchases than men; Vrinda Store generates higher sales from female customers  
- **Order status breakdown**:  
  - Delivered: 92%  
  - Refunded: 2%  
  - Returned: 3%  
  - Cancelled: 3%  
- **Top 5 contributing states**: Tamil Nadu, Telangana, Uttar Pradesh, Karnataka, Maharashtra  
- **Age & gender trends**:  
  - Adults (30–49) of both genders placed the most orders  
  - Among adults, **women** made more purchases than men  
- **Sales channels**:  
  - Amazon contributed the most revenue  
  - Followed by Myntra and Flipkart  

---

## 🎯 Final Conclusion  
Target women aged **30–49 years** residing in **Maharashtra**, **Karnataka**, or **Uttar Pradesh**. Focus marketing campaigns—ads, coupons, and offers—on platforms like **Amazon**, **Flipkart**, and **Myntra** to maximize conversions.
