# Power-Electro-Analysis

<details open>
  <summary>Table of Contents:</summary>
  
- [Project Background](#project-background)
- [Data Structure](#data-structure)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)

</details>


# Project Background:

**Power Electro** is a global e-commerce company **Operating since 2018**, specializing in selling popular electronics from leading brands like Apple, Samsung, and ThinkPad. Recently, Power Electro has been collecting significant amounts of data on a variety of key elements, including **orders**, **customer information**, **products**, and **geographic data**. However, the data is currently unrefined and underutilized, presenting both challenges and opportunities for unlocking valuable insights. As a data analyst, my role is to analyze this data in order to extract insights and deliver recommendations to improve performance across sales, product, and marketing teams.

The goal of this analysis is to transform raw data into actionable insights that can drive data-driven decision-making across the organization, which will ultimately improve Power Electro's commercial success.

An interactive Power Bi dashboard used to report and explore churn rate across key dimensions can be found [Here]()

  
# Data Structure:
The companies main database structure as seen below consists of **5 tables**: **Orders**, **Order_Status**, **Customers**, **Geographics** and **Dim_Date** with a total row count of **108 125 records**. A description of each table is as follows:
- **Orders Table:** This table contains the core transactional data for all orders placed on the Power Electro platform. It serves as the fact table in the database schema.
- **Order Status Table:** This table provides details about the different order status codes and includes key dates related to the order lifecycle.
- **Geographics Table:** This table provides geographic information associated with specific location IDs.
- **Customers Table:** This table contains information about Power Electro's customers.
- **Date Table:** This table provides a structured representation of dates, enabling efficient filtering and grouping of data by various time periods.

![star_schema power electro](https://github.com/user-attachments/assets/343f76d4-cdd1-4a1c-8e09-00efac18c736)

# Executive Summary

## Overview of Findings

From **2019 to 2020**, Power Electro reached total sales of **$28M**, with **108K** orders and an average order value of **$260**.
- 2020 had a **huge spike in sales**, this year was the best for the company as it generated total sales of **$10M**. This result  was driven by a change in customer behavior, as many consumers shifted their shopping habits during the pandemic, leading to a significant increase in online purchases.
- After this strong performance in 2020, there’s been a pretty steady decline across late 2020 and 2021, but from 2021 to 2022, sales have significantly declined throughout the entire year. Key performance indicators have all shown year-over-year decreases: **order volume by 39.9%**, **revenue by 45.7%**, and **average order value (AOV) by 9.7%**. This drop can be broadly attributed to a return to pre-pandemic normalcy.


![image](https://github.com/user-attachments/assets/d6f9d745-c848-42e9-8dfd-ea34c1074474)


# Insights Deep Dive
## 1. Sales Trends:

#### Revenue:

- **Entire Period (2019–2022):** From 2019 to 2022, Power Electro generated an average of $7M in annual sales, with around 27,000 orders per year.
- **COVID-19 Period (2019–2020):** Between 2019 and 2020, the company’s revenue continued to increase, reaching its peak in December 2020 at $1.25M.
- **After COVID-19 (Post-December 2020):** Since December 2020, sales have generally declined, with the largest drop occurring in October 2022 (–55%), when monthly sales fell to $178K.
  
![image](https://github.com/user-attachments/assets/2bace09e-d11a-4c3d-a139-ad9a3f899ffc)

#### Orders:

- The number of orders follows a trend similar to that of revenue, where the quantity sold continued to increase until reaching its highest level in **December 2020**, with a total of **4,019** orders.
- After this peak, the order volume began to decline, eventually reaching its lowest point in **October 2022**, with only **825 orders**, representing a **47% decrease** from the previous month.

![image](https://github.com/user-attachments/assets/65eb1e79-963f-4edf-800f-54f9639ba1f6)


#### Average Order Values (AOV):

- The AOV generally fluctuates between $250 and $320 across the observed period (2019–2022).
- Notably,The AOV reached its highest point at **$321** per order in **October 2020**. By contrast, it fell to a low of **$217** per order by **October 2022**. This significant drop suggests that although customers were spending more per order at the peak, they gradually shifted to lower spend levels over time.
  
![image](https://github.com/user-attachments/assets/7a2c28ae-b070-415e-b566-0f90a62b696d)

## 2. Product Performance: 
- Three categories (Gaming Monitors, Headphones, and Chargers) account for 86.7% of all orders and generate $27 M, or 96% of total revenue.
- The Headphones category continues to grow as a share of orders—now at **48%** in 2022, up from **43%** in 2020. However, headphones still account for less than **28%** of total revenue.
- The **27 inch 4K Gaming Monitor ($9.9 M)**, **AirPods ($7.7 M)**, and **MacBook Air ($6.3 M)** dominate the SKU ranking, driving the bulk of revenue.
- The company is heavily reliant on Apple products, with the brand accounting for **51%** of total revenue. Apple's iPhone has yet to make an impact though, registering less than **1%** total sales.

![image](https://github.com/user-attachments/assets/14895e65-f3d8-4e99-95ff-9c8f35afc736)

## 3. Loyalty Program:

- The loyalty program has grown rapidly since its launch in 2019. Membership peaked in 2021 at **16,977 loyal customers**, representing **57% of the total customer base**, up from just **12% (1,622 members)** in 2019.
- Loyalty‑program revenue jumped from just **$4.3K** in 2019 to a peak of **$5.1M** in 2021. In both 2021 and 2022, loyalty revenue (**$5.1M** and **$2.9M**, respectively) exceeded non‑loyalty revenue (**$4.4M** and **$2.3M**), highlighting the program’s growing pull and stickiness.
- **Over the 2019–2022** period, loyalty members contributed **$11.5M nearly 40% of the **$28.1M** total revenue—underscoring that, while non‑loyalty revenue peaked in 2020 then declined, the loyalty program has become a substantial and stable driver of overall sales.

![image](https://github.com/user-attachments/assets/5602f712-9b62-491a-b77a-e38727ca9262)


- 



