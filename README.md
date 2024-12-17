This project is a recap of my learning about data analyst at Udemy. 
This project aims to find out customer shopping behavior and also conduct RFM analysis. 
with stages of data cleaning, EDA, and data visualization using python and jupyter notebook.


1.	Data cleaning
    To make the collected data more accurate, data cleansing is required.
  	Three components of this data—completeness, consistency, and uniqueness—need to be cleansed.
  	
> Missing values

The income and city variables are the only two that have null values.



![missing values](https://github.com/user-attachments/assets/54c85e46-8408-44b3-a4de-a5c8b8235fd9)

> inconsistent data

The variable 'Customer_Lifespan_Month' contains a value xxxx that is inconsistent or does not match other values.


![inconsistency](https://github.com/user-attachments/assets/932d0ab1-3cf7-4f85-9dfe-882970382f5c)

> duplicates value

One row of the data has similarities.


![duplicat](https://github.com/user-attachments/assets/7dd71559-ba4b-4b37-912f-2a25321ec16b)     


2.	EDA

  	Exploratory Data Analysis, or EDA for short, is the next step after data cleaning.
  	Finding patterns, testing theories, forming assumptions, and spotting irregularities in the data are the goals of this phase.
	
> Purchase channel percentage

A pattern of consumer behavior about product purchases through online and in-store/offline retailers was derived from the data.
The findings indicate that compared to in-store purchases, online store purchases are higher.

![p1](https://github.com/user-attachments/assets/6e88589c-8986-4196-bce1-a5bae852c8ab)

> Total average purchase amount by city

When compared to the other three cities, Houston has the most purchases among the cities in the data.

 ![p2](https://github.com/user-attachments/assets/e3c83f56-0724-4c15-9de1-c9ca8dcf2714)

> Total RFM by churn status

Based on the RFM factors—Recency, Frequency, and Monetary—it can be inferred from the following table
that there are more clients who unsubscribe than remaining.

![p3](https://github.com/user-attachments/assets/d44b3da6-b5b7-4173-8474-3f1f7005e944)

> Churn status by city

Additionally, compared to other countries, Los Angeles has a larger percentage of clients who discontinue their subscriptions.

![p4](https://github.com/user-attachments/assets/7b2091b1-fa7f-4b75-988e-9d2513575f90)

> The relationship between average purchase amount and frequency of purchases

The two are positively correlated, meaning that customers' purchases increase with the frequency of their purchases.

> Statistic average purchase amount

The average purchasing amount yielded a statistical value of:

 Min : 37
 
 Q1 : 76
 
 Median : 97
 
 Q2 : 120
 
 Max : 163
 
 Outlier : 193 

3.	Data visualization
Hasil visualisasi dari EDA

> Percenatge of purchase channel
![g1](https://github.com/user-attachments/assets/bbe06bc0-5be5-45a1-baa1-04c219b5d0e9)

> Average purchase amount by cities
![g2](https://github.com/user-attachments/assets/115059bf-febc-4019-83bc-2d6e2fe7f5b0)

>  Customer churned by cities
![g4](https://github.com/user-attachments/assets/eabaf1f2-eb9a-472c-a504-9e096ceb87f8)

> Relationship between frequency purchase and average purchase amount
![g5](https://github.com/user-attachments/assets/c4d01532-6e35-42a2-9a2d-6422788ff6e7)

> Boxplot average purchase amount
![g6](https://github.com/user-attachments/assets/1457804a-362c-4ffb-bac9-9b15d2de4e70)

> Correlation matrix
![g7](https://github.com/user-attachments/assets/fd55e942-7ec9-4e5d-96b4-7f29c7fba9c4)

