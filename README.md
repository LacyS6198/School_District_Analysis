# School District Analysis
## Project Overview
The purpose of this project is to analyze standardized testing results PyCity School District. As part of this project, students' math and reading scores for the schools within the district were analyzed to find average test scores among each school as well as the math, reading and overall passing percentages. Once these values were calculated, the data was further analyzed to compare results per school, budget per student, school type and school size. 

After the initial analysis, discrepancies within the data for Thomas High School's ninth graders were identified. The original analysis was modified to exclude all test results (math and reading) for 9th graders at Thomas High School. To complete this, the values were replaced with NaN (no data) then the full analysis was recreated using the updated data. 

### Resources
The data files used for the analysis are available within the [Resources](https://github.com/LacyS6198/School_District_Analysis/tree/main/Resources) folder.

### Development Tools
Anaconda Jupyter Notebook with Pyhon was used for this project. The Pandas and Numpy libraries from Python were also used.

## Results
The results of the updated analysis are summarized below. The results include the impact of removing the testing scores (math and reading) from the data for 9th graders at Thomas High School.

### Effect on District Summary
The majority of testing related metrics decreased in the district summary after the data was adjusted to remove the Thomas High School's 9th graders results. In the images below, we can see the following changes occurred:

- Average Math Score decreased from 79.0 to 78.9
- Average Reading Score was the same at 81.9 both before and after
- % Passing Math decresed from 75.0 to 74.8
- % Passing Reading decreased from 85.8 to 85.7
- % Overall Passing decreased from 65.2 to 64.9

**Updated District Summary:**
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![District_Summary_New](https://user-images.githubusercontent.com/93630042/145617310-af71a42b-d5ea-428f-901c-28cc53586846.png)

**Original District Summary:**
![District_Summary_Orig](https://user-images.githubusercontent.com/93630042/145617321-1bb94225-7b28-467a-9120-d499efe49ee1.png)

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


### Effect on Thomas High School's Comparative Performance

### Effect of Replacing 9th Graders' Scores with NaN
- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type

## Summary
