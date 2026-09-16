# 🎨 Tableau BI Dashboard: Sales & Traffic Analytics

This interactive dashboard is the final BI product analyzing a global online store. It is designed to monitor key performance indicators (KPIs), evaluate user behavior, and explore the effectiveness of marketing channels in real time.

* **Interactive Version:** [Open dashboard on Tableau Public](https://public.tableau.com/views/SalesUserBehaviorAnalytics/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📊 Dashboard Visual Structure

1. **Key Performance Indicators (KPI Cards with MoM Dynamics):**
   * **Total Revenue:** Total company revenue for the month compared to the previous period.
   * **Total Sold:** Total number of orders compared to the previous period.
   * **Active Users by Month:** Number of active users per month compared to the previous period.
   * **Email Verified:** The share of users who have verified their email address.
   * **Total Country:** Total number of active countries.
2. **Revenue & Active Users Trend:** Displays weekly revenue and user activity dynamics, helping to track seasonal peaks. It allows you to instantly see whether revenue grows proportionally to audience influx, and quickly spot situations where traffic (users) is high while revenue drops (or vice versa), signaling potential conversion or pricing issues.
3. **Revenue by Channel:** Ranks traffic channels by the volume of generated revenue.
4. **Device Share:** Shows the distribution share of traffic and sales by device type.
5. **Top 10 Categories (Treemap):** Visualizes the profitability and share of product categories.
6. **Revenue & Count Account & Average Price by Subscription Status:** Analyzes differences in revenue and counts between subscribed and unsubscribed clients, shows the quantity and share of subscribers versus non-subscribers, and compares the average order value (AOV).
7. **Top-5 Country by Unit Sold:** Demonstrates the geographical distribution of sales.

---

## 🎛️ Interactive Filters
Users can dynamically filter all dashboard metrics using the parameter panel on the right:
* **Date**
* **Continent**
* **Country**
* **Channel**
* **Category**
* **Device**
* **Operating System**
* **Subscription & Verification Status (Is Unsubscribed / Is Verified)**

---

## 🖼️ Preview
![Tableau Dashboard Preview](tableau/Dashboard-analytics.png)
