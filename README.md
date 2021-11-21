# School_District_Analysis:
Analyse data on student funding and student standardized tests scores for a city school district
 
## Overview of the school district analysis:

### Maria is the chief data scientist for a City School district. In this module we will be helping Maria analyse data on student funding and student standardized tests scores. We have access to every student's math and reading scores as well as various information on the school they attend in files [schools_complete.csv](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/students_complete.csv)
* Our task is to aggregate the data and showcase trends in school performance. This analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities.

* The school board has notified Maria and her supervisor that the [students_complete.csv](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/students_complete.csv) file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We have to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we’ve replaced the math and reading scores, Maria would like us to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.
  
## Resources
* Data Source: schools_complete.csv, students_complete.csv
* Software: Python 3.7.10, Jupyter notebook 6.3.0

## School District Results:
The analysis of the School Disticts results show that:

### Results at district level:
* Total Schools: 15
	It is the same as before.
* Total Students: 39,170
	It is the same as before.
* Total Budget: $24,649,428.00
	It is the same as before.
* Avg. Math Score : 78.9
	It was 79.0 earlier. So, average math scores have come down by .1 points
* Avg. reading Score: 81.9
	It is the same as before.
* % Passing Math: 74.8
	It was 75.0 earlier. So, % passing math has come down by .2 points
* % Passing Reading: 85.7
	It was 86.0 earlier. So, % passing reading has come down t.3 points.
* % Overall passing: 64.9
	It was 65.0 earlier. So, % overall passing has come down by .1 points

You can find the district level details for both before and after below.
![district_summary](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/district_summary.png?raw=true)

### Results at school level:
The school level summary tells us the school type, total students, total budget, per student budget, Avg. Math Score, Avg. reading Score, % Passing Math, % Passing Reading, % Overall passing for all the fifteen schools. Let us see the results for Thomas High school only as other schools did not have any discrepancy in the results.

* School Type: Charter
	It is the same as before.
* Total Students: 1635
	It is the same as before.
* Total School Budget: $1,043,130.00
	It is the same as before.
* Per Student Budget: $638.00
	It is the same as before.
* Average Math Score: 83.350937
	It was 83.418349. The average math score came down by .06 points. approx.
* Average Reading Score: 83.896082
	It was 83.848930. The average reading score actually went up by .05 points approx.
* % Passing Math: 93.185690
	It was 93.272171. The % students passing math came down by .09 points approx.
* % Passing Reading: 97.018739
	It was 97.308869. The % students passing reading came down by .29 points approx.
* % Overall Passing: 90.630324
	It was 90.948012. The % overall passing came down by .32 points approx.

You can find the school level details for both before and after below.
![school_summary](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/school_summary.png?raw=true)

### Top Five schools based on overall passing rate:
	1. Cabrera High School
	2. Thomas High School
	3. Griffin High School
	4. Wilson High School
	5. Pena High School
 The Top 5 schools remain the same as before. You can find the details for both before and after below.
![top_five_schools](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/top_five_schools.png?raw=true)

### Bottom Five schools based on overall passing rate:
    1. Rodriguez High School.
    2. Figueroa High School.
    3. Huang High School.
    4. Hernandez High School.
    5. JOhnson High School.
The Bottom 5 schools remain the same as before. You can find the details for both before and after below.
![bottom_five_schools](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/bottom_five_schools.png?raw=true)

### The average math score for each grade level from each school:
As we can see clearly from the images the math score for each grade showed nan for 9th grade in Thomas High School. You can find details for both before and after below.
![math_by_grade](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/math_by_grade.png?raw=true)

### The average reading score for each grade level from each school:
As we can see clearly from the images the reading score for each grade showed nan for 9th grade in Thomas High School. You can find the details for both before and after below.
![reading_by_grade](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/reading_by_grade.png?raw=true)

### The scores by school spending per student:
Thomas High school spent $638 per student so for the $630-644 bracket resutls were:
* Average Math Score: 78.502002
	It was 78.518855. The average math score came down by .02 points. approx.
* Average Reading Score: 81.636261
	It was 81.624473 The average reading score actually went up by .01 points approx.
* % Passing Math: 73.462589
	It was 73.484209. The % students passing math came down by .02 points approx.
* % Passing Reading: 84.319261
	It was 84.391793. The % students passing reading came down by .07 points approx.
* % Overall Passing: 62.778233
	It was 62.857656. The % overall passing came down by .08 points approx

You can find the scores by school spending per student details for both before and after below.
![spending_ranges_per_student](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/spending_ranges_per_student.png?raw=true)

### The scores by school size
The school size for Thomas High School was 1635. So for the school size medium (1000-2000) students the results were:
* Average Math Score: 83.361201
	It was 83.374684. The average math score came down by .01 points. approx.
* Average Reading Score: 83.873869
	It was 83.864438. The average reading score actually went up by .01 points approx.
* % Passing Math: 93.582398
	It was 93.599695. The % students passing math came down by .02 points approx.
* % Passing Reading: 96.732654
	It was 96.790680. The % students passing reading came down by .06 points approx.
* % Overall Passing: 90.557997
	It was 90.621535. The % overall passing came down by .06 points approx.

You can find the scores by school size details for both before and after below.
![scores_by_school_size](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/scores_by_school_size.png?raw=true)

### The scores by school type
The school type for Thomas High School was Charter.So for Charter school type results were:
* Average Math Score: 83.465425
	It was 83.473852. The average math score came down by .01 points. approx.
* Average Reading Score: 83.902315
	It was 83.896421. The average reading score actually went up by .01 points approx.
* % Passing Math: 93.610020
	It was 93.620830. The % students passing math came down by .01 points approx.
* % Passing Reading: 96.550223
	It was 96.586489. The % students passing reading came down by .04 points approx.
* % Overall Passing: 90.392533
	It was 90.432244. The % overall passing came down by .04 points approx


You can find the scores by school type details for both before and after below.
![scores_by_school_type](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/scores_by_school_type.png?raw=true)

## Summary:

1. The District summary was affected and the data for 
* Avg. Math Score came down, 78.9 vs 79.0.
* Avg. Reading Score remained the same.
* % Passing Math came down, 74.8 from 75.0,  but tenths of a percent is equivalent to thousandths of a value, or grade so it doesn't matter.
* % Passing Reading came down, 85.7 from 86.0, but tenths of a percent is equivalent to thousandths of a value, or grade so it doesn't matter.
* % Overall passing came down,  64.9 from 65.0, but tenths of a percent is equivalent to thousandths of a value, or grade so it doesn't matter.
We can say that only the Math Score came down by one-tenth and thus affected the results.

2. The School Summary showed the same thing that Avg. Math Score for Thomas High School came down by .06 points that is after rounding .1 points. The reading score actaully went up by .05 points. And the % Passing Math, % Passing Reading, % Overall passing were in tenth of percent and too small to matter they meant discrepancy in one thousandth of a value.

3. The rank of the Top five schools and the bottom five schools were the same.

4. The score based on spending_per_student, school size or school type also showed minor changes but taking into account that hundredths (range: 0.01–0.09) or lower do not impact an average  and  tenths of a percent (.1-.9) is equivalent to thousandths of a value, or grade. Like averages, thousandths of a grade don't have an impact on the overall percentage because they are so small.

We can safely say that School board and Maria should be relieved that even after removing the compromised data the results of the analysis still hold good. 

So we can draw some inferences from the current analysis 
* School size is the best indicator of a school's performance. The difference is huge where schools which are small/medium in size have above 89% overall pass percentage regardless of the budget or the type of school but big schools with more than 2000 students have an overall pass percentage 58%. 
![scores_by_school_size](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/scores_by_school_size.png?raw=true)

* School type also is a indicator of a school's performance. The difference is huge where school type is Charter have 90.39% overall pass percentage while for school type as Districts have 53.67% overall pass percentage. But also can be explained because of the size as 1858 students is the highest student size for Charter type schools.
![scores_by_school_type](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/scores_by_school_type.png?raw=true)

* Wilson High School has 2283 students and lowest budget of $578 per students but it is among the top 5 schools with 90.58% overall pass percentage. There should be more analysis on the results of this school as their data may be compromised or else if their data is correct we need to do more research to find what makes it successful and try to follow their footsteps for other large schools.
![top_five_schools](https://github.com/sucharita1/School_District_Analysis/blob/730ea4fec1ea4092bc1c340f45c86fb43457bd4d/Resources/top_five_schools.png?raw=true)






