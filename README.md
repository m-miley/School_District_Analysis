# School_District_Analysis
Resources:
- Python 3.9.7, Jupyter Notebook
- Data: schools_complete.csv, students_complete.csv

## Overview
The purpose of this analysis is to generate report summaries with Pandas to communicate details and elucidating insights concerning school district performance.  The performance is based on the following:
- student test score averages in math and reading
- percent of students passing math and reading separately
- percent of students passing both math and reading overall
- budget allotment and spending per capita

Furthermore, we apply these details widely to the entire school district in a summary and break it down further into smaller reports for each school, grouping the fields by school size, spending data, and school type.

In addition, we were informed that the 9th grade test scores for Thomas High School were perhaps altered and therefore academically dishonest, so we restructured each report with the nullification of this specific category and results are as follows.

## Analysis
### District Summary
- original:
![Screen Shot 2022-04-14 at 8 25 31 PM](https://user-images.githubusercontent.com/100544761/163503445-d3fa5bd4-1816-4847-b866-dfe0b1c75c70.png)
  
- after nullification:
![Screen Shot 2022-04-14 at 8 25 09 PM](https://user-images.githubusercontent.com/100544761/163503449-4c17a525-247e-4011-939f-c6d145631a0b.png)

0.1% increase in overall math score percentage

### School Summary
  - original:
![Screen Shot 2022-04-14 at 7 56 41 PM](https://user-images.githubusercontent.com/100544761/163501201-5e564dc5-6483-4f1b-8c80-5b1d3866c5d7.png)

The original summary report suggests a slight positive correlation with higher spending per student and lower test scores and passing rates.  Similarly, it shows that largely, the smaller schools have higher overall passing percentages.

- after nullification:
<img width="1131" alt="Screen Shot 2022-04-15 at 3 19 26 PM" src="https://user-images.githubusercontent.com/100544761/163628401-01dd9299-d769-41e4-b368-e458d0baf48c.png">


We can see from the second generated summary report after nullifying 9th grade test scores for Thomas High School, that their test scores improved dramatically for the 10th-12th graders.  This action consequentially raised them from middle of the pack to 2nd best performing school in the district.

### High/Low Performing Schools
- after nullification:
  - Top:
![Screen Shot 2022-04-14 at 8 05 28 PM](https://user-images.githubusercontent.com/100544761/163501829-51e44987-2a2f-4e20-9e1a-8a377f250b72.png)

  - Bottom:

![Screen Shot 2022-04-14 at 8 05 36 PM](https://user-images.githubusercontent.com/100544761/163501833-59ca3377-4577-4d22-9bc8-95bc8e167c84.png)

### Math and Reading Scores by Grade:

<img width="485" alt="Screen Shot 2022-04-15 at 3 10 23 PM" src="https://user-images.githubusercontent.com/100544761/163627481-03cfe23b-b23c-459a-a8e9-b85e20af5e62.png">
<img width="485" alt="Screen Shot 2022-04-15 at 3 10 23 PM" src="https://user-images.githubusercontent.com/100544761/163627468-9e2d67fc-e67e-4d9d-b597-daf6470e7649.png">


### Scores by School Spending
- Oddly enough, or maybe not because only 461 of 39170 students were affected by changes in the data, that both original and altered reports were identical with no changes to data.  The results are the same.  Schools with more spending per capita have lower averages and passing rates.

![Screen Shot 2022-04-14 at 8 38 48 PM](https://user-images.githubusercontent.com/100544761/163504183-f22b8882-96e8-4353-ae06-0cbeafdcc42e.png)

### Scores by School Size
- Again, no observable changes with the altered data.  The largest schools have lower scores and pass percentages.

![Screen Shot 2022-04-14 at 8 40 50 PM](https://user-images.githubusercontent.com/100544761/163504368-87a45fc9-0704-4eec-8bae-c40b891808a0.png)

### Scores by School Type
- Again, no observable changes with the altered data from the original report.  Charter schools (likely smaller and less funding) have higher subject area averages and passing percentages than District schools.

![Screen Shot 2022-04-14 at 8 43 06 PM](https://user-images.githubusercontent.com/100544761/163504557-f3748078-a842-4d99-a3af-be9fcaf89d39.png)


## Summary
All in all, the schools in this district have varying budgets, sizes, types, and test scores.  Insights were highlighted here with nothing conclusive as to causation.  This would likely require more data such as curriculum content, teacher count and education, supplies, extracurricular activities, demographics, location, etcetera.  However, these insights do give us a good indication of performance and perhaps the affectiveness of school types. Moreover, provides evidence against the hypothesis that more funding translates to higher grades.  In the challenge script, focus was on restructuring the reports to nullifying 9th grade scores for Thomas High School.  This did have a drastic impact on their placement in the school summary top performers, ex post facto. Their overall passing percentage increased nearly 40% as a result.  Largely all the other reports: District schools, Spending, Size, and Type maintained the same scores and percentages.  There was a small 0.1% change in one of the score averages.  In conclusion, although strange at first glance, considering how 461 is only about 1.1% of the original 39,170 student count for the district, the null in the subsequent rows had no observable impacts to the analysis outside of the school summary report, of which it had a dramatic affect.

### Contact

Email:  mrmileyy@gmail.com
