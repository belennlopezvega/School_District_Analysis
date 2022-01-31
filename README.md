# School District Analysis

## Overview of School District Analysis
The purpose of this analysis is to uphold state-testing standards after the school board learned about reading and math academic dishonesty at Thomas High School. To do this, we will replace the 9th grade Thomas High School math and reading scores with NaNs while keeping the rest of the data intact. Once that's been done, we'll discuss how these changes have affected the overall analysis. 

## Results

### How the District Summary is Affected
Although minor, there were some subtle differences between the previous data, and the now altered data that correponds with there being some academic dishonesty when it comes to the district summary. The imagine below shows a comparison between the district summary before (first chart), and the district summary after (second chart) the Thomas High School math and reading scores were replaced with NaNs. When rounded, there is about a 1% difference between the Percentage Passing Math, Reading and Overall Passing but everything else remains about the same. 
![This is an image](https://github.com/belennlopezvega/School_District_Analysis/blob/main/PyCitySchools_DistrictSummary.png)

### How the School Summary is Affected
Looking at the School Summary is where we are able to see major differences between the data before, and the altered Thomas High School data after math and reading scores were replaced with NaNs. As show in the image below, we're able to see major differences in the last three columns, which are Percentage Passing Math, Percentage Passing Reading, and Percentage Overall Passing, respectively.
![This is an image](https://github.com/belennlopezvega/School_District_Analysis/blob/main/PyCitySchools_PerSchoolSummary.png)

### How Replacing Ninth Grade Math and Reading Scores Affects Thomas High School's Performance Relative to the Other School
As shown in the data and the image below, replacing the 9th grade math and reading scores had a major effect on Thomas High School. The first chart is before the data was altered and shows that Thomas High School was the second best top school right after Cabrera High School. In the second picture, they aren't even listed on the top 5 performing schools and as the data shows, they are actually at number 8. When compared to other schools, the difference is major. 
![This is an image](https://github.com/belennlopezvega/School_District_Analysis/blob/main/PyCitySchool_TopSchools.png)


### How Replacing the Ninth Grade Scores Affects the Following:

#### Math and Reading Scores by Grade
When looking at the math and reading scores by grade, there wasn't much difference between the data before and after it was altered. As only the 9th grade data was changed, you get NaNs when pulling up the reading and math scores by grade data in the 9th grade column. All else remains the same. 

#### Scores by School Spending
The scores by school spending do show some differences which align with what's stated above. The change is seen in the $630 - $644 spending range and there is about a 7% lower difference in the altered Percentage Passing Math, Percentage Passing Reading, and Percentage Overall Passing, compared to the original data.

#### Scores by School Size
The scores by school size also show some differences which align with what's stated above, and seems to be a commonality. The change is seen in the Medium (1000-2000) school size range and there is about a 6% lower difference in the altered Percentage Passing Math, Percentage Passing Reading, and Percentage Overall Passing, compared to the original data.

#### Scores by School Type
As for the school type scores, as Thomas High School is a Charter School, that is where the differences are. The differences are in the Percentage Passing Math, Percentage Passing Reading, and Percentage Overall Passing columns, and the difference is 3% - 4% lower on the altered data versus the original data.
 
## Summary
The major changes all seem to take place in the Percentage Passing Math, Percentage Passing Reading, and Percentage Overall Passing columns and not the average math and reading scores columns. Although we don't know the extent of the academic dishonesty that took place at Thomas High School, replacing the 9t grade math and reading scores with NaNs did prove to make an overall difference. As expected, the difference was hit the hardest at the school as it changed it's place in the overall ranking, but it was also subtly seen in the district as a whole which does have an affect in overall funding.
