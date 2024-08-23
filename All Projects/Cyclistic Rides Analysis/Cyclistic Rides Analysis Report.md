# Cyclistic Rides Analysis Project

## Introduction

Cyclistic is a company in Chicago that offers trips to customers daily. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, the purpose of this project is to understand how casual riders and annual members use Cyclistic bikes differently. This will help design a new marketing strategy to convert casual riders into annual members.

## Problem
The major problem is that Cyclistic wants more customers to sign up for membership instead of being casual riders. 

As a junior data analyst working with the marketing analyst team at Cyclistic, the director of marketing and my manager have asked me to answer the question: **How do annual members and casual riders use Cyclistic bikes differently?**

Answering the above question will help the marketing team identify the reasons why casual riders do not sign up for membership. It will also help propose new strategies to motivate casual riders to sign up for membership.

## Project Aim
Design marketing strategies aimed at converting Cyclistic’s casual riders into annual members. 

This report will follow a roadmap to highlight the following deliverables:
1.	A clear statement of the business task 
2.	A description of all data sources used 
3.	Documentation of any cleaning or manipulation of data 
4.	A summary of my analysis 
5.	Supporting visualizations and key findings
6.	My top three recommendations based on my analysis
   
## Business Task

**Objective**: Convert Cyclistic’s casual riders into annual members.

**Scope**: Use data analytics to identify:
*	Key factors that prevent casual riders from becoming annual members.
* Factors that will make casual riders interested in becoming annual members.
*	Patterns in riders' behaviors and product performance.
*	Opportunities to increase Cyclistic customer satisfaction.

**Key Questions**
*	What is the problem I am trying to solve?
*	How can my insights drive business decisions?
*	What are the common characteristics of annual members?
  
**Expected Outcomes**
*	A detailed report highlighting actionable insights.
*	Recommendations for targeted marketing strategies.
*	A dashboard providing real-time customer data.
  
**Success Metrics**
*	Increase in Cyclistic riders.
*	Increase in Cyclistic annual memberships.
*	Conversion of many casual riders to annual members.

### 1. Data Acquisition and Preparation
*	I used the data of Cyclistic trip data made available by Motivate International Inc. 
*	Data for the first quarter of 2019 was downloaded for the Cyclistic trip data.  

### 2.	Data Cleaning and Processing
I chose **Excel** to clean the data because it is easy to use and the dataset is not large.  The following steps were performed:
*	I sorted and filtered data to remove unnecessary and inaccurate data. 
*	I removed duplicate
*	I removed blanks or rows with empty cells to ensure the remaining data could be used.
*	Fixed rows and columns by verifying that columns with numbers were all numbers by converting text in some cells into numbers.
*	Checked the data for errors.
*	Ensured that each field had the appropriate data type by performing some conversions where needed. 
*	The raw data were transformed and changed into a standard data format suitable for analysis, storage, and easy use.

### 3.	Data Analysis and Visualization
*  The following calculations were performed in individual files first such as:
  * Mean of ride_length: =AVERAGE(D2:D32767), this gave **0:14:55**
  * Max of ride_length: =MAX(D2:D32767), this gave **232:09:59**
  * Mode of day_of_week: =MODE(E2:E32767), this gave **5**
     
*	A pivot table was created to quickly calculate and visualize the data.
  * I calculated the *average ride_length* for members and casual riders by adding *member_casual* under *Rows* and *ride_length* under *Values* and selecting *Average* from the *Values Field Settings*.
  * I calculated the *average ride_length* for users by *day_of_week* by adding *day_of_week* under *Columns*, *member_casual* under *Rows*, and *Average* of *ride_length* under *Values*
  * I calculated the *number of rides* for users by *day_of_week* by adding *Count of ride_id* to *Values*.

*	Performing these descriptive analysis steps helped make some initial observations such as, the day with the most rides is *Thursday*. The table below was designed to show the difference between both years 2019 and 2020.
Table 1: Total number of rides and average ride length for both casual riders and members – First Quarter of 2019.

|      Year     |      2019     |
| :-------------: | :-------------: |
| Total Rides          |            345357          |
| Average Ride Length  |            0:14:15         |

* Level 1
  * Level 2
    * Level 3
      * Level 4
        * Level 5
          * Level 6
            * Level 7
              * Level 8




## Author
[Edwige Songong](https://github.com/Songonge)

