# ☕SQL Café Sales Analysis

## 📂 Data Source
- [view the dataset Cafe_sales.csv](data/Cafe_sales.csv)

## About Dataset
  
  This dataset contains around **3,530 café sales transactions** recorded in a cafe. It gives info about both customer and transaction details like time of purchase, method of payment, beverage type, and amount spent. 


## 📊Project overview
  
  A complete SQL project analyzing 3,530 café sales transactions, including customer behavior, sales patterns, and revenue insights.
  
  This project explores a real‑world coffee shop dataset and answers key business questions using SQL:

- What time of day generates the most revenue

- Which coffee types are most profitable

- How payment methods affect sales

- Which days and months perform best

- Hourly, daily, and monthly sales trends


## 📁Data description

| Column Name | Description                                           |
|-------------|-------------------------------------------------------|
| Hour of the day | The hour when the purchase occurred               |
| Cash type | Payment method used                                     |
| Price | The amount of money spent on the purchase                   |
| Coffee name | The type of coffee or drink purchased                 |
| Time of Day | Morning, Afternoon, Evening, etc                      |
| Weekday | The day of the week on which the transaction occurred     |
| Month name | The month when the transaction was recorded            |
| Sorting of day or month | Weekdays and months sorting               |
| Date | Date of the transaction                                      |
| Time | Time of purchase                                             |
| Full timestamps | Date & time of purchase                           |


## 🧹 Data Cleaning Steps

*Cleaning included:*

- Fixing inconsistent text formatting

- Converting dates to YYYY-MM-DD

- Converting numeric fields

- Removing duplicates

- Creating day_name from weekday numbers

- Adding derived fields like hour and full timestamp

  **[view cleaning script](Cafe_sales_data_cleaning)**


## 📈 Key Performance Indicators (KPIs)

1. Total Revenue
2. Revenue by Coffee Type
3. Revenue by Day of Week
4. Peak Sales Hour

   **[view KPIs script](Cafe_sales_KPI)**

## 📌 Insights Summary

- Peak revenue occurs during morning hours

- Latte and Cappuccino are top sellers

- Friday shows the highest sales volume

- Card payments dominate over cash

- Revenue increases significantly during mid‑month


## 🛠️ Tools Used

- SQLiteStudio for SQL queries

- GitHub for version control

- Markdown for documentation
