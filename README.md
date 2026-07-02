# Marketing-Data-SQL-Data-Analysis
Analyzing customer demographics and wine purchasing behavior using SQLite.
# Project Overview
-The goal of this project is to evaluate how customers demographics influence retail wine purchasing patterns to determine an ideal target 
audience and maximize efficiency. 

# SQL Demographic Analysis
-The customer database was queried using SQLiteStudio to group household metrics based on family size:

''Sql
SELECT FamilySize, 
       AVG(Income) AS Avg_Income, 
       AVG(MntWines) AS Avg_Wine_Spend,
       COUNT(Age) AS Total_Customers
FROM marketing_data
GROUP BY FamilySize;


<img width="1351" height="586" alt="image" src="https://github.com/user-attachments/assets/844b2a9e-9635-41d9-ba59-2be72269b840" />

                          #Data Findings (Single and dependent households)  
                                             
Conclusion: Households with family size 0 (Single) are able to afford to spend more on wine than households with dependents.Singleconsumers spend an average of $487.65 on wine which is more than larger families

Income: The number of members in a household determines the amount spent on wine. Smaller households correlate with significantly higher average disposable of $65,677.36 for a single household.


                                             
