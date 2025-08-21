# 📊 Unicorn Dataset Analysis (Spreadsheets)

This folder contains the **`Unicorn dataset analysis.xlsx`** file, which was used for the second part of the project.

**The Google Sheets file is also available at this link:** [Unicorn Dataset Analysis](https://docs.google.com/spreadsheets/d/1DyJA0PwklEnJrPSyfb_p3dIDImqxOoqytvLtboRwa8Y/edit?usp=sharing)

## 🎯 Project Goal

The primary goal was to answer specific questions by using Google Spreadsheets as a data analysis tool. This step served as a foundation for deeper, unguided data research, providing initial insights into the dataset.

## 📋 Questions Answered

1.  What was the city with the highest sales?
2.  What is the average discount given for all orders?
3.  What is the most popular product among customers in the "Consumer" segment?
4.  What is the total profit made for the "Office Supplies" category?
5.  Who is the customer who has made the most purchases?
6.  What state made the most profit?
7.  How many orders were shipped via "Standard Class" ship mode?
8.  Which region had the highest sales in the month of June?
9.  Calculate the price per unit of each product (before discounts), and put it in a separate column. What's the most expensive product?
10. Create a pivot table that shows the total sales for each manufacturer and category combination. In the "Technology" category, which manufacturer had the second highest sales?
11. What is the subcategory of “Xerox 1887”?
12. Create a new column that calculates the number of days between the order date and the ship date for each order. Create a conditional formatting “color scale” for this column, from greenish to reddish.
13. What is the number of days between order date and shipping date for order id - “CA-2015-100363”?
14. What is the shipping price for order id “CA-2015-100678”?
15. Create a new column that concatenates the customer name, city, and state into a single string for each order.
16. Use the IFS function to create a new column that categorizes each order as "High," "Low," or "Loss" based on profit and sales criteria.
    * "High" is considered as:
        * If sales are above 200 and profit is above 20
        * If profit is above 40.
    * For other cases:
        * If the profit is equal or below 0 this is categorized as “Loss”
        * Any other case this is categorized as "Low"
    * Use conditional formatting to color the columns with the values “High” in green, the value “Low” in yellow and the value “Loss” in red.**
    * How many “Loss” cases do you have?
17. In a new sheet, create a dropdown of category and product which returns the price for a unit (which you previously solved in exercise 9.)

## 🛠️ Methodology

The analysis was performed using various spreadsheet functions and techniques, including:
* **Data Manipulation:** Creating new columns for calculations (e.g., price per unit, days between dates) and concatenating strings.
* **Conditional Formatting:** Applying rules to visually represent data insights (e.g., color scales for shipping time, highlighting profit categories).
* **Pivot Tables:** Summarizing and aggregating data to answer specific business questions.
* **Logical Functions:** Using `IFS` and other logical functions to categorize orders based on profit and sales criteria.
* **Data Validation:** Creating dropdown lists for interactive analysis.
