# Adidas-Sales-Excel-Dashboard
Data analysis project in Excel containing the following documents:

-Adidas US Sales Dashboard_v.1

-Adidas US Sales Datasets_v.1

The following activities have been carried out during the project:

-Transformation and cleaning

-Descriptive data analysis

-Dashboard

Description of the process (Included in this README file) - Analysis report (Included in this README file)

-Analysis report (Included in this README file).

Process description:


1.A data file called Adidas US Sales Datasets is extracted from Kaggle.com.
2.A pre-analysis is performed and a range of 13 columns and 9648 rows is detected. The columns are as follows: 
- Retailer
- Retailer ID
- Invoice Date
- Region
- State
- City
- Product
- Price per Unit
- Units Sold
- Total Sales
- Operating Profit
- Operating Margin
- Sales Method
3. The data range is converted to a table called ‘sales_data’.
4. Validate the duplicates. To do this we apply a conditional format in the column sale_id. No duplicates are found but to double check we create the column ‘duplicate’ in the table ‘sales_data’. In addition, the page check for duplicates is created to count the duplicate records shown in the created column. This value is 0 and shows that there are no duplicates. If duplicates had been found, the option data>data tools>remove duplicates would have been selected.
5. The numerical format of the columns is converted from customised to numerical accounting in US dollars.
6. Descriptive analysis of the data through pivot tables. Creation of kpi and distributions that have an impact on the business study.
7. Creation of a dynamic dashboard with previously created KPIs and distributions and creation of additional filters through data segmenters.
8. Simulation of the incorporation of additional data to the analysis. To practice updating the dashboard, a data file is generated temporarily after the initial ones with random values and the data of the dynamic tables are updated to check their correct functioning.



 Analysis report:

  ![image](https://github.com/user-attachments/assets/16515589-0ef9-4125-94e7-9f6d43586e6a)



A scorecard has been built for the company Adidas with the aim of analysing the company's sales and operating results in the different states of the USA through the main distributors through which Adidas reaches its customers.
In order to have an in-depth vision of the Adidas business, a series of KPIs, distributions and filters have been designed that allow us to dynamically analyse the data and obtain relevant information for decision making. The components of the scorecard are explained below.

The KPIs are as follows:
1. Total Sales: Calculates the total sum of the company's sales figure.
2. Operating profit: Calculates the sum total of the operating profit of the sales.
3. Operating Margin: Calculates the aggregate operating margin of the total operating profit over the sales figure as a percentage.
4. Units Sold: Calculates the sum total of units sold.
5. Price per Unit: Calculates the average of the prices per unit of the products sold.

The distributions are as follows: 

1. Operating performance by quarter: Time distribution of turnover and operating profit divided by quarter in a line graph.
2. Distribution of total sales and operating profit by distributor: Distribution grouping total sales and operating profit for each distributor in a grouped column chart.
3. Distribution of operating margin by distributor: Distribution that groups the operating margins for each distributor in a column chart. To do this, a new field is created in the pivot table to calculate the margin by dividing the operating profit by the sales figure, so that it calculates a total for each selected row; in this case the distributor.
4. Distribution of units sold by product: Distribution that groups the total units sold for each product in a pie chart.
5. Distribution of opperating margin by sales method: Distribution that groups the total profit margin for distribution channel by means of a circular ring diagram.
6. Distribution of total sales and opperating profit by product: Distribution that groups the total sales and operating profit for each product sold by means of a grouped column chart.
7. Distribution of operating margin by product: Distribution that groups the operating margins for each product in a column chart.

Filters give dynamism to the graph allowing to extend the depth of the analysis from different approaches. The filters are as follows:
1. Month filter: allows filtering by month.
2. Year filter: allows filtering by year.
3. Quarter filter: allows filtering by quarters.
4. Product filter: allows you to filter by product category.
5. Retailer filter: allows filtering by retailer.
6. State filter: allows you to filter by state of the country.

An analysis of sales for the years 2020 and 2021 has been carried out, excluding the data for the year 2022 as they do not represent a true picture of the business but have been used as a practice to add data to the model. The objective of this analysis is to test the information gathering capacity of the tool and the results are shown below:
1. General business analysis

![image](https://github.com/user-attachments/assets/352ad028-9723-4b3d-802b-6500a1b63ee3)




Through the analysis of the main indicators (KPI) of the business, it is detected that the total sales are approximately 900K$ and the operating profit is 332K$, equivalent to an operating margin of 37%. These results are given by a sales volume of 2.5M units sold at an average price per unit of $45. In order to analyse these data in detail, we proceed to analyse the distributions.

2. Temporal analysis of the business

![image](https://github.com/user-attachments/assets/5e0bd656-cba2-4b5b-afe1-d127553e9c10)



The analysis of the development of the operating performance per quarter shows that both the operating profit and the sales figures have followed a similar trend. There is a peak in sales in 2021 and a general upward trend. These data are a practical sample and do not necessarily have a logical explanation, but a hypothesis of a growth in sales can be established. For this purpose, the year 2020 is analysed in depth by selecting this value in the filter and compared with the year 2021.

![image](https://github.com/user-attachments/assets/9e3b1d99-1edb-4094-a1ba-95e2b5ce5927)



During 2020, quarterly sales remain constant at around 50M except for a drop in Q4 to $27K. Viewing the rest of the dashboard shows that of the total units sold seen above (2.5K), only 460K were sold this year. These products were distributed by West Gear, Foot Locker Walmart, Sports Direct and Kohl's with West Gear being the top distributor with a sales figure of $90M. 

![image](https://github.com/user-attachments/assets/198ebb0c-0652-48a1-8e73-8d86e8b5723b)



Comparing the results for 2020 with those for 2021, we detect that from the 1st quarter onwards there is already a leap in sales, reaching up to $150M and increasing to $190M in the 4th quarter. When comparing the distribution of sales by supplier, there are notable variations in the list of distributors and their sales.Foot Locker is currently the top distributor in terms of sales with $177M in turnover.In addition to the general growth in sales, we detect the entry of Amazon as a distributor. 

In addition to the analysis of the distributors, we can see that the sales of Adidas products have grown homogeneously and there are no differences between the types of products sold before and after. We see an increase in all lines of the brand and therefore we can detect that there is an aggregate increase in the brand, without focusing on a particular product line.

With this analysis, seeing a growth in sales in all distributors, going from a turnover of 182M$ in 2020 to 717M$ in 2021, it would be the object of analysis to study the data of the sector and the impact on the marketing campaigns that the company has had in order to be able to give an explanation for this increase in sales.


3. Analysis of distributors

The aim of analysing the distributors is to detect which ones provide the company with the highest sales figures and, in turn, the profitability of selling in each one of them.To do this, we analyse graphs 2 and 3 where we can see the distribution of total sales, operating profit and operating margin for each distributor.

![image](https://github.com/user-attachments/assets/f3f44111-888d-48c5-a02c-63d3e4a8959e)


Analysing sales, we find that West gear is the company that achieves the most sales with a volume of $242m, followed by Foot Locker ($220m) and Sports Direct ($182m). These three distributors are also the ones with which the company obtains the highest operating profit. Analysing the operating margin, we detect a big difference in the margin obtained in the distributor Sports Direct.This distributor achieves a margin of 41% on sales while the rest of the distributors have a margin of between 37% and 35%. Because of this, there is an opportunity to define a strategy to increase the volume of sales in this channel, as it is the most profitable.

4. Product analysis

The objective of the product analysis has a similar approach to the distributor analysis and tries to detect which are the products with which the company achieves the highest turnover and which are the most profitable for the company. For this purpose, graphs 4, 6 and 7 are analysed; distribution of units sold, sales, operating profit and operating margin.
![image](https://github.com/user-attachments/assets/1da6b3be-5249-445c-b444-3578667b617c) ![image](https://github.com/user-attachments/assets/0e3e91e8-6bf0-4628-a580-4ec544db3229)


The study of these graphs shows that product sales are distributed in percentage terms between 24% in men's casual footwear and 12% in men's clothing. Therefore, there are slight variations in product demand. Analysing turnover, it can be seen that the order of units sold is not the same as that of turnover. 
Women's clothing has the second largest turnover with 180M$ while in units sold it is in third place. As for profitability, it ranges between 34% and 40%, so it is high.It is also detected that men's casual footwear is the most profitable for the company (40%), so being the most sold product, it is the main product. However, there is an opportunity for growth in women's sports footwear as it also has a high profitability (37%) and sales (106K$) do not materialise in the same way as women's clothing (179K$).

It is therefore recommended to invest in promoting the sale of men's casual footwear and women's clothing and to explore ways to increase the sale of women's sports footwear due to its profitability.

5. Analysis of distribution channels
The study of the distribution channel shows the way in which the company delivers the product to the customer. The objective is to detect which are the most popular for customers and which are the most profitable for the company. Distribution of the margin by sales method combined with the rest of the general kpi by using filters.

![image](https://github.com/user-attachments/assets/ec0f51a4-158a-40a4-8358-923f38edca8a)

The analysis of this graph shows that there is a certain relevance between online sales and the rest, as the margin of online sales is 39% and outlet and in-store sales are 36-37%. Using the filters we detect that online sales have a turnover of 247M$, outlet sales have a turnover of 295M$ and in-store sales have a turnover of 356M$. Based on these results, it is recommended to encourage online sales.


The following conclusions are drawn from the analysis: 
1.Adidas sales are on an upward trend across all distributors and product lines and an analysis is recommended to explain the cause of this growth. The proposed lines of analysis are the evolution of the sector and the impact of marketing campaigns.

2. Due to the 41% margin that the company obtains through the distributor Sports direct, it is recommended to design a strategy to increase sales through this company.

3. It is recommended to invest in the promotion of men's casual footwear, women's clothing and it is also recommended to define a strategy to increase sales of women's sports footwear.

4. It is recommended to implement an e-commerce strategy that positions the online distribution channel as the main source of income due to its 39% profitability.



  
  
