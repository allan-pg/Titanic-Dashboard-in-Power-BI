# Titanic Dashboard in Power-BI
![image](https://github.com/user-attachments/assets/4918622f-e532-4878-bd09-3784c6c8c278)

## Introduction
Titanic Dataset can be downloaded from <a href="https://www.kaggle.com/datasets/brendan45774/test-file">Kaggle</a>  
It has 1309 rows and 10 columns  

## Tools Used
- Power BI
- Power Query
- Data Modelling
  
## Data Cleaning
- Most of the data had no issues
- I dropped columns which i did not intend to use in my dashboard
  ***Null Values***
- Two rows had null values from embarked column in the titanic dataset
- I dropped the rows since that could not have any impact on our Analysis
   
## BUSINESS REQUIREMENTS
Conduct a comprehensive analysis of Titanic Dataset to identify trends and patterns using Power BI.  

## KPI’s Requirements
1. Total Number of Passengers
   - Objective: Analyze how many passengers were on board 
2. Total Sum of Fare Paid
   - Objective: Find how much passengers paid as fare
3. Average Fare
   - Objective: Find the mean Fare paid by passengers
4. Average age
   - Objective: Find mean age of passengers

## Charts Requirements
1. Total Number of Passengers in terms of gender
   - Objective : Analyze passengers were on board in terms of gender
   - Chart type : Donut chart
2. Total number of survivors in terms of gender
   - Objective : Analyze passengers survived in terms of gender
   - Chart type : Donut chart
3. Passengers on board per class
   - Objective : Analyze passengers on board per class
   - Chart type : Donut chart
4. Number of Passengers by age on board vs Number of Passengers by age that survived
   - Objective : Analyze passengers on board by age
   - Chart type : Line Chart
5. Number of Passengers who died vs who survived per class
   - Objective : Analyze passengers on board per class who survived vs died
   - Chart type : Bar Chart
6. Distribution of Passengers embarked per town
   - Objective : Analyze number of passengers embarked in each town
   - Chart Type : Bar chat

# Findings
1. Passengers on board were 1307
   - Male Passengers were 843 and were the most
   - 464 Passengers were Female
2. Total Fare spent by passengers was $43,400
3. Average fare was approximately $33
4. Most Passengers were 29 years old since its our mean age for passengers
5. Less than half of our passengers on Board survived
   - In our business class most the passengers survived compared to other flight class
   - In the economy most passengers did not survive
6. Passengers aged 29 most of them died since they were majority
7. Most Passengers embarked at southampton who were 914
   - Very few Passengers embarked at queenstown 
