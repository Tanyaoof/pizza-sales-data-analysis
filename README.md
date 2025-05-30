# 🍕 Pizza Sales Data Analysis

> A data-driven deep dive into pizza sales patterns, customer behavior, and actionable business insights.

---

## 🧠 Background and Overview

This project explores a rich dataset of pizza orders to uncover trends and recommend improvements in sales strategy. Using SQL queries, Excel dashboards, and visualization techniques, we transform raw data into real business value.

---

## 🗂️ Data Structure Overview

The dataset is made up of the following interconnected tables:

| Table Name      | Key Columns                                   |
|-----------------|-----------------------------------------------|
| `orders`        | `order_id`, `order_date`, `order_time`                    |
| `order_details` | `order_details_id`,`order_id`, `pizza_id`, `quantity`            |
| `pizzas`        | `pizza_id`, `pizza_type_id`, `size`, `price` |
| `pizza_types`   | `pizza_type_id`, `name`, `category`, `ingredients`         |

---

## 📊 Executive Summary

- 🍕 **Top 5 pizzas by revenue** generate the majority of earnings.
- 🕐 Orders peak between **12 PM – 2 PM** and **6 PM – 8 PM**.
- 📏 Medium and Large pizzas dominate in quantity.
- 📈 Opportunities exist for strategic upselling and time-targeted promotions.

---

## 🔎 Insights and Deep Dive

### 🥇 Top 15 Highest Revenue-Generating Pizzas
![Top 15 Revenue Pizzas](images/top_15_revenue.png)

> These pizzas represent the highest-performing items in terms of earnings.

---

### 📦 Top 15 Most Ordered Pizzas by Quantity
![Top 15 Ordered Pizzas](images/top_15_orders.png)

> High volume doesn’t always mean high profit. Some frequently ordered pizzas are low-margin.

---

### ⏰ Hourly Distribution of Orders
![Hourly Orders](images/hourly_orders.png)

> Key insights into when customers are most active. Useful for staffing and time-bound offers.

---

## 💡 Recommendations

✅ **Boost Best-Sellers**  
Promote top revenue-generating pizzas through homepage features and bundle deals.

🕒 **Off-Peak Promotions**  
Introduce discounts during low-volume hours to improve kitchen utilization.

📦 **Smart Inventory**  
Match ingredient procurement with demand to reduce cost and waste.

📏 **Size-Based Incentives**  
Offer minimal upsell pricing to shift customers to larger sizes and improve order value.

🌱 **Menu Innovation**  
Test new variants of best-selling pizzas as limited-time offers to maintain engagement.

---

## 📎 Next Steps

- 📈 Build interactive dashboards with Excel or Power BI.
- ⚙️ Automate reporting pipelines.
- 📣 Collaborate with marketing to turn insights into campaigns.

---

Made with ❤️ by a pizza enthusiast & data analyst.

