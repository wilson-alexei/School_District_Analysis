# Schoo_District_Analysis
Module 4 Challenge is utilizing `Anaconda`, `Jupyter Notebook`, `Pandas` and `Python`

## Overview of the school district analysis 
Due to evidences of academic dishonesty by the ninth graders in Thomas High School, the school board has notified and requested Maria to redo the school district analysis by replacing ninth-grade reading and math scores to a "NaN" or "Not a Number". We also need to exclude Thomas High School's ninth-graders from the school district analysis. The purpose of this analysis is to create a more accurate outcome and write a report for the school district analysis to describe how these changes affected the overall analysis.

The school district analysis will include: 
  * District Summary
  * School Summary
  * Top and Bottom 5 Performing Schools, based on the overall passing rate
  * Average Math Score from each grade level from each school 
  * Average Reading Score from each grade level from each school
  * Scores by School Spending per Student, School Size, and School Type 

## Results
*How is the district summary affected?*
Before cleaning up the data, the district summary:
<img width="953" alt="District Before Clean Up" src="https://user-images.githubusercontent.com/95068439/150623149-14a4e67a-80ab-40b5-92f5-5cc4613c98c4.png">
After cleaning up the data: 
<img width="920" alt="District After Clean Up" src="https://user-images.githubusercontent.com/95068439/150623141-a71e4d46-2878-4941-b4c4-5600504b976e.png">

CHANGE: Overall, there is no significant changes on the district summary. As we can see, there is a slight drop on *Average Math Score, *% Passing Math, and *% Passing Reading which also result to a small drop on the *% Overall Passing.

*How is the school summary affected?*
Before cleaning up the data, the school summary:
<img width="481" alt="School Before Clean Up" src="https://user-images.githubusercontent.com/95068439/150623380-8dc5a4a0-1e5e-4d30-a319-174d140bdaf2.png">

After cleaning up the data, the school summary:
<img width="995" alt="School After Clean Up" src="https://user-images.githubusercontent.com/95068439/150623381-affa0101-7b2d-4f27-a98c-631d7481d842.png">

CHANGE: With the clean up on the Thomah High School's ninth graders, it seemed obvious that the academic dishonesty significant brought up the school's overall passing percentages. As we can see from the rankings, Thomas High School was ranked second with *Overall Passing* of 91. However, after the data clean-up, Thomas High School's rank significant drop to number 8 with an *Overall Passing* of 65.

*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?*
- Replacing Thomas High School's ninth graders scores significantly dropped the school's Overall Passing Percentage from 91 to 65 which brings down the school's ranking in the district from *2nd* to *8th*. This can be a strong evidence of academic dishonesty as the other grades are not performing as well as the ninth grades

*How does replacing the ninth-grade scores affect the following:*
- Math and reading scores by grade: Thomas High School's ninth grade math and reading scores has been altered to *NaN* or 'Not a Number' which is equivalent to 0 which means that they are all failed the courses. This outcome results to a big downfall in the overall passing percentage of the school. The student count for the analysis also drops from 1635 to 1174. 

Thomas High School: 1635 Counts

<img width="287" alt="Screen Shot 2022-01-21 at 22 54 54" src="https://user-images.githubusercontent.com/95068439/150623858-b374ae97-dbf0-4236-af5b-0e696d96b681.png">
Thomas High School: 1174 Counts

<img width="520" alt="Screen Shot 2022-01-21 at 22 56 57" src="https://user-images.githubusercontent.com/95068439/150623861-2d93a816-34f3-4f48-b018-659ad46b38d3.png">

- Scores by school spending: Thomas High School falls on the $630-644 spending range per student 
<img width="1009" alt="Thomas High School Spending" src="https://user-images.githubusercontent.com/95068439/150626049-906c031a-805f-4c26-b638-34774211e392.png">


- Scores by school size: By removing Thomas High School's ninth-graders' data, the school's % Passing Math, % Passing reading, and % Overall Passing significantly dropped and as their school size has been altered and now they are allocated in the Medium Size 
<img width="753" alt="Size Summary" src="https://user-images.githubusercontent.com/95068439/150625784-1753dc92-86ad-4968-9b41-f2e18b65974e.png">

- Scores by school type: Thomas High School is part of the Charter type and below are the changes before and after data clean-up:
**Before**
<img width="783" alt="Type Before Clean Up" src="https://user-images.githubusercontent.com/95068439/150625555-2250827d-98b0-433c-954c-9a5bb67e36ce.png">
**After**
<img width="711" alt="Type After Clean Up" src="https://user-images.githubusercontent.com/95068439/150625596-2da85aa7-7104-44c3-a30d-bcd7a95a94cd.png">

## Summary
The ninth-graders' math and reading grades from Thomas High School have been altered to 'NaN' as they were suspicious of academic dishonesty. As a result, the student count for the high school is reduced as well s the school's Average Math and Reading Scores which also lead to a lower Passing Math and English percentage which is also lead to lower Overall Passing percentage.   
