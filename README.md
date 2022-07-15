# School_District_Analysis

## Project Overview
A school board has noticed academic dishonesty in ninth graders reading and math scores at Thomas High School. To uphol state testing standards they would like to replace these scores with Nan for a better analysis of state testing.

1. Replace the ninth grade reading and math scores with NA
2. Repeat the School district analysis with the updated scores

## Resources
- Data Sources: schools_complete.csv & students_complete.csv
- Software: Python 3.7.6, Visual Studio Code 1.38.1
- Jupyter 4.9.2

## Results
The results of removing 9th graders reading and math scores from Thomas High School are as seen below:
```
School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.350937	83.896082	66.911315	69.663609	65.076453
```
## District Summary before removing Thomas High School 9th grade scores
```
district_summary_df
Total Schoools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	39,170	$24,649,428.00	79.0	81.9	75	86	65
```
## District Summary after removing Thomas High School 9th grade scores
new_district_summary_df
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	39,170	$24,649,428.00	78.9	81.9	74.8	85.7	64.9
## Overall Results
- The overall passing percentage for Thomas High School fell to 65%
- The overall passing percentage for the entire district fell to 64.9%
- Thomas High School was no longer included on the list of top five schools.
  
 ## Challenge Summary
After reading and math scores had been replaced, Thomas high school was no longer in the top 5 schools, it's overall passing percentage fell to 65%, "% Passing Reading" fell to 69%, "% Passing Math" fell to 66.9%, and Thomas High School was no longer in the top 5 Schools. These changes to the 9th grade scores significantly changes Thomas High School standing but upholds the standards for testing.
