# 📊 Bank Customer Churn Analysis

## 🧠 Project Overview

I worked on this project to understand a real business problem:

> Why are customers leaving the bank?

At first, it sounded straightforward. But as I went deeper into the data, I realized churn is not random — there are clear patterns behind it.

This project helped me move beyond just using tools to actually **thinking like a data analyst**, asking better questions and connecting insights.

---

## 🎯 Objective

The goal of this analysis is to:

- Identify the key factors driving customer churn  
- Understand which customers are most likely to leave  
- Provide data-driven recommendations to reduce churn  

---

## 📊 Dataset Description

The dataset contains **10,000 customer records** with the following features:

- Customer ID  
- Age  
- Gender  
- Geography (France, Germany, Spain)  
- Credit Score  
- Account Balance  
- Number of Products  
- Active Status (IsActiveMember)  
- Churn (Exited: 1 = Left, 0 = Stayed)  

---

## 🧠 Key Questions Explored

To approach the problem, I broke it down into key areas:

### 👤 Customer Profile
- Does age affect churn?
- Does gender play a role?

### 💰 Financial Behavior
- Does account balance influence churn?
- Are high-value customers more likely to leave?

### 🏦 Customer Relationship
- Does the number of products matter?
- Does being active reduce churn?

### 💳 Financial Status
- Does credit score impact churn?

### 🌍 Geography
- Which regions have the highest churn?

---

## 📈 Data Analysis Process

### 1. Understanding the Problem  
I started with a clear business question:
> “What factors actually cause customers to leave?”

---

### 2. Data Exploration  
I explored the dataset to understand distributions, patterns, and potential relationships.

---

### 3. Feature Engineering  
To make analysis easier, I created groups such as:

- **Age Groups** (e.g. 18–25, 26–35, etc.)  
- **Balance Groups** (Zero, Low, High)  
- **Credit Score Groups** (Low, Medium, High)  

---

### 4. Churn Analysis  
I calculated churn rate using:



Then analyzed churn across different variables.

---

### 5. Visualization  
Built an interactive dashboard in Power BI to clearly present insights and patterns.

---

## 🔍 Key Insights

### 🔢 Overall Churn

- **Churn Rate: 20%**  
👉 This means **1 in every 5 customers is leaving**

---

### 👤 Customer Profile

- Customers aged **46–65** have the highest churn (~50%)  
- Female customers churn more (**25%**) than males (**16%**)  

👉 Churn is higher among specific customer segments

---

### 💰 Financial Behavior

- Customers with **high balances** churn the most (~25%)  
- Customers with **zero balance** churn the least (~14%)  

🚨 The bank is losing **valuable customers**, not just inactive ones

---

### 🏦 Customer Relationship (MOST IMPORTANT)

- Customers with **1 product** → high churn (**28%**)  
- Customers with **2 products** → lowest churn (**8%**)  

---

### ⚡ Customer Activity

- **Inactive customers** → ~27% churn  
- **Active customers** → ~14% churn  

🔥 Inactive customers churn almost **2x more**

---

### 💳 Credit Score

- Low → 24%  
- Medium → 20%  
- High → 20%  

👉 Credit score has **minimal impact on churn**

---

### 🌍 Geography

- Germany → **32% churn 🚨**  
- France → 16%  
- Spain → 17%  

👉 Churn is significantly higher in **Germany**

---

## 🧠 Final Interpretation

After connecting all the insights, one thing became clear:

> Customers are not leaving because of who they are,  
> but because of how they interact with the bank.

---

### 🔥 Core Pattern

Customers most likely to leave are:

- Not actively using the bank  
- Have only one product  
- Have high balances (valuable customers)  
- Are in high-risk regions like Germany  

---

## 💡 Business Recommendations

If I were the bank, I would focus on:

### 1. Increasing Customer Engagement
- Encourage regular account activity  
- Improve user experience  
- Send reminders to inactive users  

---

### 2. Promoting Multi-Product Usage
- Offer product bundles  
- Cross-sell services  
- Incentivize customers to use at least 2 products  

---

### 3. Targeting High-Risk Segments
- Focus on middle-aged customers  
- Focus on high-balance customers  
- Investigate churn in Germany  

---

### 4. Focus Less on Credit Score
- It has minimal impact on churn  
- Behavioral factors matter more  

---

## 📊 Dashboard

I built a Power BI dashboard to visualize:

- Churn distribution  
- Customer segments  
- Key drivers of churn  
- Regional differences  

---

### 
![](https://github.com/manuel-sam/bank-customer-churn-analysis-/blob/main/Churn%20Dashboard%201.png)
![](https://github.com/manuel-sam/bank-customer-churn-analysis-/blob/main/Churn%20Dasnboard%20page%202.png)


---

## 🛠 Tools Used

- **Power BI** (Dashboard & Visualization)  
- **Excel** (Data preparation & analysis)  

---

## 🚀 What I Learned

This project helped me:

- Move from just using tools to **thinking like an analyst**  
- Ask better, more structured questions  
- Understand how to connect data insights to business decisions  
- See the importance of **customer behavior over assumptions**  

---

## 📌 Final Note

This project is part of my journey into data analysis.

I’m continuously learning, improving, and building — one project at a time.

---

## 📫 Let’s Connect

- LinkedIn(https://www.linkedin.com/in/emmanuel-samuel001)
