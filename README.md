# Churn User Analysis_PBI

## 📑 Table of Contents
- 📌 Background & Overview  
- 📂 Dataset Description & Data Structure  
- 🧠 Design Thinking Process  
- 📊 Key Insights & Visualizations  
- 🔎 Final Conclusion & Recommendations  

---

## 📌 Background & Overview

### **Objective:**
This project analyzes customer churn trends in a telecommunications company using Power BI. The objective is to:
- Identify key factors influencing churn.
- Develop data-driven retention strategies.
- Improve customer engagement and reduce churn rates.

### **👤 Who is this project for?**
✔️ Data analysts & business analysts  
✔️ Marketing & customer retention teams  
✔️ Decision-makers & stakeholders  

### **❓ Business Questions:**
✔️ What are the key factors driving customer churn?  
✔️ How do customer behaviors differ between churned and non-churned users?  
✔️ What strategies can reduce churn and improve customer retention?  

### **🎯 Project Outcome:**
✔️ Customer Segmentation: Identified patterns among high-risk churn segments.  
✔️ Retention Strategies: Suggested targeted interventions to reduce churn.  
✔️ Business Impact: Improved understanding of customer lifetime value and engagement drivers.  

---

## 📂 Dataset Description & Data Structure

### **📌 Data Source**
- **Source:** Company database  
- **Size:** ~5,700 rows, 20 columns  
- **Format:** `.csv`  

### **📊 Data Structure & Relationships**

#### **1️⃣ Tables Used:**
- Customer data table containing demographic, behavioral, and transaction-related features.

#### **2️⃣ Table Schema & Data Snapshot**

| Column Name               | Data Type | Description |
|---------------------------|-----------|-------------|
| CustomerID                | INT       | Unique identifier for each customer |
| Churn                     | BOOL      | Churn status (0 = Retained, 1 = Churned) |
| Tenure                    | INT       | Number of months the customer has been with the company |
| PreferredLoginDevice      | TEXT      | Customer's most used device for login |
| HourSpendOnApp           | FLOAT     | Average hours spent on the app per day |
| SatisfactionScore         | INT       | Customer satisfaction rating (1-10) |
| OrderCount               | INT       | Total number of orders placed |
| DaySinceLastOrder        | INT       | Days since the last purchase |
| CashbackAmount           | FLOAT     | Total cashback received |

---

## 🧠 Design Thinking Process

1️⃣ **Empathize:** Understand customer behavior and business impact.  

![Image](https://github.com/user-attachments/assets/4c11c56c-20f7-4143-a3ed-062e71386505)

![Image](https://github.com/user-attachments/assets/aeb3f20d-1bbb-4583-98a3-4b223f61ac8e)

![Image](https://github.com/user-attachments/assets/b2f7f166-0193-4f27-a8d0-04b109c823cc)

2️⃣ **Define:** 

![Image](https://github.com/user-attachments/assets/59f1f0b1-f3d8-4a07-9a78-9569106c190f)

![Image](https://github.com/user-attachments/assets/e97c41f3-965e-4af6-a089-97ffa00feb22)


3️⃣ **Ideate:**   

 ![Image](https://github.com/user-attachments/assets/96148c24-3521-46c4-8e60-e13f8a1f3f9c)

 ![Image](https://github.com/user-attachments/assets/7cee03cc-6a09-4f8d-a777-4e3f000f5c46)

---

## 📊 Key Insights & Visualizations
### 📌Visualization

#### 1. Customer Overview
![image](https://github.com/user-attachments/assets/0d85eacf-b33a-4b5e-b405-ce90f66d44ad)
#### 2. Customer Detail
![image](https://github.com/user-attachments/assets/0007500c-4be1-4f02-b730-6cea7f2c7e45)
#### 3. Churn Reason
![Image](https://github.com/user-attachments/assets/52dd1101-54f5-4da6-a1d2-7d670ce6f423)

### 🔍Key Insights
#### **1️⃣ Demographics & Churn Trends**
- **81% of customers are over 30**, but churned users have an even higher proportion (**84%**).
- **Churn is slightly higher among older users**, suggesting a need for retention strategies tailored to this segment.

#### **2️⃣ Service Usage & Churn Impact**
- **UDP service users show high churn (80%)**, compared to 67% in the overall customer base.
- **International active users have higher churn (49%)**, while group plan users have much lower churn (6% vs. 23%).
- **Group plans appear to improve retention**, indicating potential benefits in promoting them.

#### **3️⃣ Contract Type & Payment Behavior**
- **88% of churned users are on month-to-month contracts**, compared to 51% in the overall customer base.
- **Direct debit is the dominant payment method (71%) among churned users**, suggesting that payment preferences may influence retention.

#### **4️⃣ Financial Impact & Customer Spending**
- **Churned users pay a higher average monthly charge ($36.8) but have a lower total charge ($761.4)**, indicating they leave earlier.
- **Long-term contracts correlate with lower churn**, showing a need for better long-term incentives.

#### **5️⃣ Churn Reasons Analysis**
- **Competitor-related churn is the highest (45.5%)**, indicating that many customers leave due to better offers, devices, or data plans from competitors.
- **Attitude-based churn accounts for 16.2%**, with poor support service being a key issue (11.3%).
- **Dissatisfaction and Price contribute equally (16.2% each)**, showing that customer experience and pricing need attention.
- **The top 5 churn reasons include competitor offers, better devices, and poor support experiences.**

---

## 🔎 Final Conclusion & Recommendations
✅ **Retention Strategies for Older Users**
   - Personalize engagement for users over 30 with tailored benefits.

✅ **Improve UDP Service & Pricing**
   - Investigate why UDP users have higher churn and offer better value propositions.

✅ **Encourage Group Plan Subscriptions**
   - Promote bundled services to reduce churn risk.

✅ **Targeted Discounts for Month-to-Month Users**
   - Offer incentives for long-term commitments to improve retention.

✅ **Enhance Value Perception for High-Churn Segments**
   - Implement loyalty rewards for high-risk customers to maintain engagement.

✅ **Competitive Benchmarking & Pricing Strategy**  
   - Regularly analyze competitor offers and adjust pricing or value-added services to retain price-sensitive customers.  
   - Introduce personalized retention offers for users at risk of switching due to competitor promotions.

✅ **Customer Support Enhancement**  
   - Improve training for support teams to enhance service attitude and responsiveness.  
   - Implement proactive support strategies, such as AI-driven assistance or priority support for at-risk customers.

✅ **Value-Based Customer Retention**  
   - Offer exclusive benefits or loyalty rewards to customers on the verge of churning.  
   - Expand device upgrade programs or better data offerings to match competitor incentives.

✅ **Better Communication & Education**  
   - Educate customers on service benefits, reducing uncertainty (“Don’t know” was a notable churn reason).  
   - Improve transparency in service plans and pricing to reduce dissatisfaction-driven churn.
  
---




