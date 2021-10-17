# School_District_Analysis

## Overview
To provide the districst with a snapshot of their key metrics which include; the top and bottom 5 performing schools based on pass rate, average math ane reading scores by grade leve, and each schools performance based on budget, school size and type of school. After completing the initial analysis it was discovered there was potential academic dishonesty and that the grades were altered for the 9th graders at Thomas High School. Based on potential dishonesty I replaced the scores for the 9th graders with NaN and updated the analysis accordingly. The results of the findings are outlined below. 

## Results
- How is the district summary affected?
As you can see by the images below there changes in the distrcit summaries are very minor when removing the Thomas High School 9th grade reading and math scores. The % Overall passing column had the largest change with a decrease of only 3/10th of a percent. 
  
  Original
 
 ![Original_District_Summary](https://user-images.githubusercontent.com/88597956/137641977-68124cf4-e4e4-42ba-8097-a2a4369ae92b.PNG)

  Revised
  
  ![Revised_District _Summary](https://user-images.githubusercontent.com/88597956/137641988-12e78609-2fa1-45e6-9fd7-0f3d6aba99b8.PNG)

- How is the school summary affected?
Similar to the district analysis, the school summary was only minory affected when removing the 9th grade scores from Thomas High School. As shown below the largest decrease was only 3/10th of a percent. However, both the % Passing Reading and the % Overall Passing both decreased by 3/10th.

Original

![Original_School_Summary](https://user-images.githubusercontent.com/88597956/137642411-5955feb4-05a3-4d50-8aff-d43ea59f8d36.PNG)

Revised

![Revised_School_Summary](https://user-images.githubusercontent.com/88597956/137642414-1520cb1c-83b7-45f3-be2d-1832d5700dd1.PNG)

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
While Thomas High School's % Overall Passing did decrease slightly, it did not change their ranking amongst the other schools. They continue to be ranked the 2nd highest performing school in the district.

- How does replacing the ninth grade scores affect the following:
  - Math and reading scores by grade
  Naturally, since we replaced the 9th grade reading scores with NaN the 9th graders no longer have a score showing for Thomas High School.
  
  - Scores by school spending
  In the formatted summary, we do not see any change to the scores by the school spending as the changes were not enough to affect the round completed to this summary. When   looking at the scores showing multiple decimal places out we are able to see that the $630-$644 spending ranges was slightly affected by less than 1/10th on average.
  
  - Scores by school size
  Once again, no change shows to our formatted summary by school size. Should we take a deeper dive into the unformatted summary we would see that the medium school size would have been the one to show a minor decrease in the scores. 
  
  - Scores by school type
  Same with the other two summaries above, no change is noted on the school type summary. Since Thomas High School is a charter school we would notice score changes if we were to look at the unformatted summary.
  
## Summary
As previously mentioned, the changes to the various summaries were overall very minor. None the less there were changes as outlined below.

- The most obvious change to the summaries was to the scores by grade summaries, here you see nan in place of an actual score or a 0.
- The district summary had a decrease in the % overall passing of 3/10th.
- The school summary had a decrease in the % passing reading and % overall passing of 3/10th of a percent. 
- Within the analysis we had to do some additional coding to exclude the 9th grade population when calculating the reading and math scores. 
