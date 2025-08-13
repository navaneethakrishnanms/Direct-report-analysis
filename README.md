# Direct-report-analysis
Dataset Columns:
employee_id → Unique employee ID


position → Job title of the employee


managers_id → Employee ID of the manager (NULL if top-level)

#Part 1 – Basic Data Understanding (Pandas)
Load the CSV file into a Pandas DataFrame.


Display the first 10 rows of data.


Show the shape, column names, and data types.


Check for missing values and duplicates.


Use .describe() to get summary statistics for numeric columns.

#Part 2 – EDA (Exploratory Data Analysis)
Find all employees who have "Manager" in their job title.


Count how many direct reports each Manager has.


Identify the Manager with the most direct reports.


Create a bar chart showing Manager vs. Number of Direct Reports.


Create a network-style plot showing Manager–Employee relationships (optional advanced visualization).

#Part 3 – Statistics
Calculate the average number of direct reports per Manager.


Find the median and mode of direct reports count.


Probability: Pick a random employee — what is the probability that they report directly to the CTO?

#Part 4 – Linear Algebra & NumPy
Represent the number of direct reports as a NumPy array.


Create a constant weight vector to simulate Manager Influence Score.


Perform vector addition & subtraction on these arrays.


Compute the dot product between direct reports and influence score.


Perform a weighted sum (matrix multiplication) to get manager impact values.

#Part 5 – Calculus
Assume a model:

 java
CopyEdit
Productivity Score = (Direct_Reports * Efficiency_Factor) / Manager_Experience
 Find the derivative of Productivity Score with respect to Direct_Reports using SymPy.


Interpret the derivative.

#Part 6 – Feature Engineering
Create a new column Direct_Reports_Count for each Manager.


Create Is_Manager column (1 if “Manager” in title, else 0).


Create High_Team_Size column (1 if Direct_Reports_Count above average, else 0).


Create a ranking of Managers based on number of direct reports.

#Part 7 – SQL Simulation in Pandas
Find all Managers who have more than 3 direct reports.
Sort Managers by number of direct reports (desc) and employee_id (asc).Get the total number of employees per Manager (including indirect reports — optional challenge).

#Part 8 – Insights
Which Manager has the largest team?


What is the average team size for Managers?


Which Managers have below-average team size?


Is there any correlation between Manager title type (e.g., “Data Science Manager” vs “Data Engineering Manager”) and team size?

