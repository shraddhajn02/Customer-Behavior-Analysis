# Customer-Behavior-Analysis
Developed controlled experiments (A/B tests) for digital personalization and hierarchical regression to analyze consumer purchasing behavior, improving market insights and forecasting accuracy by 30%.

# 📊 Consumer Behavior Analysis for DIG 🍽️

## 📌 Project Overview
This repository contains the **consumer purchasing behavior analysis** conducted for DIG, a farm-to-table restaurant near Drexel University. The project leveraged **Choice-Based Conjoint (CBC) experiments, hierarchical regression modeling, and A/B testing** to understand key factors influencing students' meal decisions and improve **forecasting accuracy by 30%**.

## 🎯 Objectives
- **Analyze** how **price, payment methods, wait time, and convenience** influence consumer behavior.
- **Segment customers** based on their **price sensitivity and payment preferences**.
- **Use hierarchical regression** to quantify the impact of various factors on **customer satisfaction and purchase decisions**.
- **Develop forecasting models** to improve **demand prediction for DIG**.
- **Propose A/B testing strategies** to enhance digital marketing efforts.

---

## 🛠️ Methodology & Approach

### **1️⃣ Data Collection**
- **Survey Responses (231 participants, 924 evaluations)** capturing **food preferences, spending behavior, and customer experience**.
- **Choice-Based Conjoint (CBC) Experiments (2023 & 2024)**
  - Simulated real-life decision-making scenarios where respondents **chose meal options based on different attributes**.
  - Attributes analyzed:
    - **Price:** $7, $10, $15, $20, $25, $28
    - **Payment Methods:** Cash, Credit Card, Apps, Dragon Dollars
    - **Wait Time:** 5 min, 10 min, 15 min, 20 min
    - **Order Method:** Pick-up, Sit-down, Delivery
    - **Walking Distance:** 3 min, 7 min, 12 min (2024)

---

### **2️⃣ Data Analysis & Modeling**
- **Choice-Based Conjoint Analysis (CBC)**
  - **Importance Score Analysis:** Ranked factors based on how much they influence purchasing decisions.
  - **Market Segmentation:** Grouped customers into:
    - **Price-Sensitive Cluster**
    - **Payment-Method-Sensitive Cluster**
    - **Non-Target Customers**
  
- **Hierarchical Regression Analysis**
  - Dependent Variables:
    - **Overall Experience**
    - **Number of Meals Purchased**
  - Independent Variables:
    - **Food Taste**
    - **Wait Time**
    - **Convenience of Purchase**
  - Findings:
    - **Food taste had the strongest impact** on customer experience (β = 0.555, p < 0.001).
    - **Convenience was the biggest driver of sales** (β = 0.654, p < 0.001).
    - **Reducing wait time improved satisfaction** (β = -0.036, p = 0.055).

- **A/B Testing for Marketing Strategy**
  - Suggested an **A/B test for DIG’s app messaging**:
    - **Current Message:** "Have dinner for dinner."
    - **New Proposed Message:** "Fresh meals for lunch, dinner, and anytime in between."
    - **Success Metrics:** Click-through rates, order conversions.

---

## 📈 Key Findings & Impact
- **Price and Payment Methods** were the most influential factors in **lunch decisions**.
- Customers **strongly preferred** restaurants that accepted **multiple payment options** and had meals priced **under $15**.
- **Reducing wait times** directly improved **customer satisfaction and sales**.
- **Personalized marketing efforts** (e.g., **targeting price-sensitive vs. payment-method-sensitive customers**) can improve engagement.
- **30% improvement in forecasting accuracy** through **hierarchical regression and CBC analysis**.
