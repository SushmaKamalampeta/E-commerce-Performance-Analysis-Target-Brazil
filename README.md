# 📦 Target Brazil E-commerce SQL Case Study

A comprehensive SQL-based data analysis project exploring order patterns, delivery performance, customer behavior, and payment insights using Target Brazil’s e-commerce dataset (2016–2018).

---

## 🧠 Project Objective

To derive actionable business insights from a real-world e-commerce dataset of 100,000+ orders placed in Brazil, and help optimize operations, logistics, and customer engagement strategies for Target.

---

## 📂 Dataset Overview

The analysis is based on 8 interlinked CSV files:
- `customers.csv`
- `geolocation.csv`
- `order_items.csv`
- `orders.csv`
- `payments.csv`
- `products.csv`
- `reviews.csv`
- `sellers.csv`

Each file contains dimensions such as customer demographics, delivery timeframes, freight values, product metadata, seller data, and order reviews.

---

## 📊 Key Insights

- **High Delivery Time in Rio de Janeiro:** Despite being a capital city, Rio had **higher delivery time** and **lower order-to-customer ratio** compared to others.
- **Peak Shopping Hours Identified:**  
  - 🕐 **Afternoon (13:00–18:00)** — 38.5% of total orders  
  - 🌅 **Morning & Night (7:00–12:00, 19:00–23:00)** — ~28% each  
  - 🌄 **Dawn (00:00–06:00)** — 5.5%
- **São Paulo (SP)** emerged as the top-performing state in terms of:
  - Order volume
  - Customer base
  - Delivery efficiency
- **Freight & Delivery Optimization:**  
  - RR had the **highest freight** and **longest delivery time**  
  - SE had the **fastest deliveries**
- **Popular Payment Mode:** Credit cards dominate, followed by Boleto and debit cards.
- **Installments:** Many customers opted for EMIs, with some going up to 24 installments.

---

## 🧰 Tech Stack

| Tool        | Purpose                                      |
|-------------|----------------------------------------------|
| **SQL (BigQuery)** | Data cleaning, querying, aggregation        |
| **Google BigQuery** | Cloud-based data warehousing & analytics |
| **Google Sheets/Excel** | Data visualization & post-query analysis  |

---

## ✅ Business Impact

- Pinpointed logistical delays in key cities and suggested alternate shipping partners (e.g., FedEx, DHL).
- Optimized marketing focus based on high-engagement time slots.
- Identified state-wise promotional opportunities to boost underperforming regions.
- Helped design customer retention and personalized discount strategies.

---

## 📌 Recommendations

- Streamline delivery partnerships in high-delay regions like **RJ**.
- Launch **afternoon-focused ad campaigns** for higher conversions.
- Offer **installment-based promotions** and **loyalty rewards** during low-order periods (dawn).
- Expand market penetration in regions with fewer orders via **localized offers**.

---

## 📎 Files Included

- `case_study_queries.sql` – All SQL queries used for analysis  
- `outputs.xlsx` – Sample outputs and visualizations  
- `case_summary.pdf` – Final report with insights and recommendations

---


> _"Data is not just numbers; it's the voice of your business waiting to be heard."_

