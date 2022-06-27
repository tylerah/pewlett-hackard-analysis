# Analysis of Pewlett-Hackard Retiring Employees Using SQL Queries
## Overview
The purpose of this project was to identify the number of retiring employees as per their given job title and to identify which employees are eligible to participate in a mentorship program. Hewlett-Packard had csv files containing all of the relevant information, but did not have a relational database set up. As such, the first step to obtaining the relevant information was to establish a database linking all of their employee data. Afterwards, SQL queries were utilized to make lists/tables of information requested 
## Results
### Links to Requested Data
The SQL queries used to obtain the requested information can be viewed here:https://github.com/tylerah/pewlett-hackard-analysis/blob/main/queries/Employee_Database_challenge.sql

A table that shows the number of retiring employees by position/title can be viewed here: https://github.com/tylerah/pewlett-hackard-analysis/blob/main/data/retiring_titles.csv

A table that shows the employees who are eligible for the mentorship program can be viewed here: https://github.com/tylerah/pewlett-hackard-analysis/blob/main/data/mentorship_eligibility.csv

### Key Takeaways
An analysis of the obtained tables reveals four key takeaways:
  1. There are 72,458 employees retiring. Of these, roughly 35% are Senior Engineers and 34% are Senior Staff
  2. Pewlett-Hackard will need to prioritize filling their senior positions whether through new hires or internal promotion
  3. There only 1,549 employees that qualify for the mentorship program
  4. The number of potential mentors is far less than the number of people retiring

## Summary
Several more queries/tables can be created in order to mitigate the impact of the "silver tsunami" on Pewlett-Hackard. The original query has created a list of individuals born between 1952 and 1955. Assuming that most people will retire at age 65, another table can be created to separate these individuals by age. This information will further identify how many positions will be retiring and need to be filled each year. This allows Pewlett-Hackard to plan more efficiently on what positions and how many actually need to be hired each year. Additionally, as the original query revealed that many senior positions will be retiring in the next few years, several other queries could be performed to identify how many potential employees could be promoted internally to fill those positions. Such queries could filter the list of potential employees by how much time they have spent at Pewlett-Hackard so that the senior positions could be filled by people who have spent enough time at the company such that management feels confident that internal hires/promotions are up to date on the current projects teh company is working on.

In addition to queries/tables related to the positions of these retiring, it will be important for Pewlett-Hackard to gather more data on potential mentors. The original query only identified employees that would be eligible to be mentors, however, it did not provide information on what positions these employees held. Before creating a mentorship program, it would be useful to know how potential mentors there are in each job category. As it stands, it would seem that there are not enough retirees to mentor the next generation of employees as only 1,549 employees were marked as eligible. As such, it may be worth running a query to identify how long all current employees have been in a given position. It is possible that there are employees that have spent significant time in a given position even though they are not yet nearing retirement. Such employees could also prove to be effective mentor and lighten the load for all potential mentors. 
