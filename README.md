# FP20-Analytics-Data-Challenges #13 -DATA-DRIVEN-EDUCATION-MANAGEMENT 
## Analyzed and Submited by- Saddam Ansari @Aspiring Data Analyst [Linkeldin](https://www.linkedin.com/in/saddam-ansari-dataanalyst)

### Live Dashboard at Novypro [Live_link_Novypro](https://www.novypro.com/project/fp20-analytics-january-2024-challenge-by-saddam-ansari)
### Dashboard with ZoomChart Visuals [Link](https://app.powerbi.com/groups/me/reports/2c654ec6-6478-438b-9b1e-24c87619eb39/ReportSection3dce1e00b91c01b4b31c?redirectedFromSignup=1&experience=power-bi)

#
## Table of Content:
1.[Problem Statement](#problem-statement)
2.[Project Background](#project-background-information)
3.[Projects Objective](#projects-challenge-objective)
4.[Dataset](#dataset)
5.[Collaboration](#collaboration)
6.[Tools Used](#tools-used)
7.[Dashboard Overview](#dashboard-overview)
8.[Main Question](#questions--solutions)
9.[Optional Question](#optional)
10.[Full Dashboard View](#full-dashboard-view)
11.[Learning](#my-learnings)
12.[End](#the-end)

#
### Problem Statement 
[🔄 Home](#table-of-content)

The **Fort Vermilion School Division (FVSD)** is a governmental organization responsible for overseeing schools in the northwestern corner of Alberta, Canada. FVSD is renowned for their commitment to data-driven planning and decision-making to empower every student with equal opportunities and care in education.

#
### Project Background information:
[🔄 Home](#table-of-content)

The school year is split into 3 semesters (Fall, Winter and Spring). Each student is assessed each semester using three test (assessment) types - TOSREC, TOWRE and TOSWRF - using a standard score system. For each test, there is a known associated cost per student.

Based on the received score, students are split into groups indicating their performance level. Two types of grouping are used: 1) assessment level (very poor, at risk, good etc.) and 2) assessment level grouping (below average or average and above). Students with poor test results are required to take additional classes (Intervention groups), where each group contains 5 or 10 students depending on the test score, and requires additional teacher resources.

#
### Projects Challenge Objective
[🔄 Home](#table-of-content)

This challenge invites participants to delve deep into educational data and assist the School Division with strategic planning for assessments, comprehending student performance, and determining the necessary teacher resources for future enhancements.

#
### Dataset: 
[🔄 Home](#table-of-content)

Educational data related to student assessments, test scores, and associated costs.

#
### Collaboration: 
[🔄 Home](#table-of-content)

This challenge is brought to you in collaboration with ZoomCharts, integrating their exceptional Power BI solution to enhance your report creation skills.

#

### Tools Used:
[🔄 Home](#table-of-content)

In line with the objectives and project requirements, I have utilized **Power BI**, a powerful business intelligence tool, for dashboard creation.

#

### Dashboard Overview:
[🔄 Home](#table-of-content)

I have developed a Power BI dashboard consisting of **two pages** to meet the objectives of the challenge. The first page is based on **requested question**, and second page is **optional**.

##
## Questions & Solutions

[🔄 Home](#table-of-content)

#### Q1.Total number of students per each assessment level broken down by:
 * Semester (Fall, Winter, & Spring) 
 * School Year. 
 *  School

#### Solution:
One challenge I faced was that it was difficult to show data trends in a single visual with three different breakdowns. To solve this challenge, I added a filter slicer to the dashboard. The filter slicer allows users to select a specific semester, school year, and school.

To address this, I initially implemented a filter (slicer) to facilitate viewing data trends according to different breakdowns such as semester, school year, and school.

Below is the visual representing the Total number of students per each assessment level for the Spring Semester of the 2021/2022 School Year across all schools. With the applied filter, we observe the following:
 * Above Average Assessment level: **601 students**
 * Average Assessment level: **1512 students**
 * Below Average Assessment level: **707 students**
 * Good Assessment level: **330 students**
 * Poor Assessment level: **429 students**
 * Very Good Assessment level: **117 students**
 * Very Poor Assessment level: **272 students**

![1](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/39ee5f68-11f7-4769-90e9-0b1ff6506b71)

![3](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/7839ad51-e61a-4125-9cc0-e9a13e907ea7)

[🔄 Home](#table-of-content)

#
#### Q2. Total number of students per each assessment level group broken down by
 * Semester (Fall, Winter, & Spring)
 * School Year
 * School

#### Solution:

The visual below illustrates the total number of students per each assessment level group for the Spring semester of the 2021/2022 school year across all schools. According to the applied filter, during the Spring semester of the 2021/2022 school year, there were a total of 1724 students assessed as Average and Above, while 1036 students were assessed as Below Average.

![1](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/39ee5f68-11f7-4769-90e9-0b1ff6506b71)

![2](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/0e92eda2-b444-4d55-932f-8093ec910dff)

[🔄 Home](#table-of-content)
#
#### Q3. Percentage of students (calculated from the total number of students) per each assessment level broken down by: 
 * Semester (Fall, Winter, & Spring)
 * School Year
 * School

#### Solution:
Once Again it was difficult to show data trends in a single visual with three different breakdowns. To solve this challenge, I added a filter slicer to the dashboard. The filter slicer allows users to select a specific semester, school year, and school.

To address this, I initially implemented a filter (slicer) to facilitate viewing data trends according to different breakdowns such as semester, school year, and school.

Below is the visual representing the percentage of  Total number of students per each assessment level for the Spring Semester of the 2021/2022 School Year across all schools. With the applied filter, we observe the following:
 * Above Average Assessment level: **21.84%** students
 * Average Assessment level: **61.49%** students
 * Below Average Assessment level: **44.83%** students
 * Good Assessment level: **9.77%** students
 * Poor Assessment level: **32.76%** students
 * Very Good Assessment level: **2.87%** students
 * Very Poor Assessment level: **21.84%** students

![1](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/39ee5f68-11f7-4769-90e9-0b1ff6506b71)

![4](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/a0e28198-c37c-479f-9cd9-e91f7a03ac1c)

#

[🔄 Home](#table-of-content)

#### Q4. Percentage of students (calculated from the total number of students) per each assessment level group broken down by
 * Semester (Fall, Winter, & Spring)
 * School Year
 * School

#### Solution:
The visual below illustrates the total number of students per each assessment level group for the Spring semester of the 2021/2022 school year across all schools. According to the applied filter, during the Spring semester of the 2021/2022 school year, there were a total of 67.24% students assessed as Average and Above, while 62.07 students were assessed as Below Average.

![1](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/39ee5f68-11f7-4769-90e9-0b1ff6506b71)

![5](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/18ee90e4-3e06-4fd4-95af-a53007d49c47)

[🔄 Home](#table-of-content)

#
#### Q5. Students' Assessments between 80 and 90 Standard Score in each period go into an Intervention Group (Tier 2). This Group contains 10 Students that require one Teacher. How Many teachers will we require for these Intervention Groups in the Winter of 2023 / 2024 based on 2023 / 2024 Fall Results?

#### Solution:
We have requested that, Students Assessments between **80-90 Standard Score** in each period go into an Intervention Group (Tier 2). 

So, total students who obtained 80-90 score is 👉 **732**

This Group contains 10 Students that requires one Teacher.
 
####  732/10= Approx 73 Teachers will require in winter.

![6](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/50bb6e67-9a67-493a-a473-3145d3704917)

[🔄 Home](#table-of-content)

#
#### Q6. Students' Assessments below 80 Standard Score in each period go into an Intervention Group (Tier 3). This Group contains 5 Students and requires one Teacher. How Many teachers will we require for these Intervention Groups in the Winter of 2023 / 2024 based on 2023 / 2024 Fall Results?

#### Solution:
We have requested that, Students Assessments between bellow 80 Standard Score in each period go into an Intervention Group (Tier 3). 

So, total students who obtained bellow 80 score is 👉 **796**

This Group contains 5 Students that requires one Teacher.

#### 796/5= Approx 159 Teachers will require in winter.

![7](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/c6f552ae-88c5-496d-808c-e6a017fd99d1)

[🔄 Home](#table-of-content)

#

#### Q7. What are projected testing costs for the Winter of 2023 / 2024 based on 2023 / 2024 Fall results?

#### Solution:
 * Projected Testing Cost for Winter 2023/2024 **$7,493**

 * Detailed Distribution

| Assessment Type | Cost | Total Student | Total Cost |
|---|---|---|--|
| TOSREC | $1 | 2036 | $2,036 |
| TOSWRF | $1.5 | 2018 | $3,027 |
| TOWRE | $1.2 | 2015 | $2,418 |

![8](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/ade8470f-4290-4d7a-834a-0da864c3891c)

#

## Optional:

[🔄 Home](#table-of-content)

This section is optional section its mean page 2 stared here, in this section I presented some insights to solve some optional question.

#### Q1. Show AVG Standard Score by Assessment Type?
For this question I used a donught chart to show avg score by assement type. my analysis reveals that **TOSREC 80.67**, **TOSWR 97.23** and **TOWRE 91.95** avg score.

![9](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/682b0767-9df3-4f80-b9fa-565e769fbfa9)

#

#### Q2. Showcase the average score trend throughout the years?
The bar chart visual shows that the average score has increased over time. In 2021, the average score was 91.60. In 2022, the average score was 93.87. And in 2023, the average score was 93.84.

![10](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/3ddddc8a-48c0-4a00-ac5c-818bc4c4aac4)

#
#### Q3. Showcase the total number of student trend throughout the years?
The bar chart visual shows that the total number of student has increased over time. In 2021, the total number of student was 2110. In 2022, the total number of student was 2675. And in 2023, the total number of student was 2743.

![11](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/08fc1451-dea3-45b2-be3b-9f207d26dbfd)

[🔄 Home](#table-of-content)

#
#### Q4. Showcase the Total Student by School?
For this analysis, I have created a bar chart that illustrates the total number of students for each school. This visualization provides a clear overview of the student population across different schools.

According to the analysis, the **High Level Public School** boasts the highest number of students, with **563 students**, followed closely by **La Crete Public School**, which has **491 students**. These two schools emerge as the top performers based on total student count.

![12](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/6ce80789-7e55-42aa-8b0f-5855d53ae878)

#
#### Q4. Showcase the Total Teacher by School?
I've created a bar chart showcasing the total number of teachers by school. This visualization allows for a clear comparison of each school based on the total number of teachers they have.

Upon analysis, it's evident that **High Level Public School** ranks the highest with **73 teachers**, closely followed by **La Crete Public School** with **72 teachers**. These two schools emerge as the top performers in terms of total teachers.

[🔄 Home](#table-of-content)

#
#### Q5. Showcase Total Student by Gender?
To showcase the distribution of total students by gender, I've utilized donut charts, providing a clear and visually appealing representation of the data.

Based pn my analysis, it's evident that the majority of students are male, totaling 3270, while female students total 3120. 

![13](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/aaf3da97-f676-476d-ba58-ab4a705a0a13)

#

#### Q6. Showcase Total Student by Semester, Assesement Level Group and Year
For showcasing the distribution of total students by Semester, Assessment Level Group, and Year, I've utilized a bar chart. This visualization offers a comprehensive view of the data across these three dimensions.

![14](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/60704fcb-0e17-4feb-b7b8-feac3b1e6c3b)

#
### Full Dashboard View

[🔄 Home](#table-of-content)

**Page 1:**

![1](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/84b6ef53-c42f-4d87-9dc1-0088f325bd75)

**Page 2:**

![2](https://github.com/user-saddam123/FP20-Analytics-Data-Challenges-DATA-DRIVEN-EDUCATION-MANAGEMENT/assets/123800896/2ac9b08d-7cb7-404b-adf1-9afb50a08d85)

#
### My Learnings:

[🔄 Home](#table-of-content)

This challenge was a great opportunity to learn and apply advanced data analysis techniques. I also learned how to create visually appealing and informative dashboards that can be used to make data-driven decisions.

also This project has been truly rewarding, allowing me to showcase my work and further my journey as an aspiring data analyst. It not only adds value to my portfolio but also demonstrates my capabilities in handling complex datasets.

**I'm grateful to Federico Pastor and Zoomcharts for providing this opportunity to learn and grow as a data analyst.**

Check out my submission and let me know what you think!

Your feedback is highly appreciated, and I encourage you to like, comment, and provide your insights. Feedback plays a crucial role in my growth, so please feel free to share any suggestions.

Apart from this project, I have also completed over **20 Power BI projects**, which you can explore on **NovyPro** at [NovyPro Portfolio](https://www.novypro.com/profile_projects/saddamansari)

Thank you for taking the time to view my project. I hope you enjoyed it.

#

Created and Analyzed by:

Saddam Ansari @Aspiring Data Analyst LinkedIn Link

Location: India

### THE END
[🔄 Home](#table-of-content)
