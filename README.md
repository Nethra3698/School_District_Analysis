# School_District_Analysis
Using Pandas for school district analysis





## Challenge Summary

## Analysis of Challenge

Recreate the district and school summary DataFrames.
  How is the district summary affected?
  Answer:  Originally the Average Math score was 79.0 but now it is found to be 78.9. The Average Reading score was 81.9 and is still 81.9. The percentage pass in math was 75 but is now 74. The % passing in reading was 86 and is now 85. And the overall % passing was 65 and is now 64
  How is the school summary affected?
  Answer:
Recalculate the high- and low-performing schools.
  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
  Answer: Initially, Thomas High School was ranked as the second best school because of its scores and percentage. But now it dropped down to the 8th position since the 9th grade scores were not considered.
Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
  How does replacing the ninth-grade scores affect the following?
    Math and Reading Scores by Grade
    Answer: Nothing changes other than for the NaN in the place of the 9th grade scores (both math and reading) of Thomas high school
    Scores by School Spending
    Answer: Thomas High School is a school with its spending per student in the range of $630-$644  due to which there is a noticable change that can be seen in this row. The change in the average math and reading score are not prominent as there is only a slight change in the second decimal place due to many samples in this range. But this change is made clear in the passing % for the overall, math and the reading. A drop in the passing percentage in math, passing percentage in reading and overall passing percentage can be seen from 73 to 67, 84 to 77 and 63 to 56 respectively. 
    Scores by School Size
    Answer: Thomas High School can be categorized as a medium size school and rightfully the row corresponding to it is affected by the change in data. There is a small change in the average math and reading scores that is only noticed beyond the second decimal point. But this change is more pronounced in the percentages. In fact there is a drop in the percentage passing in math, percentage passing in reading and overall percentage passing from 94 to 88, 97 to 91 and 91 to 85. 
    Scores by School Type
    Answer:Thomas High School is a charter high school and hence a change can be seen for this row of data. An overall drop is seen for all the values. Specifically, the percentage passing in math drops from 94 to 90, percentage passing in reading drops from 97 to 93 and the overall percentage passing drops from 90 to 87. 

