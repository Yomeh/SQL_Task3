# SQL_Task3
# Intoduction
In the third session of the SQL section, I learned about using the **AGGREGATE** FUNCTIONS, **GROUP BY** clause, and **HAVING** statements. These statements perform specific functions retrieving values from rows after meeting a specific condition, specifying multiple conditions, etc.

# Skill Demonstrated
- Data Retrieval

# Objectives
- From the employee table, retrieve the total number of employees.
- Find the top 5 cities with the highest number of employees and filter for cities with more than 15 employees.
- Find the pincode used the most by employees.

# Methodology

**1**
![Screenshot (50)](https://github.com/Yomeh/SQL_Task3/assets/140501792/34f9aa20-5a36-4eac-af0a-f7dd13cfddb5)
To retrieve the number of employees, I used the **COUNT** function to count the number of values in the Entire column and then named it using the **AS** operator. The number of employees is *100*

**2**
![Screenshot (51)](https://github.com/Yomeh/SQL_Task3/assets/140501792/cb58737a-ba95-4642-ad99-5ccb3d551bb4)
To get the top 5 cities with the highest number of employees, I used the **TOP** function to narrow down the selection and used the **COUNT** function to count the *empID* column to get the number of employees in each city and to get the cities with more than 15 employees i used the **GROUP BY** and **HAVING** function to only display the cities where the total number of employee is more than 15. These cities include; **Mumbai**, **Delhi** and **Pune**

**3**
![Screenshot (52)](https://github.com/Yomeh/SQL_Task3/assets/140501792/02934f41-09bd-450c-8432-ae617881cd3e)
To get the pincode used the most by employees, I used the **COUNT** function to get the count of the pincode, then i used the **GROUP BY** function to group the count of the pincode into the number of uses and the pincode used the most was **410210**

