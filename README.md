# School_District_Analysis
 ## Overview
The School District Analysis below is a reorganization of data based on the assumption that the 9th graders at Thomas Hich school altered their grades. All math and reading scores for the ninth graders at Thomas High School are removed, and calulations re-done to show new results.

 ## Results 
- ### District Summary
 1) Original District Summary 
 ![District_Summary](https://user-images.githubusercontent.com/90797036/137644573-016f4cdc-9fec-46f3-b08f-6f5af4737622.png)
 2) New District Summary (Note reduction in total student count)
 ![District_Summary_New](https://user-images.githubusercontent.com/90797036/137644763-5decdf33-1b07-4873-819d-4bd06805d183.png)

- ### School Summary
 1) Original School Summary
 ![School_Summary_Original](https://user-images.githubusercontent.com/90797036/137647682-aa7c453e-a577-445b-a6d2-e3b0c80db2dd.png)
 2) New School Summary, calculated with student count less ninth grader count  (Note the miniscule change in % passing.)
 ![School_Summary_New](https://user-images.githubusercontent.com/90797036/137645719-d890c60e-7719-45b0-8e67-0889cdb9c66c.png)

 - Top Performing Schools
 1) Original Ranking
 ![High_Performing_School](https://user-images.githubusercontent.com/90797036/137647726-5fc74b2e-1b49-48ac-afe9-7033ac3870ea.png)
 2) Ranking after night grade data from Thomas High School is removed  (Note that Thomas High School remains the 2nd highest ranking school)
 ![High_Performing_School_New](https://user-images.githubusercontent.com/90797036/137647429-4c2b2940-4008-4c19-bba4-059159b078cd.png)

 - Math scores by grade:
   - ![Math_Scores_By_Grade](https://user-images.githubusercontent.com/90797036/137648042-1d4b2ade-0e30-4aac-a882-264de16cefe3.png)
 - Reading scores by grade:
   - ![Reading_Scores_By_Grade](https://user-images.githubusercontent.com/90797036/137648045-6da7ac01-0126-4220-a5d4-ae91107c36b0.png)
   - Replacing the ninth-grade scores for the math and reading scores by grade simply replaced the previous value for 9th Grade at Thomas High School with NaN, no other affect.
   - ![Math_Scores_By_Grade_NaN](https://user-images.githubusercontent.com/90797036/137648277-f0b45e89-6c44-4f26-87b9-4e45e10abd3f.png)
   - ![Reading_Scores_By_Grade_NaN](https://user-images.githubusercontent.com/90797036/137648241-1a00e619-95fa-4562-9b0c-668f3d92d1d4.png)

- Scores by school spending
   - ![Score_by_School_Spending](https://user-images.githubusercontent.com/90797036/137648407-ed9d7f43-6ad6-40d5-8128-5c03dc1d6579.png)
- Scores by school size
   - ![Score_by_School_Size](https://user-images.githubusercontent.com/90797036/137648438-d5bc8f1b-d65e-4664-a11c-f4b8fed4e06b.png)
- Scores by school type
   - ![Score_by_School_Type](https://user-images.githubusercontent.com/90797036/137648481-bd0ab9ee-ba50-4d81-9421-651fd58d264b.png)

## Summary
By updating the school district analysis reading and math scores, by excluding grades for ninth grade at Thomas High School, there was no significant change in school ranking, and might be a indicator that the ninth graders did not alter their grades, but rather, were in line with the scores of the other grades at the same school.
