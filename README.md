# 📊 Quick Bite Express – Pre-Crisis & Crisis Impact Analysis
Power BI dashboard analyzing pre-crisis vs crisis impact on orders, revenue, customers, restaurants, and delivery performance.

## 🔍 Project Overview

This project analyzes the **business impact of a crisis on an online food delivery platform** by comparing **Pre-Crisis** and **Crisis** periods.
The goal was to understand **how customer behavior, order volumes, restaurant performance, and delivery experience changed**, and to identify **key drivers behind revenue decline, churn, and negative feedback**.

The entire analysis was built using **Power BI** with **DAX-driven KPIs**, focusing on **business storytelling rather than just visual creation**.

---

## 🎯 Business Problem

During the crisis period, the platform experienced:

* Sharp decline in orders and revenue
* Increase in cancellations and delivery delays
* Customer churn and reduced repeat behavior
* Restaurant inactivity and performance drop
* Rise in negative feedback and poor ratings

Stakeholders needed a **clear, phase-based comparison** to:

* Quantify the impact
* Identify the most affected cities, customers, and restaurants
* Support recovery and operational decisions

---

## 🧠 Project Objective

* Compare **Pre-Crisis vs Crisis** performance across business dimensions
* Identify **where and why performance dropped**
* Highlight **customer, restaurant, and delivery-level insights**
* Build a **stakeholder-ready dashboard** with clean navigation and KPIs

---

## 🛠️ Tools & Technologies

* **Power BI**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **Business Analysis**

---

## 📌 Key Metrics Used

* Total Orders
* Order Decline %
* Revenue & Revenue Loss %
* Cancellation Rate %
* Average Order Value (AOV)
* Customer Churn %
* Restaurant Churn %
* SLA Compliance %
* Delivery Time
* Customer Ratings
* Negative Feedback %

---

## 📑 Dashboard Pages & Explanation

---

### 🏠 Home Page

**Purpose:**
Acts as a navigation hub and project summary.

**Key Features:**

* Page navigation buttons for smooth user flow
* Project objective and business context
* Definitions for key metrics (AOV, SLA, Churn)
* Clean, minimal design for first-time viewers

**Why it matters:**
Ensures any stakeholder understands *what the dashboard is about* before diving into insights.

---

### 📊 Executive Snapshot

**Purpose:**
High-level business summary for leadership.

**Key Insights:**

* Overall order decline and revenue impact
* Comparison of pre-crisis vs crisis KPIs
* Cancellation rate and AOV trends
* City-wise revenue loss highlights

**Skills Applied:**

* KPI design
* Context-aware DAX measures
* Executive-level storytelling

---

### 📈 Orders Trend – Phases

**Purpose:**
Analyze how order volume changed over time.

**Key Insights:**

* Clear drop in orders after crisis onset
* Phase-based trend comparison avoids data distortion
* Channel-level order contribution (Organic, Paid, Referral)

**Why phase logic was used:**
Mixing both periods would misrepresent averages and decline percentages.

---

### 🌆 Cities Impact

**Purpose:**
Identify cities most affected by the crisis.

**Key Insights:**

* City-wise order decline %
* Revenue loss contribution by city
* Helps prioritize regional recovery strategies

**Skills Applied:**

* Ranking & Top-N analysis
* Percentage-based decline metrics
* Filter interaction handling

---

### 🍽️ Restaurants – Volume & Churn

**Purpose:**
Understand restaurant-side impact.

**Key Insights:**

* Restaurant order volume decline
* Restaurant churn %
* Cancellation vs order decline relationship
* Identification of high-risk restaurants (≥50 pre-crisis orders)

**Advanced Analysis:**

* Scatter plot showing order decline vs cancellation rate
* Tables highlighting top restaurants by decline

**Key Learning:**
Percentage metrics can appear extreme at low volumes and must be interpreted carefully.

---

### 👥 Customer Behavior & Loyalty Analysis

**Purpose:**
Measure how customer engagement changed.

**Key Insights:**

* Drop in active and repeat customers
* Increase in customer churn during crisis
* Shift in customer value contribution
* Retention funnel from pre-crisis to crisis

**Important Note:**
Metrics like AOV, churn %, and averages are **non-additive**, so totals reflect weighted calculations, not simple sums.

---

### 🚚 Delivery & Sentiment Insights

**Purpose:**
Analyze operational experience and feedback.

**Key Insights:**

* Increase in average delivery time
* Decline in customer ratings during crisis
* Rise in negative feedback %
* Key reasons for dissatisfaction (delay, food quality, packaging)

**Negative vs Non-Negative Orders:**

* Negative orders = poor ratings or complaints
* Non-negative = neutral or positive experience

---

## 🧩 DAX & Modeling Highlights

* Phase-based measures to prevent KPI distortion
* Separate KPIs for Pre-Crisis and Crisis periods
* Non-additive metric handling (AOV, churn %, cancellation %)
* Filter context management for accurate visuals

---

## 🎓 What I Learned

* Designing **business-driven KPIs**, not just visuals
* Importance of **phase-based analysis**
* Handling **non-additive metrics correctly**
* Using DAX to control filter behavior
* Telling a **clear business story** with data
* Structuring dashboards for different stakeholders

---

## 🚀 Key Takeaways

This project demonstrates my ability to:

* Translate raw data into business insights
* Build structured Power BI dashboards
* Apply DAX thoughtfully for real-world scenarios
* Communicate impact clearly to stakeholders

---

## 📌 About the Project

* Part of **Codebasics Resume Challenge**
* End-to-end analysis built independently
* Focused on practical, interview-ready analytics

---

## 🔗 Author

**Savita M**
Data Analyst | Power BI | SQL | Business Analytics

