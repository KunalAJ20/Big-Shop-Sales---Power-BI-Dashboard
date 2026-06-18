# Big-Shop-Sales---Power-BI-Dashboard

<img width="1024" height="583" alt="image" src="https://github.com/user-attachments/assets/ecd467a0-a2d3-4bdb-b8fa-0355912917af" />


### 1. Project Overview

This project involves building an interactive **Power BI Sales Performance Dashboard** using historical transaction data from Big_Shop_Sales.xlsx. The primary objective of this dashboard is to provide retail stakeholders with actionable insights into inventory movement, logistics costs, and profitability margins.
Because the raw data only contained foundational metrics (unit cost and items sold), advanced **DAX formulas** were implemented to calculate **Total Revenue**, **Shipping Costs**, and net profit **Margins**. The final dashboard enables dynamic cross-filtering by region, product type, salesperson, and customer to help optimize business supply chains and sales strategies.

### 2. Visuals Used & Structure

 * **Executive KPI Cards:** 
   * Sum of Total Items Sold
   * Sum of Shipping Costs
   * Total Calculated Revenue
   * Total Net Margin
    
 * **Slicers:** Positioned as user-friendly **Drop-down**
   
 * **Distribution & Breakdown Charts (Pie & Donut Charts):**

   * *Count of Product by Region* & *Count of Region by Product*
   * *Count of Salesperson by Customer* & *Count of Salesperson by Product*
   * *Sum of Shipping Cost by Region*
     
 * **Customer Analysis (Bar/Column Chart):** Evaluates total order volumes (*Sum of No. Items*) distributed by client portfolios.
 

  * **Clustered Column Chart:** Compares *Item Cost*, *Margin*, and *Shipping Cost* variations aggregated by **Year** and **Month**.
    
   * **Line and Clustered Column Chart:** Maps *Total Revenue* and *Shipping Cost* as columns alongside *Total Margin* as a trend line to measure individual **Salesperson** performance.
    
   * **Trend Chart:** Displays the velocity of inventory volume (*Sum of No. Items*) over chronological time frames.
    
### 3. Key Results & Insights (Data-Backed)

 * **Overall Scale:** The business generated **$2,411,789.32** in total revenue across **8,566 items sold**, yielding a net profit margin of **$2,291,199.85** , after accounting for **$120,589.47** in logistics/shipping overheads.
   
 * **Top Regional Drivers:** Sales are highly concentrated in the **South West** ($800,036.49) and **North East** ($799,855.54) regions,which combined represent roughly **66.3%** of the entire company's sales revenue.
   
 * **Salesforce Leaders:** Out of the sales team, **Varun Sharma** ($312,567.43) and **Ajeet Roy** ($303,764.45), emerged as the top revenue-producing assets driving the highest margin return on the performance line charts.
