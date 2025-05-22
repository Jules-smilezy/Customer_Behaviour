# 🏪 Online Store Sales Analysis

This project focuses on analyzing sales data from an online store to uncover insights on sales trends, product performance, and customer behavior. The analysis was conducted using Pandas, Matplotlib, Seaborn and Jupyter Notebook.

## 📊 Analysis Roadmap

### 1. Total Sales Analysis

Sales were analyzed across multiple dimensions to identify patterns:

- **By Country**:  
  *The United Kingdom recorded the highest sales and most frequent orders.*

- **By Month**:  
  *November showed the highest total sales.*

- **By Week**:  
  *Week 49 recorded the highest sales.*

- **By Day of the Week**:  
  *Thursdays exhibited the highest sales activity.*

- **By Hour of the Day**:  
  *The most sales occurred between 9 AM and 3 PM.*

---

### 🔍2. Top 10 Products Analysis

The top products were identified using three key metrics:

- **Frequently Ordered Products**
- **Most Sold Products (by Total Quantity)**
- **Most Sold Products (by Total Sales Revenue)**

---

### 3. Unit Price Group Analysis

Products were categorized based on their unit price into:

- `Low_Price_Group`
- `Average_Price_Group`
- `High_Price_Group`

#### Insights from each price group:

| Price Group       | Top 10 Frequently Ordered | Top 10 Most Sold (Quantity) | Top 10 Most Sold (Sales) |
|-------------------|---------------------------|-----------------------------|--------------------------|
| **Low Price**     | 1 Products                | 5 Products                  | 1 Product                |
| **Average Price** | 5 Products                | 5 Products                  | 5 Products               |
| **High Price**    | 4 Products                | 0 Products                  | 4 Products               |

---

### 4. Customer Loyalty Analysis

Customer loyalty was assessed based on invoice frequency:

- **Loyal Customers**:  
  *Customers with more than one invoice record.*

- **Lapsed Customers**:  
  *Customers who made a purchase only once.*

---

### 💹5. RFM Analysis

The **Recency**, **Frequency**, and **Monetary (RFM)** metrics were analyzed to segment and better understand customer value.

---

### 🛒6. Average Basket Size

The average basket size (mean number of items per order) was calculated to gauge typical purchasing behavior.

---

## ⚙️ Tools Used

- **Pandas**: Data cleaning, aggregation, and analysis  
- **Matplotlib & Seaborn**: Visualization

## 📂 Project Structure

| Phase                               | Description |
|-------------------------------------|-------------|
| **Data Loading and Cleaning**       | Importing and preparing the dataset for analysis. |
| **Data Analysis and EDA**           | Exploratory analysis to uncover insights. <br><br>• **Top Performing Products** <br>• **Top Customers by**: <br>&nbsp;&nbsp;&nbsp;– Revenue <br>&nbsp;&nbsp;&nbsp;– Country <br>&nbsp;&nbsp;&nbsp;– Frequency of Purchase <br>&nbsp;&nbsp;&nbsp;– Recency <br>• **Average Basket Size** (Average items purchased per transaction) <br>• **Summary of Insights** — Key findings and business recommendations. |
| **Trend Analysis**                  | Identifying patterns and trends over time to inform decision-making. |
| **Summary**                         | Final consolidation of all analytical results and actionable insights. |
