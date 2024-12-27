# **Supermarket Sales Analysis Dashboard 2024**

## 🖥️ **Dashboard Overview**
This project presents an interactive Power BI dashboard that analyzes supermarket sales data for January to March 2019. The dashboard provides insights into key metrics, customer behavior, and product performance. The goal is to help businesses identify sales trends, understand customer preferences, and evaluate product profitability.

## 🖼️ **Dashboard Previews**

### **Page 1: Sales Overview**
![Dashboard](https://github.com/PatrykPaul/Shop-Sales/blob/main/images/Total%20Sales.png)

### **Page 2: Client Analysis**
![Dashboard](https://github.com/PatrykPaul/Shop-Sales/blob/main/images/Clients%20Analysis.png)

### **Page 3: Product Analysis**
![Dashboard](https://github.com/PatrykPaul/Shop-Sales/blob/main/images/Product%20Analysis.png)

---

## 📊 **Dashboard Insights**
The dashboard is divided into three key sections:

### **Page 1: Sales Overview**
- **Key Metrics**: Displays total sales, total transactions, average customer rating, and average sales per transaction.
- **Top Product Lines**: Highlights the best-performing product lines.
- **Sales by Customer Type**: Compares sales contributions from Member vs. Normal customers.
- **Payment Methods**: Pie chart showing sales distribution by payment method (E-wallet, Credit Card, Cash).
- **City-Wise Sales**: Bar chart comparing total sales across cities.
- **Sales Trends Over Time**: Line chart illustrating daily sales trends.

### **Page 2: Client Analysis**
- **Sales Trends by Gender**: Line chart showing sales trends segmented by gender.
- **Average Basket Analysis**: Bar chart analyzing average basket value by gender and payment method.
- **Sales by Customer Type and Gender**: Stacked bar chart comparing sales between Member and Normal customers by gender.
- **Gender-Wise Sales Distribution**: Pie chart showing the percentage of sales by male and female customers.

### **Page 3: Product Analysis**
- **Sales by Product Line Over Time**: Line chart analyzing sales trends for each product line.
- **Sales vs. Quantity by Product Line**: Scatterplot exploring the relationship between quantity sold and total sales by product line.
- **Product Line Performance**: Bubble chart displaying total quantity sold, gross income, and total sales for each product line.
- **Gross Margin by Product Line**: Donut chart highlighting gross margin percentages for each product line.

---

## 📋 **Tools and Techniques Used**

### **Power BI Features:**
1. **Data Cleaning**:
   - Handled null values and inconsistencies in the dataset.
   - Standardized columns such as dates and numeric values.
2. **Data Modeling**:
   - Established relationships between key columns (e.g., Product Line, Customer Type, City).
3. **Custom Measures**:
   - Created DAX measures for:
     - Total Sales
     - Average Basket Value
     - Gross Margin
     - Average Sales Per Transaction
4. **Interactive Features**:
   - Added slicers for filtering by date, payment method, city, and gender.
   - Enabled drill-through options for detailed analysis.

### **Dataset Preparation**:
- **Source**: The dataset includes sales transactions for a fictional supermarket chain from January to March 2019.
- **Key Columns**:
  - Product Line
  - Sales
  - Gross Income
  - Quantity
  - Customer Type
  - Payment Method
  - City
- **Data Transformation**:
  - Verified data integrity and corrected duplicates.
  - Computed new columns and measures for analysis.

---

## 🔍 **Filters and Features**
- **Date Range**: Allows users to filter the analysis for specific periods.
- **Payment Method**: Filters data by payment method (E-wallet, Credit Card, Cash).
- **City**: Filters sales by geographic region.
- **Gender and Customer Type**: Provides insights into customer demographics and membership status.

**Preview of Filters Panel**:
![Filters](https://github.com/PatrykPaul/Shop-Sales/blob/main/images/filters_1.png)

---

## 📖 **How to Use the Dashboard**
1. **Download and Open**:
   - Download the `.pbix` file from this repository.
   - Open it in Power BI Desktop.
2. **Explore Insights**:
   - Navigate through the three pages of the dashboard to analyze sales data, customer trends, and product performance.
   - Use interactive slicers to filter data dynamically and gain focused insights.
3. **Business Applications**:
   - Identify top-performing product lines and cities.
   - Understand customer purchasing behavior by gender, membership, and payment method.
   - Track sales trends to make informed business decisions.

---


## 🚀 **Future Enhancements**
- Integrate data from additional months or years to identify long-term trends.
- Add advanced predictive analytics using machine learning to forecast future sales.
- Include profitability analysis for individual products.

---
