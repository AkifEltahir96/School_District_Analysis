# Overview

The purpose of this analysis is to provide evidence regarding a case of academic dishonesty in terms of the reading and math grades of ninth graders at Thomas High School (THS). This analysis will help the school board understand the degree of any possible academic dishonesty conducted. To complete our goal, I will replace the reading and math scores for THS and complete an analysis of entire school district to compare the scores with and without THS.

# Results
## How is the district summary affected?
District Summary:
![District Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/district_summary_df.png)
Replacing the ninth graders' reading and math scores had a minimal influence on the overall scores (Average Math Score, Average Reading Scores, % Passing Math, % Passing Reading, and % Overall Passing). For example, for the district_summary_df in the module analysis (with THS 9th graders) yields an Average Math Score of 79.0 %. However, the same dataframe (district_summary_df) for the challenge analysis yields an Average Math Score of 78.9 %; this is only a 0.1 % difference. Similar small differences are observed for the other overall scores as seen in the screenshot above.

## How is the school summary affected?
School Summary:
![School Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/school_summary_df.png)
Similar to the district summary, replacing the ninth graders' reading and math scores had a minimal influence on the overall scores (Average Math & Reading, % Passing Math & Reading, and % Overall Passing).  For example, the per_school_summary_df in the (file name) for the module analysis (with THS 9th graders) yields an Average Math Score of 83.42 %. However, the same dataframe (district_summary_df) for the challenge analysis yields an Average Math Score of 83.35 %; this is only a 0.07 % difference. Similar small differences are observed for the other overall scores as seen in the screenshot above.

## How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to other schools?
Grade Replacement:
![School Preformance](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/school_performance.png)
Replacing the THS 9th graders' reading and math scores does not change THS's preformance amongst all of the schools in the district. In both analyses (with and without replacement), THS students remain in the top 5 schools for % Overall Passing. Even without the potential academic misconduct, students from THS preform very well in comparison to other schools.

## How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
  - Math Scores: All other math averages for each school by grade remain unchanged. Only difference is that THS 9th graders have a null value in the challenge analysis (vs. 83.6 % in the module analysis). ![Math Scores](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/math_scores_by_grade_df.png)
  - Reading Scores: All other reading averages for each school by grade remain unchanged. Only difference is that THS 9th graders have a null value in the challenge analysis (vs. 83.7 % in the module analysis). ![Reading Scores](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/reading_scores_by_grade_df.png)
- Scores by school spending: Scores by school spending do not change after replacing the ninth-grade scores. ![Spending Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/spending_summary_df.png)
- Scores by school size: Scores by school size do not change after replacing the ninth-grade scores ![Size Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/size_summary_df.png)
- Scores by school type: Scores by school type do not change after replacing the ninth-grade scores ![Type Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/type_summary_df.png)

# Summary

In conclusion, replacing the 9th grade THS students' reading and math scores had very little impact on the overall math and reading preformance across the school district. However, I will note four changes below.

District Summary (Points 1 to 3): ![District Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/district_summary_df.png)
School Summary (Point 4): ![School Summary](https://github.com/AkifEltahir96/School_District_Analysis/blob/main/Pictures/school_summary_df.png)
  1) Before replacing THS ninth-graders math and reading scores, the % Passing Math is 75.0 %. However, after replacement, this drops to 74.8 %.
  2) Before replacing THS ninth-graders math and reading scores, the % Overall Passing is 65.2 %. However, after replacement, this drops to 64.9 %.
  3) Before replacing THS ninth-graders math and reading scores, the % Passing Reading is 85.8 %. However, after replacement, this drops to 85.7 %.
  4) Before replacing THS ninth-graders math and reading scores, the % Passing Math is 93.27 %. However, after replacement, this drops to 93.18 %.
