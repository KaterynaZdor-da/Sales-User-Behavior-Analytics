# 🛒 Global E-Commerce Sales & User Behavior Analytics

📌 Project Overview
This project is dedicated to a comprehensive exploratory data analysis (EDA) of a global online store's dataset covering the period from November 1, 2020, to January 31, 2021. The objective of the project is to identify key patterns in sales, user behavior, and traffic channel efficiency to optimize business strategy and maximize revenue.


## 📊 Data Sources & Tools

* **Original Dataset:** Educational dataset provided by the **Mate Academy** learning platform.
* **Data Extraction & Feature Engineering (Google BigQuery):** A unified detailed dataset was gathered from the cloud storage using advanced SQL queries with `LEFT JOIN` operations (`DA.session`, `DA.session_params`, `DA.account_session`, `DA.account`, `DA.order`, `DA.product`), combining session parameters, verification/subscription statuses, and product details.
* **Data Cleaning & Processing:** The resulting dataset was imported into the Google Colab environment using the `google-cloud-bigquery` library, where exploratory data analysis (EDA), data cleaning, and core business metric calculations were performed.
* **Visualization:** Tableau Public (building an interactive dashboard featuring key KPIs, trend analysis, traffic channels, subscriptions, and product categories).
