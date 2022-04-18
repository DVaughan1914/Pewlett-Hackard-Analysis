# Pewlett-Hackard-Analysis

The analysis should contain the following:

## Overview of the analysis: Explain the purpose of this analysis.
Pwelett-Hackard is a large company that want to determine  the number of retiring employees per title, and also indentify the employees who are eligible to participate in a mentorship program.
## Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
  ## Analysis 1 and 2: 
      -This analysis was aimed at identifying employees up for retirement based on their titles.
      -We realized that there were some duplicate entries(names) in our query because some employees changed titles over the years.
      <img width="780" alt="retirement_titles_1" src="https://user-images.githubusercontent.com/100040621/163737746-557878ee-71f3-41f4-80e9-5b2c202e4f67.png">

      -Had to use the "DISTINCT" statement to retrieve the first occurence of the employee number as a result
      ![unique_titles1](https://user-images.githubusercontent.com/100040621/163737767-c7890a2b-d3ca-4cec-a386-efbe25621270.png)

      -We also had to account for the employees that have already left the company, so we filtered on the from and to dates of employment
      - So with those filters we were able to create a table of unique titles for the employees who are up for retirement.
      ![count_employees_retiring](https://user-images.githubusercontent.com/100040621/163737792-fe36ac95-da8f-4140-a35b-c6ed9fd14e90.png)

      -Then we wanted to find the number of employees based on their, so table below shows the number of employees retiring.

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
## How many roles will need to be filled as the "silver tsunami" begins to make an impact?
-According to the data and the count from the retirement title count table, there are 72,458 employees that are of retirement eligibility. That brakes down to:
  -25,916 Senior Engineers, 24,926 Senior Staff, 9,285 Engineers , 7,636 Staff, 3,603 Technique leaders, 1,090 Assistant Engineer, and 2 managers. So those are the roles that would be needed when the silver tsunami takes effect.
## 2 queries
    - To add some more meaning or answers some questions there can also be a query on the employees that qualifies for the mentorship program to filter by titles and count the titles for each position to show a break down of titles to compare to the count of retirement titles. This will show how exact distribution of titles to be mentored by the outgoing staff.
    -Also a query that shows the approxmate time frame when the employee is retiring based on years of employment and or birth date.
## Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
- From the data and queries there are 1550 employees eligible for the mentorship programs and there are approximately 70,000 employees in various positions that are eligible for retirement can provide mentorship in the program.
