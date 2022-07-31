# Pewlett Hackard Analysis

## **Overview of Project**

The purpose of this analysis is to conduct a Database analysis for Pewlett Hackard with detailed information on the number of future retirees from all departments currently working at the company to be able to prepare a plan to hire new staff and also to prepare a mentorship initiative. 

The criterion was based on the birth dates ranging from 1952 to 1955 and hired dates from 1985 to 1988.


## Results

- Below is the ERD (Entity Relationship Diagram) used to visualize the relationship between the data sources and the structure of the company's employee plan to facilitate the analysis. 

	![alt text](https://github.com/sbellorin/Pewlett-Hackard-Analysis/blob/83a559f8a835e28e97d0f4bcce6343d661e7dbf0/employeedb.png "Employee DB")

### Mentorship Candidates

- Below is the list of candidates that can qualify to become members of the mentorship program, they can be referenced as "senior" employees amongst the general staff. 

	![alt text](https://github.com/sbellorin/Pewlett-Hackard-Analysis/blob/83a559f8a835e28e97d0f4bcce6343d661e7dbf0/queries/Mentorship%20Eligibility.png "Mentorship Candidates")
	
- After creating the unique_titles table by joining the employees and titles tables, filtering them by date of birth and date hired, removing duplicates, and ordering the data points by date hired there are **90,398 employees retiring** as per the above criterion. 
	
	![alt text](https://github.com/sbellorin/Pewlett-Hackard-Analysis/blob/35987049a2452d9ca96442cd0563304ee923e446/queries/unique.png "Unique Titles")
	

## Summary

Seeing the 64% of the workforce is either retirment or mentorship eligible there will most likely be many positions to fill over the next 5-10 years. There may not exactly be enough people in the workforce to take care of the tasks or even come close to the amount of experience to fill these roles so quickly but what companies can do is try to best learn about what these employees did to be so successful/ having such long lasting careers to continue the tradition for future employees. Most likely the future generation is more computer savy/ efficent due to technologies and can catch on quickly helping companies continue to trend in the right direction by keeping revenues up.
