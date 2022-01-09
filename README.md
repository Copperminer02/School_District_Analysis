# School District Analysis

## Overview of School District Analysis

At the request of the state's Chief Data Scientist, I performed an initial  perfomance analysis on standardized reading and math scores for 9th -12th grade students.  Student performance was charted against school, school type, school size, and school spending.  These reults were compiled to create:

  - **The Entire District Summary**
  - **Results by school**
  - **Results by school and grade level**
  - **Scores by School Spending**
  - **Scores by School Size**
  - **Scores by School Type**
  
 Upon review of the initial analysis and due to speculation over inaccuracies in test scores; the analyis was ran again.  This second analysis mirrored the first, except the Thomas High School 9th grade test scores for math and reading were nulled out.  
 
 The topics below address the results of the initial analysis as well as the effects of removing the Thomas High School 9th grade test results.
 
 ## Results
 
- **District Summary:** The overall affect of the Thomas data is noticeable, but overwhelming.  The new analysis (hereinafter *Thomas Analysis*) shows mild decreases in % Passing Math (0.2%), % Passing Reading (0.1%), and Overall Passing (0.3%).  
  - ***Original Analysis*** 
 ![image](https://user-images.githubusercontent.com/91850824/148695200-e10d5c16-5e2b-44d4-8fab-c321ce78daba.png)

  - ***Thomas Analysis***
![image](https://user-images.githubusercontent.com/91850824/148695194-ee5690c8-d9f7-4315-af0e-ea58045f17b3.png)
 
- **Summary by School:** As expected the only school data changed was for Thomas High School.  The *Thomas Analysis* shows decreases in Average Math Scores (0.13), Math Passing (0.09%) and Reading Passing (0.3%), as well as overall passing (0.3%).  In contrast, the Average Reading Score increased 0.05%.
  - ***Original Analysis*** 
  ![image](https://user-images.githubusercontent.com/91850824/148695577-7a3f3a2f-eeeb-401b-a36e-01a92dc9756b.png)

  - ***Thomas Analysis***
  ![image](https://user-images.githubusercontent.com/91850824/148695580-f180f3bf-963f-4f65-9ce6-69692253dad4.png)

  - ***Top Five Schools*** - Despite the potential error, Thomas still remains second overall on the list of top performing schools.  All other data remains the same.
    - ***Original Analysis*** 
  ![image](https://user-images.githubusercontent.com/91850824/148695631-12195c74-e729-49c6-85ee-a65707fde8f2.png)

    - ***Thomas Analysis***
  ![image](https://user-images.githubusercontent.com/91850824/148695638-62333979-c051-4afb-a86e-40284cdc7dc6.png)

  - ***Bottom Five Schools*** - The *Thomas Analysis* had no effect.
     - ***Original Analysis*** 
  ![image](https://user-images.githubusercontent.com/91850824/148695781-4eaba37c-68dc-4405-bbe5-e8bf58f1d813.png) 

    - ***Thomas Analysis***
  ![image](https://user-images.githubusercontent.com/91850824/148695787-f92ff092-45ae-4cfc-8b83-277304662ad9.png)

  - ***Effect on Thomas High School Performance:*** Overall the nullification of Thomas' 9th grade scores did little to affect it's overall rating; however, the drop was enough for Griffin High School to surpass Thomas slightly in Average Math Score (0.001%) and % Passing Reading (0.1%).  Thomas is still clearly a top school, and any error's in the ninth grade data are fairly insignificant to the total validation of teh original analysis.

- **Analysis Comparisons: Effect of Thomas 9th Grade Change**
  - ***Math Scores by grade*** - Thomas 9th grade originally scored and average 83.6% on the math testing.  This is 0.1% higher then the next highest grades (11th and 12th 83.5%), and 0.2% high than the average for all other Thomas Grades.  Compared to other schools, Thomas 9th grade was second only to Holden (83.8%) and tied with Pena (83.6%) for best average math score. Thomas's 9th grade removal lowers the ALL 9th grade average math grade by 0.23% from 80.4 to 80.1.
    - ***Original Analysis*** 
    ![image](https://user-images.githubusercontent.com/91850824/148696680-578da15a-91a7-45ba-b1b3-839bcb97f874.png)

    - ***Thomas Analysis***
    ![image](https://user-images.githubusercontent.com/91850824/148696677-e2322a6e-e8a2-4e67-b704-b54500b55a3d.png)

  - ***Reading Scores by grade*** - Thomas 9th grade originally scored and average 83.7% on the reading testing.  This is 0.1% higher then lowest grade (11th 83.6%), and 0.3% lower than the average for all other Thomas Grades (83.9).  Compared to other schools, Thomas 9th grade was tied for 5th. Thomas's 9th grade removal lowers the ALL 9th grade average reading grade by 0.1% from 80.35 to 80.12.
    - ***Original Analysis*** 
    ![image](https://user-images.githubusercontent.com/91850824/148696698-6b109d34-7625-423a-84ae-3059b72adef7.png)

    - ***Thomas Analysis***
    ![image](https://user-images.githubusercontent.com/91850824/148696701-3b3e157c-c506-4d0d-981e-ec469cb0a660.png)

  - ***Scores By School Spending:*** The *Thomas Analysis* had no effect.
    - ***Original Analysis*** 
    ![image](https://user-images.githubusercontent.com/91850824/148697634-f6c461b0-7685-4e7f-8155-467c5ba85a18.png)

    - ***Thomas Analysis***
    ![image](https://user-images.githubusercontent.com/91850824/148697640-41e8f362-b49a-44cd-a7dd-93c8137e680f.png)


  - ***Scores By School Size:*** The *Thomas Analysis* had no effect.
    - ***Original Analysis*** 
    ![image](https://user-images.githubusercontent.com/91850824/148697643-bf13a0ec-82a7-4c63-b1e8-7174d2ba58f9.png)

    - ***Thomas Analysis***
    ![image](https://user-images.githubusercontent.com/91850824/148697650-961539a4-8444-437a-a8c9-39745100bfa7.png)


  - ***Scores By School Type:*** The *Thomas Analysis* had no effect.
    - ***Original Analysis*** 
    ![image](https://user-images.githubusercontent.com/91850824/148697652-0763913e-be1a-469b-81b2-c4eab5e7cef0.png)

    - ***Thomas Analysis***
    ![image](https://user-images.githubusercontent.com/91850824/148697654-f3d4edaa-e15f-4787-b963-2b36ef26d617.png)

## Summary

Overall, the removal of Thomas High School's 9th grade scores was not of huge significance to the overall validity of the original analysis or a noticeble blemish to the overall performance of the school.  The main changes to the original analysis are:
  
1. The Average Math Score for the district dropped 0.1% from 79 to 78.9
2. The % Passing Math for the district dropped 0.2% from 75 to 74.8.
3. % Passing Reading for the Dsitrict dropped 0.1% from 85.8 to 85.7.
4. % Overall Passing for the District dropped 0.3% from 65.2 to 64.9
