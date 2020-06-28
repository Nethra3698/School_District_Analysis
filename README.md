# School_District_Analysis
Using Pandas for school district analysis

## Project Overview
This particular project revolves around using Pandas to work with the reading and math scores of high school students from various schools. Muliple dataframes were created based on the requirement. Mainly, the students average scores in reading and math were obtained and  the number of students who passed in math, reading and both were also calculated. An analysis was conducted to see how these averages and percentages are comparable with different districts, schools, based on spending ranges, school sizes and grades. Also the top schools and bottom schools are obtained. 
## Resources 
The code used Python 3.7.6, along with pandas in jupyter notebook. schools_complete.csv and students_complete.csv was used as data resources for this project. 
## Summary of Results
- District Summary 
    ![Fig 1. ]( /analysis/DistrictSummary.PNG)
- School Summary
    ![Fig 2. ]( /analysis/SchoolSummary1.PNG)
- Top Schools
![Fig 3. ]( /analysis/TopSchools.PNG)
- Bottom Schools
![Fig 4. ]( /analysis/BottomSchools.PNG)
- Scores by grade (table on the left is for math and the one on the right is for reading)

    ![Fig 5. ]( /analysis/mathScoreByGrade.PNG)  ![Fig 6. ]( /analysis/ReadingScoreByGrade.PNG)
- Scores by school spending
![Fig 7. ]( /analysis/SpendingSummary.PNG)
- Scores by school size
![Fig 8. ]( /analysis/SizeSummary.PNG)
- Scores by school type 
![Fig 9. ]( /analysis/typeSummary.PNG)


## Challenge Summary
The 9th graders scores at Thomas High school needed to be replaced with NaN while all the other scores are left as they are and the analysis had to be repeated.
## Challenge Results
- District Summary 
![Fig 10. ]( /analysis/DistrictSummaryNew.PNG)
- School Summary
![Fig 11. ]( /analysis/SchoolSummaryNew2.PNG)
- Top Schools
![Fig 12. ]( /analysis/TopSchoolsNew.PNG)
- Bottom Schools
![Fig 13. ]( /analysis/BottomSchoolsNew.PNG)
- Scores by grade (table on the left is for math and the one on the right is for reading)

    ![Fig 14. ]( /analysis/mathScoreByGradeNew.PNG)  ![Fig 15. ]( /analysis/ReadingScoreByGradeNew.PNG)
- Scores by school spending
![Fig 16. ]( /analysis/SpendingSummaryNew.PNG)
- Scores by school size
![Fig 17. ]( /analysis/SizeSummaryNew.PNG)
- Scores by school type 
![Fig 18. ]( /analysis/TypeSummaryNew.PNG)
## Analysis of Challenge

1. How is the district summary affected?

   Answer: Originally the Average Math score was 79.0 but now it is found to be 78.9. The Average Reading score was 81.9 and is still 81.9. The percentage pass in math was 75 but is now 74. The % passing in reading was 86 and is now 85. And the overall % passing was 65 and is now 64

2. How is the school summary affected?

   Answer: The data points for Thomas High school is seen to change by atleast 30% in the school Summary. Previously, the percentage passing in math,reading and overall was estimated to be 93, 97 and 91 respectively. But after changing the 9th graders data these percentages drop to around 67, 70 and 65 respectively. This clearly shows that most of the 9th graders data is what amounted to the high pass percentage. 

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

   Answer: Initially, Thomas High School was ranked as the second best school because of its scores and percentage. But now it dropped down to the 8th position since the 9th grade scores were not considered.

4. How does replacing the ninth-grade scores affect the following?

- Math and Reading Scores by Grade
  
   Answer: Nothing changes other than for the NaN in the place of the 9th grade scores (both math and reading) of Thomas high school
   
 - Scores by School Spending
  
   Answer: Thomas High School is a school with its spending per student in the range of $630-$644  due to which there is a noticable change that can be seen in this row. The change in the average math and reading score are not prominent as there is only a slight change in the second decimal place due to many samples in this range. But this change is made clear in the passing % for the overall, math and the reading. A drop in the passing percentage in math, passing percentage in reading and overall passing percentage can be seen from 73 to 67, 84 to 77 and 63 to 56 respectively.
   
  - Scores by School Size
   
    Answer: Thomas High School can be categorized as a medium size school and rightfully the row corresponding to it is affected by the change in data. There is a small change in the average math and reading scores that is only noticed beyond the second decimal point. But this change is more pronounced in the percentages. In fact there is a drop in the percentage passing in math, percentage passing in reading and overall percentage passing from 94 to 88, 97 to 91 and 91 to 85. 
   
   - Scores by School Type
   
     Answer: Thomas High School is a charter high school and hence a change can be seen for this row of data. An overall drop is seen for all the values. Specifically, the percentage passing in math drops from 94 to 90, percentage passing in reading drops from 97 to 93 and the overall percentage passing drops from 90 to 87. 

Overall, there is a drop in the values after making the 9th grade scores of Thomas High School to NaN. The mean function by default skips the null values and calculates the average only for accurate data. This produces new values that are more accurate than the previously calculated ones. Also, previously Thomas high school was one of the top high schools (it was second on the list) but now it is not on the list anymore showing that the 9th grade marks contributed heavily in making it a top school. 
