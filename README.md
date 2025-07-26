# DATA CLEANING

# Ecommerce-Data-Analysis

# 🛒 Electronics Ecommerce Data Cleaning and EDA Analysis — End-to-End Data Analytics Project

## 📌 Project Overview

This project showcases data analysis using U.S. electronic sales from an ecommerce sample dataset. The process includes data cleaning with Excel and Python, exploratory data analysis (EDA), and ultimately building an interactive dashboard in Tableau to visualize sales(regional, state, and city), product sales trends (regional state, city),  customer behavior ( order times based on region, state and city).

---

## 📂 Dataset Overview

The dataset contains **11,554** records and **9** columns, with  sales data such as:

- 'Order ID','Product','Order Total','Shipping','Order Date','Order Time','City','State','Region'


---

## 🔧 Phase 1: Data Cleaning (Python - Pandas and excel)

| Step                    | Description                                                                                         |
|-------------------------|-----------------------------------------------------------------------------------------------------|
| ✅ Missing Values        | 497 missing 'Order Id' values, which I dropped making total entries 11,554                          |
| ✅ Duplicate Removal     | Removed repeated `order_id`s                                                                        |
| ✅ Type Conversion       | Converted 'Order ID' to `int` ,                                                                     |
| ✅ Checked Unique Values | All Order ID's are unique, 19 products, $9.99 standard shipping, 3 regions, 8 states, and 9 cities. |

Cleaned data exported to `ElectronicsSales.csv` for Tableau.

---

## 📊 Phase 2: Exploratory Data Analysis (EDA)

Conducted using **Seaborn**, **Matplotlib**, and **Numpy**:

## 🕒 Time Trends
- Sales trend shows that beginning of Q2(April) is showing that the 5 key products in both the lowest and highest regions
are the same 'Macbook Pro Laptop, Iphone, ThinkPad Laptop, 34in Ultrawide Monitor.
- Revenue trend shows that the  beginning of Q2(April) is showing that the leading markets are the California segment 
  of the West region. 


## 👤 Product Insights
- 
- The top 5 highest sales products are: Macbook Pro Laptop, Iphone, ThinkPad Laptop, Google Phone, 34in Ultrawide
  Monitor.
- Macbook pro segment dominates overall sales volume with $472,600 in sales.


## 🌍 Geographic Trends
- Top 4 highest sales Cities are San Fransisco, Los Angeles, and New York , and Boston (Key Markets)
- Bottom 4 lowest sales Cities are Austin, Portland, Dallas, and Atlanta. ( Majority South Region)
- The West region has the highest sales and their key state is California.
- Maine, Oregon and Georgia are the lowest sales States, however the lowest performing region is the South.


## 📈 Phase 3: Tableau Dashboard 

Incomplete

## 📦 Tools Used

- **Python**: Pandas, Seaborn, Numpy, Matplotlib
- **Tableau**:  INCOMPLETE
- **Jupyter Notebook**: Cleaning, EDA 
- **Excel/CSV**: Data export for Tableau

---

## 📁 Project Structure

```
├── Electronic Ecommerce Data Cleaning and EDA.ipynb       # Python notebook for cleaning + EDA
├── ElectronicSales.csv                            # Exported dataset for Tableau
├── README.md                                              # Project documentation
```

---

## ✅ Key Takeaways

-  Sales trend shows that beginning of Q2(April) is showing that the 5 key products in both the lowest and highest regions
are the same 'Macbook Pro Laptop, Iphone, ThinkPad Laptop, 34in Ultrawide Monitor.
- - Top 4 highest sales Cities are San Fransisco, Los Angeles, and New York , and Boston (Key Markets)
- Bottom 4 lowest sales Cities are Austin, Portland, Dallas, and Atlanta. ( Majority South Region)

---

## 📌 Next Steps (Optional Enhancements)
- Tableau interactive dashboard.
- Customer segmentation ( modeling correlation between consumer earning capacity and spending habits)
- Behavioural Analytics ( Order time and product choices based on Regions, Cities, and States.
- Real-time dashboard deployment via Power BI Service

---

## 🌐 Author

**Natasha Tshili**  
Data Analysis and Vizualization 
Graduate of the DTP Program- sponsored by IHS Towers, ICT Chamber and Rwanda Ministry of ICT and Innovation
|Python, Excel, Tableau  
tshili.natasha@gmail.com

---