# School_District_Analysis
## Overview of Project
This project consisted of a thorough cleaning of possibly corrupt grades and the repeat of an in-depth analysis that was done on the scores of the school district overall including their budgets, spendings, averages, and percentages.

### Purpose
The purpose of this project was to efficiently eliminate the possibly corrupt math and reading grades of a particular high school and then use the remaining data to re-determine a number of factors like the percentage of students in each school that are passing each section as well as the averages. Additionally, there was also an in-depth look at all of the scores in a variety of ways: school size, school spending, and even school type. 

### Outcomes and Analysis

## How is the district summary affected?
- The district summary as a whole showed a few minor changes within its dimensions. The main changes within the district summary were:
    - A decrease in each category, however it was less than a .5% change in each one
    - The biggest deficit came from the '% Overall Passing Percentage' category with a change of (-.3%)
- Updated:
![District_Summary_New](https://user-images.githubusercontent.com/73874291/101979022-5351a380-3c0e-11eb-90a5-4c684dc36611.png)
- Previous:
![District_Summary_Prev](https://user-images.githubusercontent.com/73874291/101979025-55b3fd80-3c0e-11eb-83e9-673072485051.png)
    
## How is the school summary affected?
- After the re-analysis using only the upperclassmen scores and class counts (10th - 12th grade,) the school summary was very much affected for Thomas High School:
    - The percentages of passing reading, passing math, and overall passing for Thomas High School went up dramatically.
    - There was a (+26%) increase in the percentage of students passing math
    - There was a (+27%) increase in the percentage of students passing reading 
    - And the largest increase came in the overall passing column with a nearly 35% increase. 
- Updated:
![School_Summary_New](https://user-images.githubusercontent.com/73874291/101978881-51d3ab80-3c0d-11eb-9859-66aebfe238a9.png)
- Previous:
![School_Summary_Prev](https://user-images.githubusercontent.com/73874291/101978885-54360580-3c0d-11eb-9e6d-8a8c3ceabce0.png)
        
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Replacing the scores and re-evaluating the grades had a very strong affect relative to other schools. 
    - After the re-analysis, Thomas High School was listed as #2 in the 'Top 5' Performing schools. 

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
- The main affect that replacing the ninth-grade scores had on the math and reading scores by grade was the fact that now in the array, the 9th grade column for Thomas High School is replaced by NaN. 
### Scores by school spending
- In the school spending category, there is a very small change in the actual averages and percentages in the category of $630 - $644 which is where Thomas High School falls. However, once the data was formatted and the numbers and percentages rounded out, the amounts remained the same as the  previous. 
### Scores by school size
- Similarly the school size actual total averages and percentages once rounded and formatted remained the same as the previous data numbers. However, in the full unedited numbers, there was a decrease in all categories in the 1000-2000 student bin where Thomas High School belongs. 
### Scores by school type
- Additionally, the 'Charter' school type was also affected in the same way as listed above. Small changes to the raw numbers, but once formatted remained the same as previous. 

- Updated:
![School Type New](https://user-images.githubusercontent.com/73874291/101978980-0b328100-3c0e-11eb-8480-9b522c97e8f8.png)
-Previous:
![School Type Prev](https://user-images.githubusercontent.com/73874291/101978983-11c0f880-3c0e-11eb-833e-7bf2909c8fca.png)

### District Analysis Summary
After completing the district analysis without the grades of the ninth grade class of Thomas High School, there were a few changes that stood out amongst the others as exponential to actual results of the analysis. First, there were the two columns within the school summary data frame that showed significant increases in both students passing math and students passing reading percentages. This led to the next large and very influential change, the overall passing percentage increase. After the removal of the ninth grade class cores, there was also the increase the came in the '% of Overall Passing' that increased by nearly 35% - A major change that affects the entire outlook of that report. When looking over the other results of the analysis, the math and reading scores by grade were affected by the changes as well. At this point, the 9th grade for Thomas High School is merely listed as 'NaN' so is not even a factor within that table of values.
