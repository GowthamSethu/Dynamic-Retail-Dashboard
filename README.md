# **Dynamic Retail Dashboard**  

## **Overview**  
This project involves the creation of a dynamic retail dashboard using **Microsoft Excel**, designed to visualize and analyze retail sales data across various dimensions. The dashboard connects to three main data tables—**Orders, Returns, and People**—and helps businesses gain insights into key sales performance metrics.  

The dashboard includes **Key Performance Indicators (KPIs)** that track important metrics such as:  
- **Total Sales**  
- **Total Profit**  
- **Quantity Sold**  
- **Number of Orders**  
- **Profit Margin**  

These KPIs are calculated and displayed on a centralized chart for easy comparison and visualization. The project covers multiple problem statements that help break down the data into actionable insights.  

---

## **Sample Data Tables**  

### **Orders Table**  

| Order ID        | Order Date | Ship Date | Ship Mode      | Customer Name   | Segment     | Country       | Sales   | Profit  | Quantity | Discount |
|---------------|------------|----------|--------------|----------------|------------|------------|---------|--------|----------|----------|
| CA-2012-124891 | 31-07-2020 | 31-07-2020 | Same Day      | Rick Hansen    | Consumer   | United States | 2309.65 | 762.18 | 7        | 0        |
| IN-2013-77878  | 05-02-2021 | 07-02-2021 | Second Class  | Justin Ritter  | Corporate  | Australia     | 3709.40 | -288.77 | 9        | 0.1      |
| IN-2013-71249  | 17-10-2021 | 18-10-2021 | First Class   | Craig Reiter   | Consumer   | Australia     | 5175.17 | 919.97  | 9        | 0.1      |
| ES-2013-1579342 | 28-01-2021 | 30-01-2021 | First Class   | Katherine Murray | Home Office | Germany      | 2892.51 | -96.54  | 5        | 0.1      |
| SG-2013-4320  | 05-11-2021 | 06-11-2021 | Same Day      | Rick Hansen    | Consumer   | Senegal       | 2832.96 | 311.52  | 8        | 0        |

---

### **Return Table**  

| Returned | Order ID         | Market          |
|----------|----------------|----------------|
| Yes      | MX-2013-168137  | LATAM          |
| Yes      | US-2011-165316  | LATAM          |
| Yes      | ES-2013-1525878 | EU             |
| Yes      | CA-2013-118311  | United States  |
| Yes      | ES-2011-1276768 | EU             |

---

### **People Table**  

| Person             | Region   |
|-------------------|---------|
| Anna Andreadi     | Central |
| Chuck Magee      | South   |
| Kelly Williams   | East    |
| Matt Collister   | West    |
| Deborah Brumfield | Africa  |

---

## **KPI Table**  
The **KPI table** consolidates essential performance metrics for retail analysis, enabling the dashboard to provide actionable insights by comparing important sales aspects.  

| KPI Name        | Symbol | Formula                   |
|----------------|--------|--------------------------|
| Total Sales    | 💰     | SUM(Sales)               |
| Total Profit   | 📈     | SUM(Profit)              |
| Total Quantity | 📦     | SUM(Quantity)            |
| No. of Orders  | 🛒     | COUNT(Order ID)          |
| Profitability  | 🔍     | SUM(Profit) / SUM(Sales) |

---

## **Problem Statements Solved**  
The **Dynamic Retail Dashboard** answers several business questions, providing in-depth insights into key performance areas:  

- **KPIs** – Total Sales, Total Profit, Quantity, Number of Orders, and Profit Margin.
  
  ![image](https://github.com/user-attachments/assets/611c7c39-ebd1-4ced-aeb4-ae598afa232d)

- **Sales and Profit Analysis** – Understanding overall sales and profitability.
  
  ![image](https://github.com/user-attachments/assets/8b6d30e6-53c2-451a-b463-ca4d4eca469e)

- **Category-wise Profit** – Breakdown of profit by product category.
  
  ![image](https://github.com/user-attachments/assets/16ad0c4a-b328-46a0-8719-441a9c6e1639)

- **Segment-wise Sales Share %** – Breakdown of sales by customer segment.
  
  ![image](https://github.com/user-attachments/assets/2e35501d-da23-45dc-b1b0-45151be83929)

- **Sales by Country** – Sales performance based on different countries.
  
  ![image](https://github.com/user-attachments/assets/89d26711-674b-4797-81a2-c93a6eae5c9b)

- **Top 5 Subcategories** – The best-performing subcategories based on sales.
  
  ![image](https://github.com/user-attachments/assets/07375ae5-f88f-4052-b33d-6250f589ff85)

- **Bottom 5 Subcategories** – The least-performing subcategories based on sales.
  
   ![image](https://github.com/user-attachments/assets/e7305c0c-a64a-426b-a701-1caece775fcc)

- **Yearly Sales Trend** – Understanding how sales evolve over the year.
  
   ![image](https://github.com/user-attachments/assets/a672fb79-5c7a-44f7-8afa-0bb7a0945ab6)


---

**Snapshot of the entire Dashboard**
![image](https://github.com/user-attachments/assets/91ff08b4-9bb0-4cf9-aff7-a838271fd094)


## **Conclusion**  
The **Retail Dashboard** serves as an invaluable tool for business analysts and retail managers by providing a **comprehensive view of sales performance**.  

It aggregates data from key business areas and **visualizes them dynamically**, enabling **quick decision-making**. With its ability to **calculate essential KPIs** and generate detailed analyses across different product categories, regions, and time periods, the dashboard ensures that stakeholders can make **data-driven decisions** to **optimize retail operations**.
