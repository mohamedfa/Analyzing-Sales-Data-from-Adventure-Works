# Adventure Works Sales Data Analysis using Power BI
![Screenshot 2024-08-24 212454](https://github.com/user-attachments/assets/9d6498e3-4fa8-4af0-a475-217f5e835d7a)

This repository contains the Power BI dashboard used to analyze sales data from the Adventure Works dataset. The dashboard provides key insights into the sales performance, product trends, order distribution, and much more. The visualizations help stakeholders make informed business decisions based on historical data, You can check the dashboard from [here](https://app.powerbi.com/view?r=eyJrIjoiOTRhNjJkYWYtNDk5ZC00OTQ0LWJjNzItNjM1ZTMzOTA3ZDA3IiwidCI6IjhmY2Y0Y2Q5LTJmZTQtNDU3MS04NDMxLWIxN2MzZjI5ZWZiMyJ9).

## Key Performance Indicators (KPIs)
![image](https://github.com/user-attachments/assets/49c5ba04-a4a6-47c5-b47f-1f9b52015a56)

The dashboard starts with a set of key performance indicators (KPIs) that summarize the overall sales data:

- **Number of Customers:** 294
- **Number of Orders:** 1,465
- **Number of Order Details (Items Sold):** 24,000
- **Total Sales Amount:** $30,000,000
- **Total Tax:** $2,931,097
- **Total Freight Costs:** $915,968
- **Total Price (including taxes and freight):** $34,000,000

These KPIs provide a quick overview of the sales performance and help in identifying key metrics for the business.

## Dashboard Visualizations

### 1. **Number of Orders by Date (Line Chart / Time Series)**
![image](https://github.com/user-attachments/assets/6019d619-303c-42af-bb3d-74455430adc2)

This line chart tracks the number of orders over time, highlighting trends across different months.

- **Key Insight:** March 2014 saw the highest number of orders, with a total of **141 orders**. This could indicate a seasonal spike or a promotional period that drove increased sales.

### 2. **Orders and Total Amount by Territory (Line and Stacked Column Chart)**
![image](https://github.com/user-attachments/assets/3bcfdff7-9b28-47a5-b442-1bffc3de4b93)

This visualization consists of two parts:
- **Line Chart:** Represents the total sales amount over time.
- **Stacked Column Chart:** Displays the number of orders over time, broken down by territory.

- **Key Insight:** Canada has the highest number of orders and sales. Specifically, Canada recorded **448 orders** and a **total amount of $10,591,830**. This suggests that Canada is a major contributor to sales.

### 3. **Top 5 Products Ordered (Stacked Bar Chart)**
![image](https://github.com/user-attachments/assets/9a96a855-3ccd-497c-a592-40e5652e68a6)

This stacked bar chart showcases the top 5 products ordered based on the frequency of their sales.

- **Key Insight:**
  - The **AWC Logo Cap** is the most ordered product, with **428 orders**.
  - The **Long-Sleeve Logo Jersey** comes in second place with **425 orders**.
  
This highlights the most popular items in the Adventure Works product lineup.

### 4. **Number of Orders by Status (Pie Chart)**
![image](https://github.com/user-attachments/assets/bbf5e418-95a9-4a82-9b06-0ad40a4674e8)

This pie chart shows the distribution of orders based on their status.

- **Key Insight:**
  - **Approved Orders** make up **27%** of all orders.
  - **In Process Orders** account for **26%**.
  - **Shipped Orders** represent **25%** of the total.

The remaining 22% of orders are in other statuses, including canceled or on hold. This provides a snapshot of the order lifecycle.

### 5. **Number of Order Details and Number of Orders by Product Category (Treemap)**
![image](https://github.com/user-attachments/assets/761d393f-986d-4080-953a-beb132df85ad)

This treemap visualizes the breakdown of order details (items) and the number of orders by product category.

- **Key Insight:**
  - The **Bikes** category is the highest, with over **9,000 items** sold.
  - The **Components** category follows with around **7,000 items**.
  - The **Clothing** category is third with about **5,000 items**.

This chart helps identify which product categories are driving the most orders and sales.

## Data Sources
The data used in this analysis is derived from the **Adventure Works** dataset, a fictitious company that sells bicycles, outdoor products, and accessories, You can check the data [here](https://github.com/mohamedfa/Analyzing-Sales-Data-from-Adventure-Works/blob/main/Sales.xlsx).

## Tools Used
- **Power BI**: For creating interactive visualizations and reports.
- **Adventure Works Dataset**: A publicly available database used to simulate business scenarios.

## Conclusion
This Power BI dashboard offers a comprehensive analysis of Adventure Works sales data, allowing users to explore KPIs, trends, product performance, and regional sales. By examining these visualizations, business analysts and decision-makers can derive actionable insights to improve business operations and drive growth.
