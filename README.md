# KPMGInternCapstone.github.io
This repository contains the files for my KPMG Data Analytics Consulting Virtual Internship.
[SPROKET DASHBOARD FINAL](https://user-images.githubusercontent.com/70212980/213344502-4e88230f-ad4d-4324-8b69-5adbfc74213f.JPG)

*Project Description*:
The main goal of this project is to get insight from a dataset from a medium-size bikes & cycling accessories organization. The marketing team want to boost the sales by targeted marketing to new customers and I am required to Identify and Recommend Top high value 200 Customer to Target from 1000 new customer Dataset using the 3 datasets provided.

*Data Cleaning*:
Various rows, such as the brand of a purchase, or job title, have empty values in certain records.
For transactions dataset that have missing fields these records have been removed from the dataset.
Null Job titles and DOB were changed to N/A.
Inconsistent values for the same attribute (e g Male being represented as “M" and Male“) etc were made consistent
There are some missing Customer_ids in the ‘Customer Demographic’ data but in ‘Transactions table’ and ‘Customer Address table’. Only customers in the Customer Demography list is used for the model.
Product_ids having 0 in the transaction table were assigned appropriate ids using Brand, Product specifications and list price.
Inconsistent data type for the same attribute were normalized.

*Data Exploration*:
From the new customer, customers working in Financial services are 24.31%, Manufacturing 23.83% and Health is 18.3% which accounted for about 66% of the customers. Telecommunications and Agriculture acciunted for 6% and are respectively have lowest industry.
Similar pattern was observed in “Old Customers” with the three highest industry accounting for 65% of thecustomers .
Most of the customers are aged between 40-49 in New customers as well as in Old customers.
The new customer list shows that the majority of the customers ages between 20 and 69 while the old customer suggest 20-59years.
In wealth segmentation, Mass Customer category dominates every age group in both old and new customers while the next segment with majority of customer is High net worth.

*Model Development*:
RFM analysis is deployed. This is a marketing technique used to determine which customers are the best to target to increase sales. 
The RFM model (Recency, Frequency and Monetary) is a data driven customer behaviour segmentation technique. It ranks customers according to how recent, how frequent and how much was spent in purchases over a period of time.

 
*Model Results*:
The customers who purchased recently (between the past 50 days) generated more revenue. The customers that visited between 50-100 days generated a good amount of revenue and the customers that haven’t visited a while gave a very low revenue.

The 1000 new customer is categorized to the rank title using the developed model, it was predicted that there are top 229 customers (platinum customers) which would have bought recently, buys often and spent a huge amount of money. These set of people are our target customers.
