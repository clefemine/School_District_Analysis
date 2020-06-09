# School District Analysis


# Challenge

Objective: replace all reading and math scores from the 9th grade class at Thomas High School with "NaN"
  1. Determine if data is clean.
  2. Remove any prefixes or suffixes within student names.
  3. Replace math/reading scores of 9th graders at Thomas High school with "NaN".
  4. Merge data frames with clean and complete data.
  5. Calculate average math/reading scores.
  6. Find and count students with passing reading/math scores.
  7. Calculate each school's budget based on their passing scores.
  8. Determine spending ranges per student.
  9. Determine each school's size based on amount of students per school and passing rate.
  10. Calculate the passing percentages based of school type.
  

## Resources
 - Data Source: schools_complete.csv, students_complete.csv, and clean_students_complete.csv
 - Software: Anaconda - Jupyter Notebook (imported; Pandas, Numby)

## Summary

### Q&A Based on Challenge

How is the district summary affected?
- The passing percentages of math/reading, and overall scores decreased by 1%.
      
How is the school summary affected?
- There is a dramatic drop in percentages of math/reading and overall scores at Thomas High School. No other school is affected. 
      
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
- Thomas High School loses its spot in the top 5 overall scores but it does not get placed in the bottom 5 schools. 
 
How does replacing the ninth-grade scores affect the following?
  
Math and Reading Scores by Grade:
- This only affects the 9th grade class of Thomas High School, because it is replaced with "NaN". 

Scores by School Spending:
- The only spending range affected is $630-644. Here the percent of passing math/reading and overall scores has decreased.

Scores by School Size:
- The medium (1000-2000) school size is affected by the change. The percentage of math/reading and overall scores has decreased.

Scores by School Type:
- Charter schools are affected and their percentage of math/reading and overall scores has decreased by 3-4%.
