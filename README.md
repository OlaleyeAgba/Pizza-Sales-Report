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

This Data Analysis Project aims to provide insight into the Sales Performance of Pizza over the past year. By analysis various aspects of the sales data , we seek to identify trends, make datadriven recommendation, and gain a deeper understanding of the Pizza Company performance. 

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
1. The  analysis results are summarised as follows:
2. Orders are highest on weekends Friday and Saturday evenings.
3. There are maximum orders from month of July and January. 
4. Classic Category contribute to maximum sales and total orders.
5. Larges Size Pizza contribute to maximum sales. 
6. The Thai Chicken Pizza contribute to maximum Revenue.
7. The Barbecue Chicken contribute to maximum Total Quantities
8. The Classic Deluxe Pizza contribute to maximum Total Orders.
9. The Brie Carre Chicken Pizza minimum Revenue, minimum Total Quantities and Orders.


### Recommedations
Based on the analysis, we recommed the following actions:
- Invest in marketing and promotion during the Peak Sales seasons to maximize revenue.
- Focus on expanding and promoting Classic Category and Large Size Pizza

### Limitation
I have to remove all zero values from Revenue column because they would have affected the accuracy of my conclusion from analysis.

### References
1. Youtube - [Data Tutorials](https://youtu.be/V-s8c6jMRN0?si=GhC_5pPP_JGiuQSQ)
