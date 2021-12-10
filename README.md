# School District Analysis
## Project Overview
The purpose of this project is to analyze standardized testing results PyCity School District. As part of this project, students' math and reading scores for the schools within the district were analyzed to find average test scores among each school as well as the math, reading and overall passing percentages. Once these values were calculated, the data was further analyzed to compare results per school, budget per student, school type and school size. 

After the initial analysis, discrepancies within the data for Thomas High School's ninth graders were identified. The original analysis was modified to exclude all test results (math and reading) for 9th graders at Thomas High School. To complete this, the values were replaced with NaN (no data) then the full analysis was recreated using the updated data. 

### Resources
The data files used for the analysis are available within the [Resources](https://github.com/LacyS6198/School_District_Analysis/tree/main/Resources) folder.


### Development Tools
Anaconda Jupyter Notebook with Python was used for this project. The Pandas and Numpy libraries from Python were also used.
<br/><br/>

## Results
The results of the updated analysis are summarized below. The results include the impact of removing the testing scores (math and reading) from the data for 9th graders at Thomas High School.
<br/>

### Effect on District Summary
The majority of testing related metrics decreased in the district summary after the data was adjusted to remove the Thomas High School's 9th graders results. In the images below, we can see the following changes occurred:

- Average Math Score decreased from 79.0 to 78.9
- Average Reading Score was the same at 81.9 both before and after
- % Passing Math decreased from 75.0 to 74.8
- % Passing Reading decreased from 85.8 to 85.7
- % Overall Passing decreased from 65.2 to 64.9

**Updated District Summary:**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![District_Summary_New](https://user-images.githubusercontent.com/93630042/145617310-af71a42b-d5ea-428f-901c-28cc53586846.png)

**Original District Summary:**
![District_Summary_Orig](https://user-images.githubusercontent.com/93630042/145617321-1bb94225-7b28-467a-9120-d499efe49ee1.png)
<br/>

### Effect on School Summary
As part of the analysis, the high (top 5) and low (bottom 5) performing schools were reviewed. The results of this summary were overall the same. The top 5 high and low performing schools remained the same after adjusting the data for Thomas High School's 9th graders' test scores. While the overall results were the same, there was a decrease in Thomas High Schools' overall passing rate, decreasing from 90.948012 in the original analysis to 90.630324 in the updated analysis.

**Updated School Summary - Top 5**
![SS_Top_New](https://user-images.githubusercontent.com/93630042/145618504-3ad54734-cef6-4ec0-a80c-399554477276.png)

**Original School Summary - Top 5**
![SS_Top_Orig](https://user-images.githubusercontent.com/93630042/145618518-ee8ac255-0274-40b5-8418-018befc28fbb.png)

**Updated School Summary - Bottom 5**
![SS_Bottom_New](https://user-images.githubusercontent.com/93630042/145618476-c0f17ec4-0480-45bd-8445-2c90300f2dda.png)

**Original School Summary - Bottom 5**
![SS_Bottom_Orig](https://user-images.githubusercontent.com/93630042/145618487-da82f509-174b-4fb6-b803-7b86cae76eb1.png)
<br/>

### Effect on Thomas High School's Comparative Performance
Thomas High School's comparative performance was not affected by the data adjustments. In comparison to all other schools, Thomas High School was the second highest performing school both in the original and modified analysis. While the overall results were the same, there was a decrease in Thomas High Schools' overall passing rate, decreasing from 90.948012 in the original analysis to 90.630324 in the updated analysis.
<br/>

### Effect of Replacing 9th Graders' Scores with NaN
This section details out the effect of replacing 9th graders' scores with "NaN" for Thomas High School. The effect was reviewed on the following metrics:

- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type

#### Math and Reading Scores by Grade
The only effect on math and reading scores were for Thomas High School's grade 9. In the below screenshots we can see that the updated summary shows "NaN" in the 9th grade data instead of a value. 

| **Updated Math Scores by Grade**  | **Original Math Scores by Grade** |
| ------------- | ------------- |
| ![MO_New](https://user-images.githubusercontent.com/93630042/145620701-e52b214d-4b6e-4f3d-a21a-0e6bd298c997.png)  | ![MO_Orig](https://user-images.githubusercontent.com/93630042/145620709-ee12eba1-1681-43d4-9531-8f2947c817c2.png)  |


| **Updated Reading Scores by Grade**  | **Original Reading Scores by Grade** |
| ------------- | ------------- |
| ![RO_New](https://user-images.githubusercontent.com/93630042/145620721-27921d01-142f-4482-8f4e-d3cadf5bf3ba.png)  | ![RO_Orig](https://user-images.githubusercontent.com/93630042/145620725-14a4fa38-898d-490c-9679-cb7001c9b9d2.png)  |
<br/>

#### Scores by School Spending
There was no change in the scores by school spending when comparing the updated analysis to the Original.

| **Updated School Spending Summary**  | **Original School Spending Summary** |
| ------------- | ------------- |
| ![Spending_New](https://user-images.githubusercontent.com/93630042/145621834-59e0b707-572a-4da7-8c65-f6883ed7e27e.png) | ![Spending_Orig](https://user-images.githubusercontent.com/93630042/145621844-ea4f963f-cad9-4bf3-ad8b-382a153f9349.png)  |
<br/>

#### Scores by School Size
There was no change in the scores by school size when comparing the updated analysis to the Original.

| **Updated School Size Summary**  | **Original School Size Summary** |
| ------------- | ------------- |
| ![Size_New](https://user-images.githubusercontent.com/93630042/145622462-b77bd1db-4498-443d-a31b-6b21497535d3.png)  | ![Size_Orig](https://user-images.githubusercontent.com/93630042/145622492-67c479ce-8449-44c9-bd12-a21499003b98.png)  |
<br/>

#### Scores by School Type
There was no change in the scores by school type when comparing the updated analysis to the Original.

| **Updated School Type Summary**  | **Original School Type Summary** |
| ------------- | ------------- |
| ![Type_New](https://user-images.githubusercontent.com/93630042/145622596-42ab0af1-c6e3-4c97-9391-f7213d32fbdc.png) | ![Type_Orig](https://user-images.githubusercontent.com/93630042/145622615-86e01671-ec52-4314-afa4-c97db2e53e4d.png)  |
<br/>

## Summary
The below summarizes the key metric changes caused by the data manipulation that was performed to remove Thomas High School's 9th graders' math and reading scores. Overall, there was a minimum impact to results, both for the overall school district as well as Thomas High School itself. 

- Effect on District Summary:  **minimal effect**
  - Average Math Score decreased from 79.0 to 78.9
  - Average Reading Score was the same at 81.9 both before and after
  - % Passing Math decresed from 75.0 to 74.8
  - % Passing Reading decreased from 85.8 to 85.7
  - % Overall Passing decreased from 65.2 to 64.9
- Effect on School Summary:  **minimal effect**
  - No effect on overall results among schools; top 5 high and low performing schools remained the same
  - Thomas High Schools' overall passing rate decreased from 90.948012 in the original analysis to 90.630324 in the updated analysis
- Math and reading scores by grade:  **minimal effect**
  - Thomas High School's 9th grade scores were all changed to "NaN". 
  - No other effects on Thomas High School's grades 10 - 12 or other schools within the district
- Scores by school spending:  **no effect**
- Scores by school size:  **no effect**
- Scores by school type:  no effect
