# School_District_Analysis


### Overview of the School District Analysis
The `students_complete.csv` file shows evidence of **academic dishonesty**; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards We have to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we've replaced the math and reading scores, we will repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.
#

#### How is the district summary affected?
Let's take a look at the data **before** and **after** making the changes:

##### Before:
<img src="/Resources/DistrictSummary_Before.png" alt="district_summary_before"><br>
##### After:
<img src="/Resources/DistrictSummary_After.png" alt="district_summary_after"><br>

As we can see, after making the required changes in the data, the affected columns were:
```
- Average Math Score: Decreased by 0.12%
- % Passing Math:     Decreased by 0.27%
- % Passing Reading:  Decreased by 0.11%
- % Overall Passing:  Decreased by 0.46%
```


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


The affected columns decreased by 0.12%. Here is a breakdown of that calculation:

#
#### How is the school summary affected?


#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
- Scores by school spending
- Scores by school size
- Scores by school type

### Results
