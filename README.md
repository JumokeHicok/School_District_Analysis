# School_District_Analysis

## Project Overview
The school board would like the following tasks completed after replacing the 9th grade math and reading scores to confirm their suspicion of academic dishonesty at Thomas High School.

1. Recalculate the district summary
2. Recalculate the school summary
3. Recalculate the high and low performing schools
4. Recalculate the average math and reading scores by grade
5. Regroup the scores by school spending per student
6. Regroup scores by school size
7. Regroup scores by school type

## Resources
- Data Source: students_complete.csv and schools_complete.csv
- Software: Python 3.9.12, Visual Studio Code, 1.69.0

## Results
The analysis of the election show that:

- The passing percentages for the revised district summary are very similar to the original:
    - Original
![District Summary Original](/Resources/District_Summary_Original.png)
    - Revised
![District Summary Revised](/Resources/District_Summary_Revised.png)

- The passing percentages for the revised school summary are very similar to the original:
    - Original
![School Summary Original](/Resources/School_Summary_Original.png)
    - Revised
![School Summary Revised](/Resources/School_Summary_Revised.png)

- Thomas High School is still the second best school in regards to overall passing percentages:
    - Original
![Top 5 Original](/Resources/Top_5_Original.png)
    - Revised
![Top 5 Revised](/Resources/Top_5_Revised.png)

- Math and reading scores by grade are showing as "nan" in the revised dataframes since we replaced the 9th grade scores in the student_data dataframe with "nan".
    - Original
        Math                                                      | Reading  
        :----------------------------------------------------------------:  | :-------------:  
        ![Math by Grade Original](/Resources/Math_by_Grade_Original.png)  |  ![Reading by Grade Original](/Resources/Reading_by_Grade_Original.png)

    - Revised
        Math                                                      | Reading  
        :----------------------------------------------------------------:  | :-------------:  
        ![Math by Grade Revised](/Resources/Math_by_Grade_Revised.png)  |  ![Reading by Grade Revised](/Resources/Reading_by_Grade_Revised.png)
        
- There was no change to the scores by school spending because the change in passing percentages for Thomas High School was very small and the formatting of this output is rounded to zero decimal places.  Average scores were not replaced in this analysis.
    - Original
    ![Scores by Spending Original](/Resources/Scores_by_Spending_Original.png)
    - Revised
    ![Scores by Spending Revised](/Resources/Scores_by_Spending_Revised.png)
- There was no change to the scores by school size because the change in passing percentages for Thomas High School was very small and the formatting of this output is rounded to zero decimal places.  Average scores were not replaced in this analysis.       
    - Original
    ![Scores by Size Original](/Resources/Scores_by_Size_Original.png)
    - Revised
    ![Scores by Size Revised](/Resources/Scores_by_Size_Revised.png)
- There was no change to the scores by type size because the change in passing percentages for Thomas High School was very small and the formatting of this output is rounded to zero decimal places.  Average scores were not replaced in this analysis
    - Original
    ![Scores by Type Original](/Resources/Scores_by_Type_Original.png)
    - Revised
    ![Scores by Type Revised](/Resources/Scores_by_Type_Revised.png)


## Challenge Summary
After completing the updated analysis we can see that 1) the passing percentage for math at Thomas High School changed from 93.272171% to 93.185690% 2) the passing percentage for reading at Thomas High School changed from 97.308869% to 97.018739% 3) the overall passing percentage at Thomas High School changed from 90.948012% to 90.630324% and 4) the overall passing percentage for the district changed from 65.2% to 64.9%.  

