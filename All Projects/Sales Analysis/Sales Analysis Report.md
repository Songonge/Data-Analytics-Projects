# Project: Sales Analysis in some Cities in the United States

## Introduction
This project about Sales Analysis is one of the projects offered by MeriSKILL as part of an internship. The project is focused on data analytics and is carefully planned to reveal patterns and insights hidden in complex datasets. I will be using Power BI to facilitate the extraction of critical insights.

## Project Aim
Deep dive into sales data with the aim of extracting valuable insights to enhance strategic decision-making. This will involve analyzing sales data to identify trends, top-selling products, and revenue metrics for business decision-making.    

## Project Description
In this project, I will dive into a large sales dataset to extract valuable insights. To properly convey my findings, I will calculate revenue indicators like total sales and profit margins, analyze sales patterns over time, determine the best-selling products, and produce visualizations. This project demonstrates my capacity to work with and extract meaning from huge datasets, allowing me to provide data-driven recommendations for improving sales strategies. 

The following bullets list the insights I derive through my data analysis process:
*	What are the best-selling products?  
*	What are the top five cities with the highest sales in 2019?
*	How much profit was made in 2019?
*	What are the top five products based on sales?
*	Which day of the week and which month have major sales?
  
Here is what I did:

### 1.	Data Acquisition and Preparation
MeriSKILL provided data. I downloaded the dataset from Google Drive. Then, I uploaded it in Power BI using the Get Data option. This dataset was unclean and had 10 columns in total. The data were recorded for the year 2019.

### 2.	Data Transformation and Cleaning
The first row of the data was used as headers using the option Use First Row as Headers under the Home tab. Then, using the Transform tab, I selected Detect Data Type to automatically identify the data type of each column and convert them where needed.
* Next, I split the fourth column named Order Date into date and time stamps. I
  * selected the column named Order Date. 
  * Then, I chose the Split Column option and selected the space as the delimiter.
  * Next, I selected Each occurrence of the delimiter. Then I pressed OK.

*	To proceed, I created a column named Day to extract days of the week from the date column.
*	I also performed some calculations by using the New measure option:
  * The total cost using the formula: Total cost = SUM('Sales Data'[Price Each])
  * The profit margin using the formula: Profit Margin = ([Total Sales]-[Total Cost])/[Total Sales])*100
  * The total sales using the formula: Total Sales = SUM('Sales Data'[Sales])
    
### 3.	Data Analysis and Visualization
In Power BI, I used Visualizations to create a dashboard as shown in Figure 1. I used a
*	Line chart to represent sales trend over the year, 
*	Stacked column chart to display weekly sales for each day, 
*	Treemap to show the best-selling products, 
*	Stacked bar chart to identify the top 5 best-selling products, 
*	Map to show the top 5 cities by sales, 
*	Cards to display the sum of all sales, the total sales quantity, and the profit margin. The "Format" option for the visual was used to adjust the callout value to change the display unit of the quantity ordered as desired.
*	My charts were assembled and made interactive through the use of Slicers to display cities, months, days, and products.  
