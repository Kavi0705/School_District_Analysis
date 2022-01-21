# School_District_Analysis

## Background and Purpose

It has been discovered by the school board that there has been a case of academic dishonesty, specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The purpose of this analysis is to re-calculate the math and reading scores with the ninth scores at Thomas High School removed from the analysis. Then, these new figures will be used to generate an updated school district analysis in order to drive budgeting and set priorities for the schools within the district.

## Results

### District Summary

When assessing average scores and passing percentages among the 15 high schools in the school district, no significant changes were noted. The average math score dropped .1 point, the average reading score stayed the same, the percentage passing math, the percentage passing reading, and the overall passing percentage all dropped 1%. 

<img width="772" alt="District Summary" src="https://user-images.githubusercontent.com/93743169/150595508-b0d5ca65-afbd-456f-86e5-c178d7b3b790.png">


### School Summary

The re-calculation impacted the school summary statistics significantly. Thomas High Shcool how displayed 66.9% math passing percentage (previously 93.3%), 69.6% reading passing percentage (previously 97.3%), and an overall passing percent rate of 65.1% (previously 90.1%). This resulted in Thomas High School no longer being one of top 5 performing schools. 

<img width="771" alt="School Summary" src="https://user-images.githubusercontent.com/93743169/150596365-fb3e7755-c2f5-4344-8dce-02c5a8c153d1.png">

The re-calculation impacted the school summary statistics significantly. Thomas High Shcool how displayed 66.9% math passing percentage (previously 93.3%), 69.6% reading passing percentage (previously 97.3%), and an overall passing percent rate of 65.1% (previously 90.1%). This resulted in Thomas High School no longer being one of top 5 performing schools. 

#### Top Performign Schools

<img width="773" alt="Top 5 Schools" src="https://user-images.githubusercontent.com/93743169/150595654-a9b1cb77-b035-453e-af6b-63d2f941a21d.png">

#### Bottom Performing Schools

Good news -- it was not in the bottom 5 performing schools either.

<img width="774" alt="Bottom 5 Schools" src="https://user-images.githubusercontent.com/93743169/150595682-5f8e93f4-a1a0-474a-8e19-08734f54c17e.png">


### Average Math & Reading scores

The average math and reading scores remained unchanged, except for ninth graders in Thomas High School (as these were set to NaN values).

#### Average Math Scores by Grade Level for Each School

<img width="290" alt="Average Math Scores for each grade level by school" src="https://user-images.githubusercontent.com/93743169/150596108-753b3f7c-21d0-475f-94e6-2f3812347edc.png">

#### Average Reading Scores by Grade Level for Each School

<img width="293" alt="Average Reading Scores for each grade level by school" src="https://user-images.githubusercontent.com/93743169/150596167-cf039b6f-a50f-4618-a1c9-bd5daf82bccd.png">

### School Spending Summary

When reviewing the school spending summary data, there was a 6% decrease in passing math percentage, a 7% decrease in passing reading percentage, and a 7% decrease in overall passing percentage in the $630-$644 spending range per student.

<img width="776" alt="Scores by school spending per student" src="https://user-images.githubusercontent.com/93743169/150596418-17861b86-f238-4edc-9ec4-4cfec69bc467.png">

### Scores by Schools Size Summary

When reviewing the data for scores according to school size, there was a 6% decrease noted for passing math percentage, passing reading percentage, and overall passing percentage. According to the original data, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small-sized (90% overall passing) and large schools (58% overall passing). Given the data change, medium-sized schools are now the second in performance by size (85% overall passing).

<img width="782" alt="Scores by school size" src="https://user-images.githubusercontent.com/93743169/150596794-834069b6-c972-4611-9da7-7b8706c24cac.png">

### Scores by School Type

The re-calculation negatively impacted the charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now had a 90% passing math, 93% passing reading, 87% overall passing. However, even with these changes, charter schools outperform district schools.

<img width="754" alt="Scores by school type" src="https://user-images.githubusercontent.com/93743169/150596899-f87b9ce4-bcd4-415a-adb0-94205f638c0c.png">

## Summary

In summary, after the reading and math scores for ninth grade at Thomas High School were replaced with NaN values, there were four notable changes in the data. First, overall student count for the district that had a passing math and reading score was reduced, which impacted the passing math, passing reading and overal passing percentages forth district (albiet not my much). Secondly, scores within the $630-$644 spending ranges were lower, that can have an impact on school budgeting decisions. Thirdly, scores based on school size also decreased. This would be more in line with what one would expect, smaller student-to-teacher ratios woul yield better grades. Finally, scores by school type also changed. Scores for charter schools dropped by about 3%-4%, however, this was not significant enough to close the gap between how the two different school types performed overall. Students at district schools still remain far behind their peers at charter schools.
