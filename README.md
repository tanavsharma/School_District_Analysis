# School_District_Analysis


### Overview of the School District Analysis
The `students_complete.csv` file shows evidence of **academic dishonesty**; specifically, reading and math grades for **Thomas High School** ninth graders appear to have been altered. The school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards We have to **replace** the **math** and **reading** scores for Thomas High School with **NaNs** while keeping the rest of the data intact. Once we've replaced the math and reading scores, we will repeat the **school district analysis** and write up a report to describe how these changes affected the overall analysis.

#

#### How is the district summary affected?
Let's take a look at the data **before** and **after** making the changes:

##### Before:
<img src="/pictures/DistrictSummary_Before.png" alt="district_summary_before"><br>

##### After:
<img src="/pictures/DistrictSummary_After.png" alt="district_summary_after"><br>

As we can see, after making the required changes in the data, the affected columns were:
```
- Average Math Score:    Decreased by 0.12%
- Average Reading Score: Stayed The Same
- % Passing Math:        Decreased by 0.27%
- % Passing Reading:     Decreased by 0.11%
- % Overall Passing:     Decreased by 0.46%
```
*You can find a breakdown of these numbers at the end of this document.*


---
#### How is the school summary affected?

Let's take a look at the data **before** and **after** making the changes:

##### Before:
<img src="/pictures/headings.png" alt="headings"><br>
<img src="/pictures/school_summaryTHS_before.png" alt="school_summary_before"><br>

##### After:
<img src="/pictures/headings.png" alt="headings"><br>
<img src="/pictures/school_summaryAfter.png" alt="school_summary_after"><br>

As we can see, the sumarry of school **Thomas High School** was not affected significantly. This is due to the fact that, none of the records for grade 9 were considered, but for grade 10, 11 and 12 were considered. Onlu the grade 9 math and reading scores were removed from the data set. The affected columns and their percent change are listed below.

```
- Average Math Score      : Decreased by 
- Average Reading Score   : Increased by 
- % Passing Math          : Decreased by 
- % Passing Reading       : Decreased by 
- % Overall Passing       : Decreased by 
```

*You can find a breakdown of these numbers at the end of this document.*

---

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Let's take a look at the summary of all schools, and compare them to Thomas High School. Here is the chart, with all the schools and their scores after the adjustment.

<img src="/formulas/school_summary_allSchools.png" alt="average_math_formula">

To make our life easier, lets calculate the mean for each column and compare those values to the value of Thomas High School, and detirmine how the schools performace was affected and by how much. 

Here is a chart of the means for all schools for each column:
<img src="/pictures/allschools_average_scores.png" alt="allschools_average_scores">

Just Thomas High School (Before):
<img src="/pictures/THS_Headers.png" alt="allschools_average_scores">
<img src="/pictures/THS_Scores_Before.png" alt="allschools_average_scores">

Just Thomas High School (After):
<img src="/pictures/THS_Headers.png" alt="allschools_average_scores">
<img src="/pictures/THS_Scores_After.png" alt="allschools_average_scores">

Based on the images above, it is evident that with the altered data from grade niners, it put **Thomas High School** in top 5 highest performing schools. However, once removing the altered data, we can see that Thomas High School scores suffered significantly, to a point bringing the school in bottom lowest.

We can also see that their percentages dropped below the average for each category (math and reading).
#

#### How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade  

  <img src="/pictures/ScoresByGrade.png" alt="math_scores_by_grade"><br>
 
  
  
- Scores by school spending
  
- Scores by school size
  
- Scores by school type



### Screenshots & Other Breakdowns

#### District Summary Calculations
  <img src="/formulas/districtFormulas.png" alt="average_math_formula" width="700">
  
#

#### School Summary Calculations
<img src="/formulas/schoolFormulas.png" alt="average_math_formula" width="700">

#



### Results
