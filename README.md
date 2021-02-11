# School_District_Analysis
Using the Pandas library and Jupyter Notebook replace incorrect math and reading scores for ninth graders from one high school using logical operations with conditionals. 

## Goals:
- Filter DataFrames using logical operators
- Replace the incorrect values with NaN

## PyCitySchools analysis contains:
 - District Summary
 - School Summary
 - High and Low Performing Schools
 - Math and Reading Scoresby Grade
 - Scores by School Spending
 - Scores by School Size
 - Scores by School Type
 
 ## Following Functions were used on DataFrames
 - Mean
 - Sum
 - Count
 - Cut
 - Map
 - Format
 - Sort_values
 - Merge
 - GroupBy

With these data changed, this is how the results changed:

- for the district summary overall passing was decreased by one percent, math by 0,1% and reading did not change. Out of 39,170 students, ninth graders from Thomas High School count for only 461 students. This is why leaving their performance hadn't affected it significantly.

- for the school summary, leaving out ninth graders affected math and reading score only slightly but we can see significant decrease in overall passing, from 90% to 65%. 

- Changing data put Thomas High Shool on Overall Passing lever for the district, which is 64%


- Math and Reading Scores for ninth grade for Thomas High School are not counted NaN

- Scores by School Spending - Thomas High School is in the third spending range bin, passing percentage for math and reading declined and overal passing went down by 7%

- Scores by School Size - Thomas High School is medium size shool, only medium size school passing percentage for math and reading declined and overal passing went down by 6%.

- Scores by School Type - Thomas High School is charter school, passing math and reading number went down, overal passing down by 3%









