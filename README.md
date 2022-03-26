# School District Analysis

## Overview
  In this challenge, I was asked to re-analyze student data after it was determined that ninth graders at Thomas High School engaged in academic dishonesty.  In doing so, I needed to remove scores from these students based on scholol and graade.  Then, I needed to re-calculate averages for reporting.  Finally, I needed to redo the analysis for factors like school spending, school size, and type of school.

## Results

  -  The district summary shows one discernable difference in the totals.  The number of records in the data offset the removal of one's school's ninth grade class,except in the case of Average Math Score, which dropped by a tenth of a point.  Below are the summaries for before and after:

<img width="892" alt="District_Summary_Before" src="https://user-images.githubusercontent.com/99457275/160257503-eaf0c0ad-77b3-411a-84bf-83f3b7781a56.png">

<img width="895" alt="District_Summary_After" src="https://user-images.githubusercontent.com/99457275/160257507-1ae095ed-63c2-4c9a-a69b-0f94711d9132.png">

  -  The Per School Analysis shows a small change in the totals after removing the Thomas High School ninth graders.  Below is a before and after of the dataframe:

<img width="899" alt="Per_School_Analysis_Before" src="https://user-images.githubusercontent.com/99457275/160256890-31ad0310-18ad-403a-badb-13aa500bbccc.png">

<img width="907" alt="Per_School_Analysis_After" src="https://user-images.githubusercontent.com/99457275/160256896-73129453-135f-4676-a2d2-6e721d5d4cda.png">

  All of the averages went down slightly, except Average Reading Score.

  - Given the negligible changes in the average scores, Thomas High Scool's performance in relation to the other schools remains unchanged, as can be seen below, with before on the left, and after on the right.

<img width="1867" alt="Top_Schools_Before_After" src="https://user-images.githubusercontent.com/99457275/160257708-d25e9eff-b974-4fa3-8bd9-d1ae86d30d95.png">


  - In the dataframe broken down by school and grade, the difference is that the Thomas High ninth grade scores are switched to "nan".  You can see each below, with before on the left, and after on the right:

  <img width="1042" alt="By_School_Grade_Math_Before_After" src="https://user-images.githubusercontent.com/99457275/160257343-92eba204-eb53-4a5e-9e12-724f1ad4eea3.png">

  <img width="997" alt="By_School_Grade_Reading_Before_After" src="https://user-images.githubusercontent.com/99457275/160257353-7bf59844-9145-4a0d-a963-bd6ed4d79757.png">
  
  - The averages by School Spending also remain significantly unchanged.  Below is the before (left) and after (right):

<img width="1840" alt="Averages_By_School_Spending" src="https://user-images.githubusercontent.com/99457275/160257804-406ba94c-a75c-4e0c-8099-7bd362d6d761.png">

  - The averages by school size tell a similar story.  This data has been rounded to industry standard specifications.  Once again, before is on the left and after is on the right.

<img width="1788" alt="Averages_By_School_Size" src="https://user-images.githubusercontent.com/99457275/160257889-a803d9a4-9aee-4cc4-ab36-58f0d78ec38c.png">

  - This trend continues when the data is sliced by school type.  Below, before is shown on the let, and after is shown on the right:

 <img width="1720" alt="Averages_By_School_Type" src="https://user-images.githubusercontent.com/99457275/160257934-7d9bfabf-5330-4bcb-9dcb-24f99a7048cb.png">

## Summary
In conclusion, changes were seen mostly in the per school analysis.  We can see that averages (Average Math Score and all passing percentages) went down slightly, except Average Reading Score, which went up.  We also saw one change in the district summary, where removal of Thomas High ninth graders meant a tenth-of-a-point drop in Average Math Score.  Another change was in the analysis by school and grade, which showed the obvious null values for ninth graders at Thomas High after that data was removed.  A lot of the unchanged information can be attributed to sample size and rounding done for reporting purposes.  
