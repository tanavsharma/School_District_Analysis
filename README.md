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
---
#### How is the school summary affected?

Let's take a look at the data **before** and **after** making the changes:

##### Before:
<img src="/pictures/headings.png" alt="headings"><br>
<img src="/pictures/school_summaryTHS_before.png" alt="school_summary_before"><br>

##### After:
<img src="/pictures/headings.png" alt="headings"><br>
<img src="/pictures/school_summaryTHS_after.png" alt="school_summary_after"><br>

As we can see, the sumarry of school **Thomas High School** was affected significantly. This is due to the fact that, none of the records for grade 9 were considered. As mentioned before, the scores for grade 9 seemed altered, so they couldn't be included and had to be removed from the data set. The affected columns and their percent change are listed below.

```
- Average Math Score      : Decreased by 0.07%
- Average Reading Score   : Increased by 0.05%
- % Passing Math          : Decreased by 28.26%
- % Passing Reading       : Decreased by 28.40%
- % Overall Passing       : Decreased by 28.44%
```




#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type



### Screenshots & Other Breakdowns

#### District Summary Calculations
- Average Math Score:<br>
  <img src="/formulas/average_math_formula.png" alt="average_math_formula" width="250">
  
---
- % Passing Math:<br>
  <img src="/formulas/passing_math_formula.png" alt="passing_math_formula" width="250">

---
- % Passing Reading:<br>
  <img src="/formulas/passing_reading_formula.png" alt="passing_reading_formula.png" width="250">

---  
- % Overall Passing:<br>
  <img src="/formulas/overall_passing_formula.png" alt="overall_passing_formula.png" width="250">

#

#### School Summary Calculations
- Average Math Score:<br>
  <img src="/formulas/average_math_formula.png" alt="average_math_formula" width="250">
  
---
- % Passing Math:<br>
  <img src="/formulas/passing_math_formula.png" alt="passing_math_formula" width="250">

---
- % Passing Reading:<br>
  <img src="/formulas/passing_reading_formula.png" alt="passing_reading_formula.png" width="250">

---  
- % Overall Passing:<br>
  <img src="/formulas/overall_passing_formula.png" alt="overall_passing_formula.png" width="250">


### Results
