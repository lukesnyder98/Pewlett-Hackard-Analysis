# Pewlett-Hackard-Analysis

## Overview

The purpose of this analysis is to examine the "silver tsunami" at Pewlett-Hackard and gather data that would inform a mentorship program. We find the number of retiring employees per title and the number of employees who would be able to mentor the next generation.

## Results

![The retirement_titles table](/Resources/retirement_titles.png)

* The retirement_titles table shows that most employees have been promoted at least once during their time at Pewlett-Hackard, with many employees appearing as duplicates after being promoted to a senior position.

![The retiring_titles table](/Resources/retiring_titles.png)

* According to the retiring_titles table, the two roles with the most retiring employees are Senior Engineer and Senior Staff. This aligns with the previous result and indicates that most retiring employees have been promoted several times.
* There are 50,842 total retiring Senior Engineers and Staff and 21,616 retiring employees holding other titles.

![The bottom rows of the mentorship_eligibility table](/Resources/mentorship_eligibility.png)

* The mentorship_eligibility table has 1549 rows, showing that 1,549 employees are eligible for the mentorship program.

## Summary

Considering there are 21,616 retiring employees holding non-senior positions and only 1,549 employees eligible for the mentorship program, there may not be enough employees to mentor the next generation at Pewlett-Hackard. However, since it will take at least three years for all of these employees to retire and all of their positions to be filled, the eligible employees could mentor a new employee or employees every year. If there are not enough mentors, then perhaps they could mentor only the youngest new employees. Two queries that may provide more insight would be a table of the current employees who joined Pewlett-Hackard within the last three years, and another table sorting these employees by birth date to show the ages of the youngest new employees.