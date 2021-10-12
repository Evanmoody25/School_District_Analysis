# School_District_Analysis

## Overview of project
-A snapshot of the district's key metrics, presented in table format.

-Key metrics for each school, presented in table format.

-Tables presenting each of the following metrics:
1) Top 5 and bottom 5 performing schools, based on the overall passing rate
2) The average math score received by students in each grade level at each school
3) The average reading score received by students in each grade level at each school
4) School performance based on the budget per student
5) School performance based on the school size
6) School performance based on the type of school Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.

## Background

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Deliverable 1 requierments 

##The loc method is used to select all the reading and math scores from the ninth grade at Thomas High School.

1a) A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df.

1b) A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.

2a) Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.

2b) Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.

3) The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.

# Deliverable 1 


## The loc method is used to select all the reading and math scores from the ninth grade at Thomas High School.

1a) A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df.

1b) A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df.

![Capture](https://user-images.githubusercontent.com/89880015/137040911-0624eb15-4033-4fe0-98d3-1bd8bb696d30.PNG)

2a) Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df.

2b) Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df.

![Capture](https://user-images.githubusercontent.com/89880015/137041186-85b285d6-6705-47df-b493-3321ee9eb742.PNG)

3) The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.

![Capture](https://user-images.githubusercontent.com/89880015/137041497-f604997b-0a6f-446a-bfd2-9c25f5b38000.PNG)

![Capture](https://user-images.githubusercontent.com/89880015/137041552-b9d19280-caeb-4af5-a8d5-4e115fdb6582.PNG)

## Deliverable 2 requirements

## The task is to repeat the school district analysis and update the following required metrics in the PyCitySchools_Challenge.ipynb file:

1) The district summary DataFrame.

2) The school summary DataFrame.

3) The top 5 performing schools, based on the overall passing rate.

4) The bottom 5 performing schools, based on the overall passing rate.

5) The average math score for each grade level from each school.

6)The average reading score for each grade level from each school.

7)The scores by school spending per student.

8)The scores by school size.

9)The scores by school type.

## Deliverable 2

1) The district summary DataFrame.

![Capture](https://user-images.githubusercontent.com/89880015/137042588-6f9f6594-092e-4c5e-a808-161345a93291.PNG)

2) The school summary DataFrame.

![Capture](https://user-images.githubusercontent.com/89880015/137042747-d3c6dec3-97ff-420b-ba56-14461c2fac00.PNG)

3) The top 5 performing schools, based on the overall passing rate.

![Capture](https://user-images.githubusercontent.com/89880015/137043014-4cf22360-9dfd-473e-98b6-4f2559391758.PNG)

4) The bottom 5 performing schools, based on the overall passing rate.

![Capture](https://user-images.githubusercontent.com/89880015/137043069-e3f445c4-2894-4909-9ed8-bd2a51a348e0.PNG)

5) The average math score for each grade level from each school.

![Capture](https://user-images.githubusercontent.com/89880015/137043571-7428a0f0-b140-440f-bec2-5f38c9f33355.PNG)

6)The average reading score for each grade level from each school.

![Capture](https://user-images.githubusercontent.com/89880015/137043657-c401c267-a6b1-45c1-876a-1311fcfe2f79.PNG)

7)The scores by school spending per student.

![Capture](https://user-images.githubusercontent.com/89880015/137043886-1ad2df7f-7894-4727-8b9a-90fc183e5106.PNG)















