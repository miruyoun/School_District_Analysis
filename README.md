# School District Analysis

## Overview
For this challenge, a school board has notified its employees that there was a possibility of academic dishonesty in the reading and math scores of ninth-graders at Thomas High School. An employee has asked me to replace the math and reading scores for Thomas High School night graders with NaNs while keeping the integrity of the rest of the data. After I replaced all Thomas High School ninth graders' scores with NaN's, I reconducted the school district analysis to see how much it changed the overall analysis.

## Results
* For the most part, there was a small decrease in some values of the district school summary, and with the removal of Thomas High School ninth graders' scores the...
  * Average math score went down from 79.0 to 78.9.
  * Average reading score stayed the same.
  * Math passing percentage went down from 75.0% to 74.8%.
  * Reading passing percentage went down from 86.0% to 85.7%.
  * Overall passing percentage went down from 65% to 64.9%.

### Original District Summary
![original_district](https://user-images.githubusercontent.com/106292020/175364485-af95f227-19c8-423d-9033-d1eed4722b95.png)

### Changed District Summary
![changed_district](https://user-images.githubusercontent.com/106292020/175364491-c2d5af4e-4bf9-45cd-9b30-d829661227cf.png)

* In the school summary, there were three values affected, namely math, reading, and overall passing percentages.
  * Math passing percentage greatly increased from 66.9% to 93.2%
  * Reading passing percentage greatly increased from 69.7% to 97.0%
  * Overall passing percentage greatly increased from 65.1% to 90.6%

### Original School Summary
![original_school_summary](https://user-images.githubusercontent.com/106292020/175363174-b6d347d9-967a-4c58-a01e-3743af570705.png)

### Changed School Summary
![changed_school_summary](https://user-images.githubusercontent.com/106292020/175363189-0ed97cea-17fd-42f9-9be9-0e328f8c879f.png)

* Changing the ninth graders' math and reading scores improved Thomas High School's overall performance as they went from having the 8th highest overall passing rate to having the 2nd highest overall passing rate.

### Sorted Overall Passing Rate
![top_sort](https://user-images.githubusercontent.com/106292020/175364829-5a3ca683-e8d6-44eb-bfca-d1dfaf4739c7.png)

* By replacing the ninth graders' score...
  * Math and reading scores by grade did not change but only for Thomas High School's ninth-graders as their math and reading scores just changed to NaNs.
  * Scores by school spending did not change.
  * Scores by school size did not change.
  * Scores by school type did not change.

## Summary
To summarize my findings, after replacing Thomas High School's ninth graders' scores with NaNs, there were slight changes to the school district analysis. First, the average math score, percentage of students passing math, percentage of students passing reading, and percentage of students passing overall went down by a few decimals. Furthermore, I noticed a significant increase in the math, reading, and overall passing percentages at Thomas High School after eliminating the ninth graders' scores. Thus, placing them second in the district. Lastly, by replacing the ninth graders' scores, it did not affect the scores by school spending, scores by school size, and scores by school type. For math and reading scores by grade, the cell with Thomas High School's ninth grades scores became NaN.
