# Customer Churn Analysis Dashboard

> An interactive Excel dashboard analyzing customer churn distribution by state, plan, and demographics — built to uncover key retention insights.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Description](#data-description)
- [Key Features](#key-features)
- [Dashboard Preview](#dashboard-preview)
- [Tools and Technologies](#tools-and-technologies)
- [Insights](#insights)
- [Key Learnings](#key-learnings)  
- [Recommendations](#recommendations)  
- [Conclusion](#conclusion)  

---

## Project Overview
This project analyzes a **simulated customer churn dataset** designed to mirror the structure of a real-world **telecommunication company (MTN)** customer database. The dataset includes key customer attributes such as state, subscription plan, tenure, and usage patterns, providing a realistic framework for churn analysis.  
This project demonstrates practical experience in **data cleaning, analysis, visualization, and interactive dashboard design**, and showcases the ability to translate data into actionable business insights, even using simulated datasets.

---

## Objectives
The aim of this project is to answer the following questions:  
- **Who are the customers?**  
- **Where is churn happening?**  
- **When and why are customers leaving?** 
- **What is the impact of churn on the business?**  

Other objectives include:  
- Analyze churn distribution by state, plan, and customer segment  
- Identify high-churn regions and customer groups  
- Track overall churn rate and retention metrics  
- Build an interactive dashboard for easy exploration and decision-making

---

## Data Description
The dataset is **simulated** but structured to reflect typical MTN customer data.  
It contains the following key attributes:  
- **Customer ID:** Unique identifier for each customer
- **Full Name:** Name of each customer
- **State:** Geographic location of the customer  
- **Subscription Plan:** Type of service plan  
- **Tenure:** Length of time the customer has been active  
- **Age Group:** Age category of the customer  
- **MTN Device:** Type of device used
- **Satisfaction Rate:** Customers rating of services offered ranging from 1-5  
- **Churn Status:** Whether the customer has churned (Yes/No)  
- **Churn Reasons:** Their reason for leaving

---

## Key Features
- **Map Chart:** Visualizes churn distribution across states  
- **KPI Cards:** Show churn rate, retention rate, total customers, total revenue lost and churned customers  
- **Bar & Pie Charts:** Compare churn by gender, device, and subscription plan  
- **Dynamic Slicers:** Allow users to filter the dashboard interactively by **months, device type, customer age group, and tenure group**, enabling quick and flexible insights 

---

## Dashboard Preview

<p align="center">
  <img src="images/Customer Churn Analysis.png" alt="Dashboard Preview" width="750">
  <br>
  <em>Excel dashboard showing customer churn analysis</em>
</p>

---

## Tools and Technologies
- **Excel:** Power Query, Pivot Tables, Pivot Charts, Slicers  
- **Data Cleaning & Transformation:** Power Query  
- **Visualization:** Excel Dashboard  
- **Dataset Source:** https://www.kaggle.com/datasets/oluwademiladeadeniyi/mtn-nigeria-customer-churn?resource=download  

--- 

## Insights

The customer churn analysis tells a compelling story about customer behavior, loyalty, and revenue impact.

- The company had a **total of 496 customers**, out of which **146 churned**, representing a **29.44% churn rate** and a **70.56% retention rate**. This resulted in a **₦58 million revenue loss**, showing that customer attrition is having a major financial impact.

- When viewed by **gender**, **female customers churned more (52.74%)** compared to **male customers (47.26%)**, suggesting that women might be more responsive to pricing, competitor incentives, or perceived service quality.

- By **device type**, churn was highest among **mobile SIM card users (39.04%)**, followed by **4G routers (25.34%)**, **5G broadband routers (18.49%)**, and **broadband MiFi devices (17.12%)**. This suggests that customers on flexible, low-commitment devices find it easier to switch providers.

- **Long-tenure customers (2+ years)** churned the most, followed by those with **1–2 years of service**. This indicates that loyal customers, the very ones who have stayed longest, are leaving. The pattern is echoed in the ratings data, where customers who rated the company as *“Very Good (4⭐)”* and *“Excellent (5⭐)”* churned the most. Clearly, **satisfaction does not guarantee loyalty**.

- When examining **reasons for churn**, the top drivers were **better offers from competitors (29 customers)** and **high call tariffs (26 customers)**. Other strong factors included **poor network quality (20)**, **costly data plans (20)**, **fast data consumption (18)**, **poor customer service (18)**, and **relocation (15)**. These pain points show that churn is being driven by both **external competition** and **internal service challenges**.

- The **1.5TB yearly broadband plan** accounted for the **largest revenue loss (₦15 million)**, followed by the **165GB monthly plan (₦8 million)**. These are high-value products, meaning the company is losing its most profitable customers.

- From the **age group analysis**, customers aged **30–44 years** contributed the **highest revenue loss (₦19 million)** with a **28.52% churn rate**, followed by **18–29 years (₦15 million, 19.72%)** and **60+ years (₦13 million, 28.17%)**. This shows that the **working-age population**, which is the company’s core customer base, is driving the majority of churn.

- The **map visualization** adds a geographical perspective. **Bauchi** recorded the **highest churn count (9)**, followed by **Imo, Jigawa, Plateau, and Taraba (7 each)**, and **Ondo, Zamfara, Kaduna, and Gombe (6 each)**. Overall, churn appears to be **heavier in the northern part of Nigeria**, suggesting possible issues with network quality, infrastructure, or service reach in that region.

- The **timeline slicer** reveals a worrying seasonal trend:
  - **January:** 33 customers churned, ₦13.78M lost, **24.26% churn rate**
  - **February:** 72 customers churned, ₦30.59M lost, **31.58% churn rate**
  - **March:** 41 customers churned, ₦13.63M lost, **31.06% churn rate**

  The **spike in February** indicates a potential event such as a competitor promotion, tariff change, or temporary service issue that triggered a mass customer exit. This pattern highlights the need for ongoing churn monitoring and proactive intervention.

---

## Key Learnings

- **Loyalty doesn’t always prevent churn.** Even long-tenure and satisfied customers can leave if competitors provide better perceived value.  
- **Pricing, service quality, and competition** are the strongest churn drivers in telecom markets.  
- **Data segmentation and interactive dashboards** (using slicers for age, tenure, and device type) help uncover insights that would otherwise remain hidden.  
- **Regional and seasonal analysis** are vital because churn patterns differ by geography and time.  
- A data-driven approach to churn can directly guide **customer retention, marketing, and pricing strategy**.

---

## Recommendations

1. **Strengthen Retention Programs**  
   - Develop personalized retention offers for **long-tenure and high-value customers**, such as loyalty discounts or exclusive renewal benefits.  
   - Implement churn prediction models to identify at-risk customers early.

2. **Revisit Pricing and Plans**  
   - Reassess **call tariffs** and **data plan pricing**, especially high-churn plans like the 1.5TB yearly and 165GB monthly packages.  
   - Offer **flexible or promotional bundles** that make staying more attractive than switching.

3. **Enhance Network Reliability**  
   - Prioritize network upgrades and maintenance in **northern states** where churn is highest (for example, Bauchi, Jigawa, and Taraba).  
   - Conduct customer experience surveys to monitor satisfaction with coverage and speed.

4. **Improve Customer Experience**  
   - Investigate why satisfied customers are still leaving, possibly due to **competitor marketing or perceived value gaps**.  
   - Strengthen customer service training and responsiveness to reduce service-related churn.

5. **Focus on Female Customers**  
   - Design engagement campaigns and bundles that appeal specifically to **female customers**, who show slightly higher churn rates.  

6. **Address Seasonal and External Factors**  
   - Examine **February’s churn spike** to identify specific triggers such as tariff increases, service issues, or competitor deals.  
   - Use monthly churn tracking dashboards to anticipate and prevent future churn surges.

---

## Conclusion

This analysis reveals that customer churn isn’t limited to dissatisfied users. It also affects **loyal and high-value customers** who may be lured away by better offers or experience service-related frustrations.  

To reduce churn and recover lost revenue, the company must combine **competitive pricing, consistent service quality, and targeted retention programs**.  

With a **data-driven approach** powered by this dashboard, management can move from reacting to churn to **predicting and preventing it**, thereby boosting customer satisfaction, protecting revenue, and strengthening long-term loyalty.

