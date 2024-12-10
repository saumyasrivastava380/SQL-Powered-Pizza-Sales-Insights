# SQL-Powered-Pizza-Sales-Insights
## 📄 Project Overview  
This project showcases how SQL can be leveraged to analyze and extract actionable insights from a simulated pizza sales dataset. The analysis includes revenue trends, top-selling items, and customer ordering patterns.

---

## 🛠️ Tools Used  
- **SQL:** For querying and analyzing the dataset.  
- **Dataset:** Simulated pizza sales data mimicking real-world scenarios.

---

## 🔍 Key Insights  
1. Total number of orders placed.  
2. Total revenue generated from pizza sales.  
3. Highest-priced pizza identified.  
4. Most common pizza size ordered.  
5. Top 5 most ordered pizzas by quantity.  

### Intermediate Analysis:  
- Total quantity of pizzas by category.  
- Distribution of orders by hour of the day.  
- Average number of pizzas ordered per day.  

### Advanced Analysis:  
- Cumulative revenue trends over time.  
- Revenue contribution of each pizza type.  
- Top 3 pizzas by revenue per category.

---

## 📊 Sample Queries  
Below are some key SQL queries used in the analysis:

### Calculate Total Revenue:  
```sql
SELECT SUM(quantity * price) AS total_revenue
FROM orders
JOIN order_details ON orders.order_id = order_details.order_id
JOIN pizzas ON order_details.pizza_id = pizzas.pizza_id;
🤝 Connect with Me
Feel free to explore, fork, or contribute!

LinkedIn: www.linkedin.com/in/saumya-srivastava380
Email: saumya3805@gmail.com
⭐ If you find this project insightful, give it a star! ⭐
