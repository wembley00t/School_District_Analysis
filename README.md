# School_District_Analysis

## Overview School_District_Analysis
This is an updated school district analysis updated by removing the ninth grade math and reading scores for Thomas High School with NaNs.  
The updated analysis will include the following metrics for review:

  *  The district summary
  *  The school summary
  *  The top 5 and and bottom 5 performing schools, based on the overall passing rate
  *  The average math score for each grade level from each school
  *  The average reading score for each grade level from each school
  *  The scores by school spending per student, by school size and by school type.

The analysis will compare the updated metrics after the correction for Thomas High School with the original school district analysis.

## School District Analysis Results

### District Summary

Below is a comparison of the original school district summary to the updated district summary.

Original

![Org School District](https://user-images.githubusercontent.com/100876517/163746328-0ae073b4-362e-4e43-9bab-79eebd6317c2.png)

Updated

![Updated School District](https://user-images.githubusercontent.com/100876517/163746321-83f01945-00e9-4efc-8b5a-446e96b92bc2.png)

The total students decreased by 461 or 1.2%.  This small decrease did not materially impact the overall results.  This can be seen by comparing 
the metrics.  The most noted change is the change in overall passing from 65.2% to 64.1%.

### School Summary

Original School Summary
![Org School Summary](https://user-images.githubusercontent.com/100876517/163747852-aade38ce-ad0d-462a-a0fc-d44717547c7d.png)


Updated
![Updated School Summary](https://user-images.githubusercontent.com/100876517/163747508-220ad36d-ad68-4175-9bfa-edef76dc5e34.png)

Thomas High School is the only school with changes.  As with the updated school district, the updated overall school summary is materially the same.

### Thomas High School Performance
Thomas High School reflects much better performance when the ninth graders with NaNs are removed.  While the average math and reading score do not change,
the % passing math, reading and overall passing show a significant improvement.  The original passing percentages for these categories were 65% to 70%.
With the update, the passing percentages for these categories improves to 91% to 97%.

### Updated Scores after Replacing Ninth-Grade Scores

#### Math Grades
Original Math Grades by Grade


![orig math grades by grade](https://user-images.githubusercontent.com/100876517/163749378-90cb1091-0030-4c3c-bd4f-d27fbe814e65.png)

Updated Math Grades by Grade


![updated math grades](https://user-images.githubusercontent.com/100876517/163749395-0374e7d1-2604-4b03-b662-b320a7bbe65b.png)

#### Reading Grades
Original Reading Grades by Grade


![Orig reading grades by grade](https://user-images.githubusercontent.com/100876517/163749403-9795ec31-ace8-42e2-852c-93835318f9e4.png)

Updated Reading Grades by Grade


![updated reading grades](https://user-images.githubusercontent.com/100876517/163749410-a4c6b828-58b7-44eb-8576-8a318bb05cef.png)

#### Scores by School Spending
Original

![Orig Scores by spending](https://user-images.githubusercontent.com/100876517/163750133-6a3158f3-05cc-4e64-869c-24f457217bc7.png)

Updated

![Updated scores by school spending](https://user-images.githubusercontent.com/100876517/163750147-541d0e47-b54d-4da0-8fb8-c1321456a827.png)



#### Scores by School Size

Original

![Orig scores by school size](https://user-images.githubusercontent.com/100876517/163750106-2246f04e-e457-498f-8d27-9405ee6f8789.png)

Updated

![Updated scores by school size](https://user-images.githubusercontent.com/100876517/163750118-3fde4caa-8e4e-495f-b398-42526809876e.png)

#### Scores by School Type

Original

![orig scores by school type](https://user-images.githubusercontent.com/100876517/163750079-535d52c4-b152-4cc2-9493-ff844fd43428.png)

Updated

![Updated scores by school type](https://user-images.githubusercontent.com/100876517/163750093-cbd2a698-c09d-4216-a4f3-ecf73ebd8293.png)
 
## School District Analysis Summary

The code used for this specific election-audit can be modified and used in any election.  The code can be modified to include additional voter data or to combine the county and candidate data to show trends for candidate vote by county. 
