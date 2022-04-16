# School_District_Analysis

## Overview of the school district analysis:
The purpose of this project was to take an existing Pandas script, update the data frame to ignore the data that could be incorrect (in this case it was provided that the 9th grade data from one of the schools had evidence of academic dishonesty) and re-run the analysis on rest of the data.

## Results:
The results of the analysis are as follows:
* How is the district summary affected?
    - % math, % reading and % overall passing results dropped slightly

### Screenshots of the district summary
Original Aanalysis
<img src="/Resources/district_summary_original.png" >

Updated Analysis
<img src="/Resources/district_summary_new.png" >

* How is the school summary affected?
    - % math, % reading and % overall passing results dropped slightly but have insignificant impact on the results for Thomas High School.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - It did not impact the rank of Thomas High School as it was still second ahead of Griffin High School for % overall passing results. However, the gap between the two schools narrowed a bit.
    - If we just compare the % of students who passed reading, Thomas High School now is behind the Griffin High School
* How does replacing the ninth-grade scores affect the following for Thomas High School:
    - Math and reading scores by grade: average math scores deteriorated so slightly while the reading scores got better by a very small margin
    - Scores by school spending: no significant impact
    - Scores by school size: no significant impact
    - Scores by school type: no significant impact

    ### Screenshots of the school summary & top five schools
Original Aanalysis
<img src="/Resources/top_five_original.png" >

Updated Analysis
<img src="/Resources/top_five_new.png" >

## Summary: 
In summary, updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs did not have a significant impact on the ranking of Thomas High School. As follows are the four changes that could be noted in the updated analysis:
- For Thomas High School the average math scores dropped slightly while the reading scores got better by a very small margin
- % math, % reading and % overall passing results for Thomas High School dropped slightly
- % math, % reading and % overall passing results for the school district dropped slightly
- Thomas High School is now behind the Griffin High School for % of students that passed reading