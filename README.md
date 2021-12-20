# Pewlett-Hackard-Analysis

## Overview of the analysis
Now that Bobby has proven his SQL chops, his manager has given both of us two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, we’ll write a report that summarizes our analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

## Results
We made a table with all of the current workers' titles who were born between January 1, 1952, and December 31, 1955. Our table contains the most recent titles of each employee. We built another database that contains current workers born between January 1, 1965, and December 31, 1965, in order to assess who is qualified to engage in a mentoring program.
### The Number of Retiring Employees by Title
- Our first table has detailed information on all retiring workers, including titles from the beginning to the end, employee numbers, and first and last names.

![retirement_titles](https://user-images.githubusercontent.com/91230277/146698233-816803cd-818a-4d44-b970-1a3927848ee0.png)

- Our next table has unique title data, which means it contains each employee's most recent job title.

![unique_titles](https://user-images.githubusercontent.com/91230277/146698362-5ce84404-81fb-41e8-ba6e-d3e1adaeb032.png)

- Another table we created had grouped a number of employees by titles. Our research assisted us in determining not just how many positions must be filled, but also how many vacancies will be available for a certain title. According to our data, the most in demand job positions in Pewlett Hackard are Senior Engineer and Senior Staff, whereas normal Engineer and Staff are each half that amount. However, only two manager positions are open:

![retiring_titles](https://user-images.githubusercontent.com/91230277/146698377-471862b7-583c-4c98-af83-befa68d46b6b.png)

### The Employees Eligible for the Mentorship Program
- This table is similar to the first retirement titles table, however it only includes workers born in 1965. It gives us a list of workers who are qualified to participate in the Pewlett Hackard mentoring program for future hiring.

![mentorship_eligibilty.](https://github.com/kossakova/Pewlett-Hackard-Analysis/blob/main/PNG/mentorship_eligibilty.png)

## Summary

There is a total count of 90398 positions to be open in Pewlett Hackard in the near future, they are:
29414 Senior Engineer positions, 28254 Senior Staff, 14222 Engineer, 12243 Staff, 4502 Technique Leaders, 1761 Assistant Engineers and 2 Manager positions.
Also, there is a total of 1549 qualified employees who are eligible to mentor new generation of Pewlett Hackard. 

It will be extremely beneficial to know how many qualified mentorship eligible workers we have for each title in preparation for the anticipated "silver tsunami." In our mentoring eligibility titles database, our query yielded extra information.

![mentorship_eligibilty_titles](https://user-images.githubusercontent.com/91230277/146698535-59d98183-ca15-473c-9d8f-14005b0e34d5.png)

Another chart we created is one for retirement compensation. It includes a list of retiring workers, along with employee numbers, names, and salaries.

![retirement_salary](https://user-images.githubusercontent.com/91230277/146698592-194a5202-3ad4-4da5-a2e4-0ff878fae7fe.png)
