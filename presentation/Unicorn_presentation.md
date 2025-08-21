### **Tableau Work & Visualizations**

This section describes the dashboards and visualizations created in Tableau to present the key findings of the project. The Tableau Story is structured to guide the viewer through the analysis and recommendations step-by-step.

#### **Dashboard 1. Unicorn Overview**

![Unicorn Overview Dashboard](screenshots/1_Unicorn_Overview.png)

This dashboard provides a high-level overview of the company's financial performance. It showcases the positive growth trends over four years, with both sales and profits increasing annually.

* **Key Metrics:** The dashboard displays key performance indicators (KPIs) such as total sales, total profit, and the average annual profitability of **12.6%**.
* **Trends:** It reveals a clear seasonal pattern in sales and profit, with volumes peaking towards the end of the year and declining at the beginning. It also highlights a critical issue: a decrease in profit during periods of high sales in November, which could be linked to the start of the discount season in the US.
* **Interactivity:** Users can select a specific year to view KPIs, as well as a year for comparing sales and profit volumes with the previous period.

#### **Dashboard 2. Sales Geography**

![Sales Geography Dashboard](screenshots/2_Sales_Geography.png)

This dashboard visualizes the geographical distribution of sales and profitability across the United States.

* **Profitability Map:** Sales are shown in numbers, while states with negative profitability are highlighted in red. The analysis identified **10 states** that cause losses despite high sales volumes, with Texas experiencing the highest losses.
* **Interactivity:** On the geography dashboard, you can also select one or multiple years to display the data.

#### **Dashboard 3. Discount Policy Analysis**

![Discount Policy Analysis Dashboard](screenshots/3_Discount_Policy_Analysis.png)

This dashboard dives deep into the root cause of the profitability issues: the discount policy.

* **Impact of Discounts:** **18% of all orders** were sold with discounts greater than 20%, resulting in losses of approximately **$140K** over four years. Out of 17 product subcategories, only two are profitable when offering discounts greater than 20%.
* **Unprofitable Subcategories:** The dashboard highlights specific subcategories, such as **Tables, Supplies, and Storage**, which are unprofitable regardless of the discount percentage applied.
* **Recommendation:** The analysis recommends revisiting the discount policy and completely eliminating discounts exceeding 20%, and discontinuing discounts for the unprofitable subcategories.
* **Interactivity:** You can select categories and years to display on the dashboard.

#### **Dashboard 4. Client Analysis**

![Client Analysis Dashboard](screenshots/4_Clients_Analysis.png)

This dashboard focuses on customer behavior and growth opportunities.

* **Customer Loyalty:** It shows that while the number of active loyal customers is significant and shows positive growth, the number of new customers is steadily declining.
* **New Customer Growth:** The analysis highlights a critical issue: in 2018, only **11 new customers** were acquired.

#### **Dashboard 5. Profit Forecast Compared with 2018**

![Profit Forecast Dashboard](screenshots/5_Profit_Forecast.png)

This interactive dashboard presents a predictive analysis to demonstrate the potential for growth.

* **Forecast Model:** The forecast is based on the 2018 price and sales volume data, considering the increase in the number of new customers and changes in the discount policy.
* **Key Forecasts:**
    * An increase of **100 customers** is projected to grow annual profit by **$13,412** (a **14.4% increase** compared to 2018).
    * Eliminating discounts above 20% would generate an additional profit of over **$240K**, more than doubling the company's profitability by **2.5 times**.
* **Interactivity:** The dashboard allows users to adjust the number of new customers and the maximum discount percentage using the parameters, and you can also change the state for analysis through the filter.

#### **Dashboard 6. Profit Forecast for Unprofitable States**

![Profit Forecast for Unprofitable States Dashboard](screenshots/6_Profit_Forecast_Unprofitable_States.png)

This final dashboard provides a targeted forecast specifically for the unprofitable states.

* **Risk Assessment:** It shows that, under the current discount policy, an additional number of customers would lead to even greater losses in these states.
* **Recommendation:** The analysis emphasizes the need to **revise the discount policy first** before focusing on expanding the customer base in these regions.
* **Interactivity:** Users can adjust parameters for new customers and maximum discount percentage, and also filter by state.
