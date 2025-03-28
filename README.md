Here's your **final README** combining both the details of your project and referencing the GitHub repository:  

---

# **Dynamic Retail Dashboard in Excel**  

## **Overview**  
This project is a **dynamic retail dashboard** built in **Excel**, using **three tables**: **Order, People, and Return**. The data is ingested from a folder, cleaned, and analyzed to extract meaningful business insights. The dashboard provides an interactive way to monitor sales, profit, and order trends across different **regions, segments, and categories**.  

## **Significance**  
Retail businesses require **efficient data visualization** to make informed decisions. This project helps in:  
- Monitoring key business **KPIs** such as **total sales, profit, quantity, number of orders, and profit margin**.  
- Identifying **profitable categories** and **underperforming products**.  
- Understanding **sales distribution** across different **regions, segments, and subcategories**.  
- Analyzing **returns and their impact on profitability**.  
- Visualizing yearly trends to plan future strategies.  

---

## **Dataset Structure**  

### **1. Order Table**  
This table contains detailed information about each order, including order specifics, customer details, product information, and financial metrics.  

| Order ID        | Returned | Order Date | Ship Date  | Ship Mode   | Customer ID | Customer Name | Segment   | City           | State         | Country        | Market | Region  | Product ID      | Category    | Sub-Category | Sales    | Quantity | Discount | Profit   | Shipping Cost | Order Priority |
|-----------------|----------|------------|------------|-------------|-------------|---------------|-----------|----------------|---------------|----------------|--------|---------|-----------------|-------------|--------------|----------|----------|----------|----------|---------------|----------------|
| CA-2012-124891  | No       | 31-07-2020 | 31-07-2020 | Same Day    | RH-19495    | Rick Hansen   | Consumer  | New York City  | New York      | United States  | US     | East    | TEC-AC-10003033 | Technology  | Accessories  | 2309.65  | 7        | 0        | 762.18   | 933.57        | Critical       |
| IN-2013-77878   | Yes      | 05-02-2021 | 07-02-2021 | Second Class| JR-16210    | Justin Ritter | Corporate | Wollongong     | New South Wales| Australia      | APAC   | Oceania | FUR-CH-10003950 | Furniture   | Chairs       | 3709.39  | 9        | 0.1      | -288.76  | 923.63        | Critical       |

### **2. People Table**  
This table associates individuals with specific regions, which can be useful for regional sales analysis.  

| Person            | Region  |
|-------------------|---------|
| Anna Andreadi    | Central |
| Chuck Magee      | South   |
| Kelly Williams   | East    |
| Matt Collister   | West    |
| Deborah Brumfield| Africa  |

### **3. Return Table**  
This table records information about returned orders, including the order ID and the market associated with the return.  

| Returned | Order ID        | Market      |
|----------|-----------------|-------------|
| Yes      | MX-2013-168137  | LATAM       |
| Yes      | US-2011-165316  | LATAM       |
| Yes      | ES-2013-1525878 | EU          |
| Yes      | CA-2013-118311  | United States|
| Yes      | ES-2011-1276768 | EU          |

---

## **Problem Statements Solved**  
The dashboard answers the following business questions:  
1. **KPIs Tracking** - Displays key performance indicators such as total sales, total profit, quantity, number of orders, and profit margin.

   <img width="626" alt="image" src="https://github.com/user-attachments/assets/86c1dbde-b4d2-40ff-b050-5f0de827b1f5" />
 
3. **Sales and Profit Analysis** - Breakdown of sales and profit patterns.
<img width="214" alt="image" src="https://github.com/user-attachments/assets/4edbcdcf-16d9-43a1-9c15-cf449b4bc79c" />

5. **Category-wise Profit** - Identifying the most and least profitable categories.
   <img width="206" alt="image" src="https://github.com/user-attachments/assets/ba39be70-3d12-48cc-a6da-4f574a33fbfe" />

7. **Segment-wise Sales Share %** - Analyzing the contribution of different customer segments to total sales.
   <img width="209" alt="image" src="https://github.com/user-attachments/assets/68f00b2d-a4af-4b2a-9388-f0a4399883e1" />

9. **Sales by Country** - Geographical distribution of sales.
    <img width="212" alt="image" src="https://github.com/user-attachments/assets/ee986d26-86fe-4e90-92f7-8876c4c024a0" />

11. **Top 5 Subcategories** - Identifying the best-performing subcategories.
    <img width="207" alt="image" src="https://github.com/user-attachments/assets/e7e3c81d-8c9e-4f01-b033-8d422be33fe5" />

13. **Bottom 5 Subcategories** - Highlighting underperforming subcategories.
    <img width="213" alt="image" src="https://github.com/user-attachments/assets/8e0e1727-0e6b-4e44-b6f8-8b79e22bdd1c" />

      
15. **Yearly Sales Trend** - Observing sales fluctuations over time.  

---
## Snapshort of dashboard
<img width="556" alt="image" src="https://github.com/user-attachments/assets/8504e661-7dbe-4a3f-9c63-907796766a11" />

## **KPI Table for Unified Analysis**  
To ensure all KPIs are analyzed together, a **KPI table** has been created:  

| KPI Name           | Description          | Symbol |
|--------------------|----------------------|--------|
| Total Sales        | Sum of Sales         | 💰     |
| Total Profit       | Sum of Profit        | 📈     |
| Total Quantity     | Sum of Quantity      | 📦     |
| Number of Orders   | Count of Order ID    | 🛒     |
| Total Profitability| Sum of Profitability | 🔍     |

This KPI table enables a unified view of critical metrics, facilitating informed decision-making and performance tracking within the retail dashboard.  

---

## **Conclusion**  
This project provides a **comprehensive sales analysis** using Excel, allowing businesses to quickly identify **strengths and weaknesses** in their sales and profitability. With **interactive features** and **dynamic filters**, the dashboard serves as a powerful tool for **data-driven decision-making** in the retail industry.  

### **GitHub Repository:**  
For detailed code, dataset, and implementation, visit:  
🔗 **[Dynamic Retail Dashboard GitHub Repository](https://github.com/harirra/Dynamic_Retail_Dashboard)**  

---

Let me know if you need any modifications! 🚀
