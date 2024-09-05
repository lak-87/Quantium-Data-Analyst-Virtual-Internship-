# Quantium-Data-Analyst-Virtual-Internship-

Welcome to my repository Quantium Data Analytics Virtual Internship, which contains the work I've accomplished during Quantium Data Analytics Virtual Experience Program by Forage. 

Certificate of Completion:https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Quantium/NkaC7knWtjSbi6aYv_Quantium_WfhCvYnh4LMnnzbrf_1723766750042_completion_certificate.pdf

## Table of Contents
1.	Introduction 
2.	Tools
3.	Data Exploration and Customer Analytics (Task 1)
4.	Experimentation and uplift testing (Task 2)
5.	Analytics and commercial application (Task 3)

## Introduction

Supermarkets frequently adjust their store layouts, product offerings, pricing, and promotions to meet evolving customer needs and preferences, stay competitive, and seize new opportunities. The data analytics team is involved in these processes to assess and analyze the impact of these changes and provide recommendations on their success. This project includes an in-depth analysis of transactional and customer data and experimentation to deliver practical insights and suggestions for improving sales strategies. 
The project involved three task 

  * Task 1: Data Exploration and Customer Analysis
  * Task 2: Experimentation and Uplift Testing
  * Task 3: Analytics and Commercial Application

## Tools

Data Analysis - Rstudio (Libraries used in R)<br/>
 *	library(ggplot2)<br/>
 * library(tidyr)<br/>
 * library(data.table)
 * library(tidyverse)
 * library(readr)
 * library(skimr)
 * library(janitor)
 * library(data.table)
Excel (for createing charts for final report)
PowerPoint (for creating final report)

## Data Exploration and Customer Analysis (Task 1)
Analyze transaction and customer data to identify customer purchasing behaviours to generate insights and provide commercial recommendations. Create metrics to gain insights into overall sales performance and create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.

### Background information for the task
The Category Manager for Chips wants to get better understanding of the types of customers who purchase Chips and their purchasing behaviour within the region. As a part of Quantium’s retail analytics team, we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. 
<br/>The main goals of the task are :
1.	Exploratory data analysis -examine transaction data and customer data for formatting, missing data, anomalies, outliers 
2.	Data analysis on customer segments – 
•	Who spends the most on chips (total sales), describing customers by lifestage and how premium their general purchasing behaviour is
•	How many customers are in each segment
•	How many chips are bought per customer by segment
•	What's the average chip price by customer segment
•	The customer's total spend over the period and total spend for each transaction to understand what proportion of their grocery spend is on chips
•	Proportion of customers in each customer segment overall to compare against the mix of customers who purchase chips
Experimenting and testing
Explored and cleaned the dataset, formatting the Date column to the Date data type.
Developed metrics and examined sales drivers for overall sales performance insights.
•	Created visualizations and formulated clear recommendations for the client's strategy.
Insights:
•	Sales have mainly been due to budget-older families, Mainstream - young singles/couples, and Mainstream- retirees shoppers. 
•	Mainstream young singles/couples and retirees spend more on chips because there are more of them than other buyers. 
•	Mainstream, midage and young singles and couples are also more likely to pay more per packet of chips. This is indicative of impulse buying behaviour.
•	Mainstream young singles and couples are 23% more likely to purchase Tyrrells chips compared to the rest of the population. 

•	To increase the category’s performance by off-locating some Tyrrells and smaller packs of chips in discretionary space near segments where young singles and couples frequent more often to increase visibilty and impulse behaviour.

4.	Experimentation and Uplift Testing (Task 2)
Create measures to identify controlled stores against trial stores to test the trial store sales performance.
background information on your task
The Category Manager for Chips, requested to test the impact of the new trial layouts with a data-driven recommendation as to whether or not the trial layout should be rolled out to all their stores.
Evaluate the performance of stores 77, 86 and 88. 

Match trial stores 77, 86 and 88 to control stores that are similar to the trial store prior to the trial period of Feb 2019 in terms of :
• Monthly overall sales revenue
• Monthly number of customers
• Monthly number of transactions per customer
Considered Pearson correlations and magnitude distance as measures to compare different control stores to each of the trial stores
The main goals of the task are 
1.	Find the control stores by exploring data, defining metrics and visualize graphs
2.	Assessment of trial -Discover the insights/trends by comparing trial stores with control stores
3.	Summarize and provide recommendations.
Experimenting and testing
Find the control stores
1.	Compile each store's monthly: Total sales, Number of customers, Average transactions per customer, Average chips per customer, Average price per unit
2.	Calculate the correlation and the standardised magnitude distance between the trial store’s performance and each control store’s performance. 
3.	Selected control stores based on how similar monthly total sales in dollar amounts and monthly number of customers are to the trial stores.
4.	Visualized the trends based on the drivers for total sales and total customers.
Assessment of trial 
Find the uplift in overall chip sales and number of customers between the trial period starts from March 2019 to June 2019. 

1.	Apply Hypothesis testing – check the null hypothesis of there being 0 difference between trial and control store.
2.	Checked the control and trial stores difference is significant by calculating the 95th percentile of the t distribution with the appropriate degrees of freedom 
3.	created the  visual version by plotting the total sales / total customers of the control store, the total sales/ total customers of the trial stores and the 95th percentile value of total sales/ total customers of the control store.

Insights:
•	Control stores for trials 77, 86, and 88 are 233, 155, and 237 respectively.
•	The results for trial stores 77 and 88 during the trial period show a significant difference in at least two of the three trial months but this is not the case for trial store 86. but overall, the trial shows a significant increase in sales. 

Analytics and Commercial Application (Task 3)
Create a report for the Client, highlighting key insights from Task 1 and Task 2 using the Pyramid Principle.

