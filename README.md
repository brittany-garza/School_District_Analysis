# School_District_Analysis


Overview of the school district analysis: Explain the purpose of this analysis.

The analysis will provide the math and reading scores for all 15 schools. 
This information has been updated with academic dishonesty of Thomas High school ninth grade. 
We will be able to see how this academic dishonesty affects the math, rading and overall scores 

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?

The academic dishonestly did not affect the district summary a lot. The percentages for passing math, reading and overall remained close. 
(insert screenshots of before dishonetly and after dishonesty)

How is the school summary affected?

No other school was affected with the academic dishonestly, other than Thomas High School. 
Thomas High Schools percentage dropped from over 90% in math, reading and overall to below 70% in all 3 categories.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Comparing the school summaries of before and after replacing the grades of Thomas 9th graders, dropped the school from 3rd highest percentage to the 3 lowest school.

How does replacing the ninth-grade scores affect the following:
	Math and reading scores by grade
	This will affect the average that will need to be calculated for the scores by school spending, size and type.

	Scores by school spending
	The scores by school spending remained the same. 

	Scores by school size
	The school size score remained the same since we did not drop students from the data.

	Scores by school type
	The school type scores reamined the same.

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The first change that needed to be made was having to calculate a new student count. I found the total number of students of all schools and subtracted from the number of
Thomas High School 9th graders.

2. New averages needed to be calculated to reflect the change in the stundent count in the district summary dataframe. I used the same calculation from the module 
but divided by the new student count.

3. The calculations for the math, reading and overall percentages needed to be adjusted to only include Thomas grade levels 10th - 12th. I passed a conditional to only include 
Thomas high school and any student in 1oth, 11th, or 12th grade. I used the same conditionals as the module to get the number of students who passed math, reading and both. 
Once I calculated the new percentage, I replaced the only Thomas High school with the new math, reading and overall percentages.

4. The data frames by grade level needed to show NaN for Thomas 9th graders. All other averages remained the same as the module. 
