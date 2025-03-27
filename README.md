# 🍃 Global Skincare and Beauty E-commerce Dashboard

+ 📊 **View the Dashboard directly:** [Power BI](https://app.powerbi.com/view?r=eyJrIjoiNjk5NmE2MjMtNjI2Yi00MDQ4LTllMjUtMDg3YjFmOGZlNGIzIiwidCI6ImNiNDg0NDZlLTkwZTYtNGJmMS04MjViLTQwZTQ4ZmNjOWZmNiJ9) 
+ 📊 **View the detailed report:** [PDF](https://github.com/ngthuylinh3003/Beauty_Ecommerce_Dashboard/blob/050e0e29642ee94268f9c692f2169277bac516d5/Beauty%20Ecommerce%20final%20.pdf)

## 📌 Objective 
The skincare and beauty e-commerce industry is rapidly growing so this Project can help the company to aim:  
- **Analyze key financial metrics** (Sales, Profitability, Discount Strategy)  
- **Track sales and profit growth** (target: at least **20% YoY increase**)  
- **Understand customer behavior & market trends** (2020-2023)  
- **Evaluate the impact of discount strategies** and give some recommendations for the company

---

## 📂 Data Source   
The dataset contains sales information from a [Global skincare & beauty e-commerce](https://docs.google.com/spreadsheets/d/1QBbx3X3zIicPMWaMCCHvSfdFx7cLqJruMQX4z-f0PAM/edit?usp=sharing) and includes:  
- **Financial Metrics:** Sales, Quantity, Profit, Discount
- **Customer & Market Factors:** Customer ID, Country, Product, Category, etc 
- Source: FP20 Analytics Data Challenges Group - Federico Pastor  (Linkedin)

---

## ⚡ Approach

### Full Power BI Workflow  

### **📌 Data Processing & Preparation**  
- **Data Cleaning:**  
  - Removed unnecessary columns for analyzing (e.g., Country latitude & longitude)  
  - Checked for NULL values and corrected data types
- **Created a Date Dimension Table (DIM_Table)** for time-based analysis  

### **📌 Measure Calculations**  
Before analysis, I created **measures** to calculate the metrics and track growth or performance, for example:  
- **Total Sales, Total Profit, Total Quantity**  
- **Sales Growth % (YoY, MoM), Profit Growth %, Quantity Growth %**  
- **Profit Margin, Discount Rate, Average Order Value (AOV)**  

### **📌 Dashboard Structure (4 Pages)**  
1. Page 1: **Overview**:  Sales, Profit, and Quantity summary by month/year & region  
2. Page 2: **Products & Market**: Best-selling products & market trends  
3. Page 3: **Customers & Location**: Sales & Profit by customer and country 
4. Page 4: **Discount Strategy**: The effectiveness of discount strategy on sales and profit (by customer and by time)

### **📌 Data Visualization**  
- **Cards & Bar Charts**: Business financial metrics & growth over time  
- **Maps**: Sales distribution by country & region
- **Pie Charts**: Contribution % of Category, Market, Customer Segment 
- **Heatmaps**: Peak sales by day of the week/month
- **Matrix Table**: Detailed breakdown of metrics 
- **Scatter Plot**: Correlation between Discount Rate and Profit Margin

--- 

## 📊 Results 

### **📌 Sales & Profitability Trends**  
- Sales tend to be **higher** in the **later month** of the year compared to the earlier months (except July)  
- **Yearly Sales & Quantity exceeded 20% growth target**, but **Profit** missed the target (-12.2%) in 2023

### **📌 Product & Market Performance**  
- **Body care** has the highest revenue, with **Herbal Essences** leading sales  
- **Asia-Pacific** is the dominant market, while **Africa** has the lowest sales

### **📌 Customer & Segment Insights**  
- **United States** has the highest sales & profit
- **Corporate segment** contributes **50%+ of total profit** 

### **📌 Discount Strategy Analysis**  
#### **The question of the company: "Did we have a good discount strategy in the last few years?"**  
1. **Customer-Level Analysis:**  
   - Some top customers **with high sales still have negative profit and profit margins** (?)  
   - Suggests that **deep discounts may be negatively impacting profitability**
   -> **A threshold should be identified** to **ensure discounts boost sales without eroding profit** (0-20%)
   
2. **Time-Based Analysis:**  
   - **2020-2022:** Sales and Profit Margin After Discount remained stable 
   - **2023:** While Sales increased, Profit Margin After Discount dropped significantly, indicating **an issue with discounting strategy**  

3. **Correlation Between Discount Rate & Profit Margin:**  
     - The **Scatter Plot** shows a **negative correlation**: Higher discounts (20-30%) **lead to significant profit drops**  
     - However, some customers with discount rates below 20% still have **varying profit margins**, suggesting other influencing factors  

#### **📢 Personal recommendations for Discount Strategy**  
+ Set **discount thresholds carefully**, especially for customers with high sales
+ **Identify the optimal discount range** where profit remains positive 

---  

🔎 **This analysis reflects personal insights—open to feedback & discussion!** 🚀
