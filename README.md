# School_District_Analysis

## Overview of the School District Analysis
The School Board would like insight on school performance trends in order to make strategic decisions about the school budgets and priorities. The data scientist team analyzed data on student funding and standardized test scores to deliver several performance metrics at both the district and school level. However, the School Board discovered that there is evidence of grades being altered for the ninth graders at Thomas High School (THS). The purpose of this analysis is to reevaluate the data by excluding the math and reading scores for THS's ninth grade to uphold state-testing standards. 

## Results

### District Summary
The district summary score metrics had a slight decrease except for the Average Reading Score.
- Average Math Score decreased from 79% to 78.9%
- Passing Math Score decreased from 75% to 74.8%
- Passing Reading Score decreased from 85.8% to 85.7%
- Overall Passing Score decreased from 65.2% to 64.9%

#### District Summary Analyis 
![PyCitySchools_Challenge_District1](https://user-images.githubusercontent.com/78664640/112765058-59129f80-8fd9-11eb-991c-1d04d850ebe8.png)

#### District Summary Analyis with THS 9th Grade Excluded
![PyCitySchools_Challenge_District2](https://user-images.githubusercontent.com/78664640/112765069-69c31580-8fd9-11eb-8929-aa2d5e8a354a.png)

### School Summary
The school summary score metrics for THS was affected in the following ways:
- Average Math Score decreased from 83.42% to 83.35%
- Average Reading Score increased from 83.84% to 83.89%
- Passing Math Score decreased from 93.27% to 93.19%
- Passing Reading Score decreased from 97.31% to 97.02%
- Overall Passing Score decreased from 90.95% to 90.63%

#### School Summary Analysis
![PyCitySchools_Challenge_School1](https://user-images.githubusercontent.com/78664640/112765322-b0fdd600-8fda-11eb-8db3-ad14709ecc25.png)

#### School Summary Analysis with THS 9th Grade Excluded
![PyCitySchools_Challenge_School2](https://user-images.githubusercontent.com/78664640/112765337-b8bd7a80-8fda-11eb-81e6-ed9a5eb8196f.png)

### Thomas High School Performance 
Although THS's overall passing score decreased from 90.94% to 90.63% after the ninth graders' scores were excluded, it was still the second top-performing school as shown in the images below.   

#### Top-Performing Schools Analysis
![PyCitySchools_Challenge_TopSchools1](https://user-images.githubusercontent.com/78664640/112765670-3c2b9b80-8fdc-11eb-8cbd-1d965f70b800.png)

#### Top-Performing Schools Analysis with THS 9th Grade Excluded
![PyCitySchools_Challenge_TopSchools2](https://user-images.githubusercontent.com/78664640/112765686-46e63080-8fdc-11eb-8f4f-001d787c8a11.png)

### Impact on Scores 
#### Math Scores by Grade
The analysis on math scores by grade was not impacted since it was on a grade level, but the images below show that the THS ninth graders' math score was excluded in the updated analysis.

![PyCitySchools_Challenge_GradeMath1](https://user-images.githubusercontent.com/78664640/112766227-bfe68780-8fde-11eb-846b-bc1950457cac.png)

![PyCitySchools_Challenge_GradeMath2](https://user-images.githubusercontent.com/78664640/112766235-c96fef80-8fde-11eb-846a-2014887fbcb2.png)

#### Reading Scores by Grade 
The analysis on reading scores by grade was not impacted since it was on a grade level, but the images below show that the THS ninth graders' reading score was excluded in the updated analysis.

![PyCitySchools_Challenge_GradeReading1](https://user-images.githubusercontent.com/78664640/112766241-d391ee00-8fde-11eb-9322-3b6e733390d1.png)

![PyCitySchools_Challenge_GradeReading2](https://user-images.githubusercontent.com/78664640/112766247-db519280-8fde-11eb-800b-70cb999dac3d.png)

#### Scores by School Spending
Since THS was in the $630-644 spending range, the analysis on scores by school spending had a very small impact for that range. The metrics were impacted as follows:
- Average Math Score decreased from 78.51% to 78.50%
- Average Reading Score increased from 81.62% to 81.64%
- Passing Math Score decreased from 73.48% to 73.46%
- Passing Reading Score decreased from 84.39% to 84.32%
- Overall Passing Score decreased from 62.86% to 62.78%

##### Scores by School Spending Analysis
![PyCitySchools_Challenge_Spending1](https://user-images.githubusercontent.com/78664640/112766664-b0683e00-8fe0-11eb-9b6a-7fc0e5aa2e5a.png)

##### Scores by School Spending Analysis with THS 9th Grade Excluded
![PyCitySchools_Challenge_Spending2](https://user-images.githubusercontent.com/78664640/112766668-b827e280-8fe0-11eb-97eb-1aa84d0c9773.png)

#### Scores by School Size 
Since THS was in the medium school size range, the analysis on scores by school size had a small impact for that range. The metrics were impacted as follows:
- Average Math Score decreased from 83.37% to 83.36%
- Average Reading Score increased from 83.86% to 83.87%
- Passing Math Score decreased from 93.60% to 93.58%
- Passing Reading Score decreased from 96.79% to 96.73%
- Overall Passing Score decreased from 90.62% to 90.56%

##### Scores by School Size Analysis
![PyCitySchools_Challenge_Size1](https://user-images.githubusercontent.com/78664640/112766870-bb6f9e00-8fe1-11eb-98d2-b1a0a781a270.png)

##### Scores by School Size with THS 9th Grade Excluded
![PyCitySchools_Challenge_Size2](https://user-images.githubusercontent.com/78664640/112766878-c32f4280-8fe1-11eb-9956-a3d7db2bec27.png)

#### Scores by School Type 
Since THS was is a Charter, the analysis on scores by school type had a small impact for that type on a few of the metrics. The metrics were impacted as follows:
- Average Math Score remained the same at around 83.47%
- Average Reading Score remained the same at around 83.90%
- Passing Math Score decreased from 93.62 to 93.61%
- Passing Reading Score decreased from 96.59% to 96.55%
- Overall Passing Score decreased from 90.43% to 90.39%

##### Scores by School Size Analysis
![PyCitySchools_Challenge_Type1](https://user-images.githubusercontent.com/78664640/112767092-beb75980-8fe2-11eb-9e1d-cfac6f546f13.png)

##### Scores by School Size with THS 9th Grade Excluded
![PyCitySchools_Challenge_Type2](https://user-images.githubusercontent.com/78664640/112767100-c676fe00-8fe2-11eb-9487-c14be80c1186.png)

## Summary
The results have shown that the updated analysis was slightly impacted after the ninth grade score for THS were excluded, with some major changes to the following metrics:
- The school summary was impacted the most with a 0.08% decrease for the passing math score, 0.29% decrease for the passing reading score and a 0.32% decrease for the overall passing score. 
- THS's overall passing score experienced a major change with a 0.31% decrease from the initial analysis. 
- The scores by spending analysis experienced a 0.07% decrease for the passing reading score and 0.08% decrease for the overall passing score. 
- The scores by school size analysis experienced a 0.06% decrease for both the passing reading score and the overall passing score.

The summary above shows that the passing reading score and overall passing score were the metrics that experienced the most change. 