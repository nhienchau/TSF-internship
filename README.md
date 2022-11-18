# The Sparks Foundation Internship 
## 🔅 Task 3: Exploratory Data Analysis - Rtail Analysis (Level - Beginer)
1. Perform ‘Exploratory Data Analysis’ on dataset ‘SampleSuperstore’
2. As a business manager, try to find out the weak areas where you can work to make more profit.
3. What all business problems you can derive by exploring the data?
4. Dataset can be found at: https://bit.ly/3i4rbWl
---
## 🔓 Steps
1. Use SQL in Oracle environment to exploratory the dataset

👉 **Total rows of the dataset**

`SELECT COUNT(*) AS TOTAL_ROWS
    FROM SUPERSTORE;`
    
👉 **Top 10 cities have highest sales**

`SELECT CITY, SALES, SUM(SALES) 
FROM SUPERSTORE
GROUP BY SUM(SALES) DESC
FETCH FIRST 10 ROWS ONLY; `

👉**Profit by region**

`SELECT REGION, SUM(PROFIT) FROM SUPERSTORE GROUP BY REGION ORDER BY SUM(PROFIT) DESC;`

2. Find out the weak areas where the company can work to earn more profit by building a dashboard

👉 **Using Power BI to create a dashborad** 

<img align="center" alt="Gif" width="350px" style="padding-right:150px;" src="https://user-images.githubusercontent.com/108797740/202766711-60f4c641-e9ac-4350-8b06-a4b17cfb9418.gif"/>
👇 For more dashboard information in detail

https://app.powerbi.com/links/BDpn537UKQ?ctid=40127cd4-45f3-49a3-b05d-315a43a9f033&pbi_source=linkShare
