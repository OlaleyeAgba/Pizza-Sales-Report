# Pizza Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results-findings)
- [Recommedations](#recommedations)
- [Limitation](#limitation)
- [References](#references)

### Project Overview
---

This Data Analysis Project aims to provide insight into the Sales Performance of Pizza over the past year. By analysis various aspects of the sales data , we seek to identify trends, make datadriven recommendation, and gain a deeper understanding of the Pizza Company performance. 
![Dashboard1](https://github.com/user-attachments/assets/5aa290a9-5b7e-40d7-8256-dff929d3342e)


![Dashboard2](https://github.com/user-attachments/assets/de6e0f11-bb01-41a6-82f9-2b58e4a80b42)


## Data Sources

Pizza Sales Data: The primary dataset used for this analysis is the 'Pizza_Sales1.csv', containing detailed information about each Pizza Sales.

### Tools

- Excel - Data Cleaning [Download_here](https://microsoft.com)
- PgAdmin - Data Analysis
- Power Bi - Visualization/ Report

### Data Cleaning/Preparation

Data Preparation tasks include:
 1. Data loading and inspection.
 2. Handling missing values.
 3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key question, such as;
 What is the overall sales trends?
 Which Pizza are Best Sellers?
 Which Pizza are Worst Sellers?
 What are the Peak Sales Periods?

 ### Data  Analysis
 ```sql
 SELECT sum(quantity) from PIZZA1;
 ```

### Results/Findings
 The  analysis results are summarised as follows:
1. Orders are highest on weekends Friday and Saturday evenings.

   ![order(Fri and Sah)](https://github.com/user-attachments/assets/daa5f536-35a9-4b97-9baf-7bc13bb91a78)

2. There are maximum orders from month of July and May.

   ![Capture](https://github.com/user-attachments/assets/a523036f-870b-45dd-9138-150905562f8c)

3. Classic Category contribute to maximum sales and total orders.

   ![Classic cah](https://github.com/user-attachments/assets/047f6d96-2026-4887-8e05-61a2eb8f6dbc)

4. Larges Size Pizza contribute to maximum sales.

 ![Large Pizza](https://github.com/user-attachments/assets/0ba114e5-1c81-46c8-b8a1-62ea930017e2)

5. The Thai Chicken Pizza contribute to maximum Revenue.

 ![Max Rev](https://github.com/user-attachments/assets/c8fd2553-9e1c-4e84-bf59-50a170574119)

6. The Barbecue Chicken contribute to maximum Total Quantities

   ![Max Qgh](https://github.com/user-attachments/assets/df5f05ca-5fb2-40e9-8190-b75aa40223e4)

7. The Classic Deluxe Pizza contribute to maximum Total Orders.

  ![Max Order](https://github.com/user-attachments/assets/cc242c93-1965-401d-acce-0db94a83efa9)

8. The Brie Carre Chicken Pizza minimum Revenue, minimum Total Quantities and Orders.

![Min Rev](https://github.com/user-attachments/assets/0b91f901-2baa-4eba-8d93-21ad5045e62b)

![Min Qgh](https://github.com/user-attachments/assets/8b20dfa0-34dc-4895-bdd1-e0dc6c454a57)


![Min Order](https://github.com/user-attachments/assets/1dd13681-33d3-44a0-bd8b-337f6921215f)

### Recommedations
Based on the analysis, we recommed the following actions:
- Invest in marketing and promotion during the Peak Sales seasons to maximize revenue.
- Focus on expanding and promoting Classic Category and Large Size Pizza

### Limitation
I have to remove all zero values from Revenue column because they would have affected the accuracy of my conclusion from analysis.

### References
1. Youtube - [Data Tutorials](https://youtu.be/V-s8c6jMRN0?si=GhC_5pPP_JGiuQSQ)


