# 🍽️ Restaurant Sales Dashboard (Zomato-Style) - Power BI Project

This Power BI project replicates the kind of dashboard a restaurant brand might use to analyze order and sales data received from platforms like Zomato. It was created using synthetic data that includes key restaurant metrics such as sales, item performance, delivery types, and customer feedback.

---

## 📁 Dataset

The dataset was synthetically generated and includes the following key fields:

- `Order_ID`: Unique ID for each order
- `Order_Date`, `Order_Time`, `Order_DateTime`: Timestamp details
- `Item_ID`, `Item_Name`, `Item_Price`, `Item_Cost`
- `Area`: Area from where the order was placed
- `Order_Type`: Delivery, Dine-in, or Takeaway
- `Rating`: Customer rating (1 to 5)
- `Delivery_Time(min)`: Time taken to deliver the order

---

## 📌 Objective

As a Business Analyst hired by a restaurant chain, the goal was to build a dashboard that helps answer the following questions:

- What is the total sales over a period?
- Which item is the most frequently ordered?
- What is the average order value?
- What is the order frequency across different hours?
- What percentage of orders are delivery vs dine-in vs takeaway?
- How does each area perform in terms of revenue?
- What are the trends in monthly sales and order volume?
- How does customer feedback (ratings) correlate with performance?

---

## 📈 Key Metrics

- **Total Sales**
- **Avg Order Value**
- **Avg Rating**
- **Avg Preparation Time**
- **Order Frequency**
- **Most Ordered Item**
- **Sales by Month**
- **Sales by Area**
- **Order % by Type**
- **Order Frequency by Time**

---

## 🔗 Data Model

![Data Model](Screenshot%202025-05-18%20202935.png)

The model includes:

- `Orders` fact table
- `Items` dimension
- `Dim Date` dimension for time intelligence
- `_measures` for DAX measures like KPIs and dynamic titles

## Dashboard

![Dashboard](dashboard.png)
