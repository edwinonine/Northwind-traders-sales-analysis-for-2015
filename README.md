# Northwind-traders-sales-analysis-for-2015
![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/Northwind.PNG)

## Introduction
This is a power bi project on northwind traders. The project is carried out to review, analyze and derive insight to answer crucial questions and help the northwind traders make data driven decision.

## Problem statement
Northwind Traders, a company known for distributing gourmet food products, wants to make its operations better and decisions smarter in the 2nd half of 2015. To achieve this, the company plans to study its sales data, how customers behave, and how well its products are doing with emphasis on the 1st half of 2015. By doing this, Northwind Traders hopes to find important insights and ways to grow even more.
In their analysis, Northwind Traders wants to look closely at sales trends, how customers buy things, and which products are selling well based on what was achieved in the 1st half of 2015. 
They believe that by understanding these things better, they can make smarter choices about what to sell and how to sell it. This means they can make sure they have the right products in stock and keep their customers happy.
Northwind Traders knows that using data to make decisions is important. They want to use this information to find ways to make their business better and keep up with what their customers want.
Below are som of the business questions they need to find answers:
1. What makes customers keep coming back, and how can Northwind Traders use this to get more loyal customers?
2. Are there certain products that are selling faster than others, and how can Northwind Traders make sure they always have enough of these in stock?
3. Do different types of customers buy different things, and how can Northwind Traders use this information to offer products that people want?

## Skills demonstrated
In carrying out the analysis certain skiils were demonstrated in analyzing and deriving insights. This skills includes checking for data quality, data cleaning and transformation using power query in dealing with missing values and duplicate values, data modelling which was used in creating relationships between the datasets, and performing dax functions (creating calculated fields and columns) to derive more insights during the coure of analysis.

## Data sourcing
I had to task myself to review, analyze and create visuals for a dataset obtained on google drive which was provide by data-nex instructor. the dataset is about of northwind traders. The reason for the analysis is to understand sales trends, how customers buy things, and which products are selling well based on what was achieved in the 1st half of 2015. the following were the datasets used for the analysis: categories.csv, customers.csv, employees.csv, order_details.csv, order.csv, product.csv, and shippers.csv.


## Data transformation and data cleaning
In ensuring quality and reliability of the dataset. Columns were checked for duplicates, checked for inconsistencies, errors, and inaccuracies, blank cells and outliers within the dataset. The following were keys steps used in ensuring the dataset was ready for analysis.
1. Data quality
2. Data integrity
3. Check for duplicate values
4. Check for missing values
5. Conditional formatting
6. Data modelling
7. Application of dax functions (calculated fields and new columns)

## Data cleaning process
After reviewing the datasets, it was discovered that the employees dataset has blank cells (null value), other datasets has duplicate values which was necessary i checked for data quality of all the datasets provided. the data cleaning process was done using power query.

### Image 1
The screenshots below show the data cleaning process before proper analysis was done.

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/Capture.PNG)
![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/actual%20null%20change.PNG)
![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/Null%20values%20data%20entry.PNG)

## Data modelling
In the course of the analysis in other to derive insights in answering the business questions.the datasets were modelled thereby creating relationships in order to derive more insights.
the image below shows the relationships of the necessary datasets that were required in answering the business questions.

### image 2

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/modelling.PNG)

## Analyzing and visualization
In answering the business questions, i carried out descriptive analysis in order to understand the datasets after data modelling was done. The following were insights derived for the first quarter in 2015: 
1. Revenue (sales) for 2015 was $441,000
2. The average revenue(sales) was $63800
3. Total quantity was 16000
4. Total order 270000
5. Total customer 81

## Actual Analysis
After carrying out descriptive analysis, i divided the analysis into two major segments/parts, the first one majorly focuses on the sales (revenue) generated during the first quarter in 2015 some of the key performance indicators (kpi's) i used were as follows: Top 10 order by country, quantity order by month, revenue generated by month, Top 10 revenue by products, and lastly order by category. while The other analysis focuses majorly on product performances using total sales, order amd total quantity as key metrixs in deriving insights.

## finding 1:
The first analysis, i had to investigate into orders by country for 2015. during the analysis i had to trim the result into top 10 of order by country to gain more insights, it was discovered that the united states of america ranked highest with a total order of 39, while venezuela ranked second with an order of 18 and United kingdom ranked third with a total order of 16 quantities. However, is was discovered that poland with 4 quantities, norway with 3 quantities and portugal with 2 quantities ranked lowest in the order by country pecking order.

## Image
The screenshot below depicts the top 10 order by country in 2015.

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/orderbycountry.PNG)


## finding 2:
the second analysis focuses on revenue by category. its discovered that within the different categories of product in which northwind traders are into. beverages ranked the highest in terms of revenue with a total of $116,000, while daily products ranked as the second with a total of $75,000 and confections ranked as third with a total of $55,000. furthermore, other categories which ranked lowest in terms of revenue were as follows: condiments with a revenue of $33,000, produce $31,000 and grains and cereal with $29,000.

## Image

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/revenuebycategory.PNG)

## finding 3:
The third analysis focuses on top 10 revenue by products. several results were obtained however, i had to reduce it to just top 10. it was discovered that thuringer Rostbratwurst ranked highest with a revenue of $33,700, while uncle bob organic dried pears with a revenue of $12,300 and Wimmers gut with arevenue of $10700. i decided to look into the lowest ranked product by category, its was also discovered that Valkoinen suklaa with a revenue of $9,000, tourtierre witha revenue of $7,000 and Tofu witha revenue of $4,000.

## Image
![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/revenuebyproduct.PNG)

## finding 4:
The fourth analysis focuses on order by category. insights obtained show that beverages ranked as the highest category with a total order of 128 quantities made by customers, while sea foods ranked second with a total order of 101 and daily products rank third with a total order of 90 quantities respectively. However, other categories that ranked lowest based on orders were as follows grains and cereal with a total order of 55, meat and poultry with a total order of 43 and produce with a total order of 42.

## Image
![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/orderbycategory.PNG)

## finding 5:
The fifth analysis, ths analysis focuses on a trend analysis based on order by month. insights obtained, the month of April 2025 had the highest order made with 74 quantities, while march has the second highest order by month with a total order of 73 quantities, January has the third highest order with a total quantities of 55 quantities, and February ranked as fourth with a total order of 54 quantities. However, from the analysis i discovered that northwind traders experienced a decline in orders made by customer for the month of may with a total order of 14 quantities.

## Image 
![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/orderbymonth.PNG)

## Report
## Image
Below is the screenshot of the final report on sales trends for 2015.

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/report.PNG)

## Product Performance
## Image
Below is the screenshot showing the product performance for 2015

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/reportPNG.PNG)

I had to carry out a correlation analysis with total sales (revenue), quantity and total order to see if there are any relationship that exist between the variables, from my analysis it was perfect negative relationship.

![](https://github.com/edwinonine/Northwind-traders-sales-analysis-for-2015/blob/main/correlation.PNG)

## Actions and Recommendations

1. In answering the question one (1), factors that would make customers to comeback for more are for northwind to understand what aspect of their brand are worthy of customer loyalty. identify what makes their brand unique and how their values align with their customer's core belief. craft a marketing strategy that highlights these unique attributes and communicates your purpose effectively.However, i strongly suggest that northwind traders should do the following: encourage satisfied customers to become brand advocates. word-of-month recommodations from loyal customers can significantly impact the business, create a well-structured loyalty program that rewards repeats purchases. offer incentives such a discounts, exclusive access, or points-based systems and Build meaningful relationship with your customers.
2. In answering question two (2), northwind traders should do the following: regularly seek feedback from their customers. understand their choice of purchase and preferences, act on their feedback to enhance their products, services, and overall customer experience. However, in ensuring that those products that remain regularly in stock, anticipate customer demand by analyzing historical sales data, seasonal trends and market fluctuations and regularly monitor inventory levels and replenish products before they run out.
3. Finally, in answering question three (3), northwind traders should focus on collecting customer feedback after purchase. understand why customers chose specific products. use the this feedback to improve existing offerings or develop new ones that align with customer preference and use use predictive models to forecast future purchase. Analyze historical data to predict which products a customer might buy next.
 
