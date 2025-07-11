# 🏗️ Operational Breakdown Analysis – Finding Root Causes Behind Revenue Loss

> 📉 A cross-departmental root cause system to trace failures and recover lost revenue using Python & Power BI

---

## 🧠 Project Overview

Companies silently lose crores in revenue due to **operational failures** like late shipments, stockouts, vendor delays, and IT outages. These issues are often spread across departments and **not directly connected to revenue loss**, making them hard to fix.

This project builds a **data-driven system** that:
- 📍 Detects where failures are happening
- 🔍 Traces them to root causes like vendors, products, or systems
- 💸 Calculates the exact revenue lost per failure type
- 🎯 Prioritizes high-impact fixes with ROI-driven planning

Built using **Python (Pandas, Seaborn, Matplotlib)** for analysis and **Power BI** for business dashboards.

---

## ❓ Business Questions Answered

### 1️⃣ Which departments and processes cause the most revenue impact?

- 💰 ₹646M revenue lost out of ₹1,048M total — **61.5% lost to failures**
- 🏗 Logistics, Vendor, and Inventory alone cause **97.5%** of total loss
- 🔧 IT and Support losses are minimal — low-priority areas

**Recommendations:**
- Focus recovery efforts on **Logistics**, **Vendor**, and **Inventory**
- Set revenue-recovery KPIs by department
- Launch root-cause projects to address top leakages

---

### 2️⃣ What are the most common failure modes and their financial impact?

- 🚛 Carrier delays, 📦 stockouts, 🤝 vendor delays, 🛑 escalations, and ⚠️ system outages are the top 5
- These appear in **40,000+ cases each** and cost **₹208M+ per type**
- 95% of revenue loss comes from these 5 failures

**Recommendations:**
- Enforce SLAs with vendors & carriers  
- Implement demand forecasting to reduce stockouts  
- Automate support workflows and outage alerts  

---

### 3️⃣ What hidden drivers are causing these failures?

- 🔟 Top 10 products = ₹63M in stockout loss  
- 🧪 Failures are recurring — not random  
- 🔍 Vendor metrics track speed, but not **shipment completeness**
- 3 vendors cause **40%** of vendor-related loss  
- 5 product categories = **90%+** of stockout loss

**Recommendations:**
- Add **fill rate, partial shipment** metrics to vendor scorecards  
- Set alerts for high-loss SKUs  
- Reduce reliance on top 3 vendors  
- Automate restocking for top 5 product categories  

---

### 4️⃣ Where should we invest for maximum savings and ROI?

| Department     | ROI     | Fix Cost (₹M) | Recovery (₹M) | Priority |
|----------------|---------|---------------|----------------|----------|
| 🏪 Inventory    | 7.0x    | ₹30M          | ₹209M          | ⭐ Highest |
| 🚚 Logistics    | 5.3x    | ₹40M          | ₹211M          | ✅ High |
| 🏭 Vendor       | 6.0x    | ₹35M          | ₹210M          | ✅ High |
| 🖥 IT Systems   | 0.8x    | ₹10M          | ₹8M            | 🔻 Low |
| 📞 Support      | 1.4x    | ₹5M           | ₹7M            | 🔻 Low |

**Recommendations:**
- 💡 Prioritize investment in **Inventory**, **Vendor**, and **Logistics**
- 📉 Deprioritize IT & Support upgrades unless critical
- 🧠 Align operational spending with ROI potential

---

## 📊 Tools Used

- 🐍 Python (Pandas, Matplotlib, Seaborn)  
- 📊 Power BI (Dashboards, KPIs, Departmental Drilldowns)

---

## 💡 Key Outcomes

- 🧩 Connected failures to revenue impact — not just process inefficiency  
- 💸 Identified ₹630M+ loss from top 3 departments  
- 📌 Prioritized ROI-based recovery projects  
- 📈 Delivered department-wise and failure-type breakdowns via Power BI  
- 🧠 Gave leadership a focused roadmap for operational improvement  

---

## 🙋‍♂️ About Me

**Madhu B M**

📧 **Email**: [Madhubm9243@gmail.com](mailto:Madhubm9243@gmail.com)  
💼 **LinkedIn**: [linkedin.com/in/madhubm9243](https://www.linkedin.com/in/madhubm9243)  
🐙 **GitHub**: [github.com/madhubm9243](https://github.com/madhubm9243)

---

> 🧠 *“Revenue loss is a symptom — this project uncovers the root causes and shows where to act.”*
