# School_District_Analysis
## Using Anaconda and Jupiter

## Overview  
The school board has notified Maria and her supervisor that the student_complete file stats the proof of academic dishonesty; in particular the reading and math grades for Thomas High School, seems like the ninth graders data has been altered. 
The school board is not aware about the whole records and unknown to full extent of the academic dishonesty they want to go with the state-testing standards and want to help Maria in regards to this. She requested to replace the math and reading scores for the Thomas High school with NaN while keep the rest data intact. once that data been removed then Maria like to do analysis on how it will affect the overall analysis.

## Initial Analysis
  In this Analysis the ninth-grade reading and math score are been replace with the NaN values as they seems to be manipulated. In order to make it possible we have filtered the data by the school name and grade by Thomas High school and 9th grade respectively then assigned the value equal to np.nan so that the data will change to NaN as shown in the figure.
![Initial Analysis](https://github.com/urvish7/School_District_Analysis/blob/main/Deliverable1.png)
![Thomas School data](https://github.com/urvish7/School_District_Analysis/blob/main/Thomas_school_data.png)
   
   
 ## Second Analysis 
  Tn this analysis the we are summarizing the multiple school data. Analyzing the data for all the schools then sorting them on the base of performance. few tasks that we are fetching in particular inorder to have a general idea about the data such as :
- Sorting the top 5 schools on passing rate.
![Top 5 Schools](https://github.com/urvish7/School_District_Analysis/blob/main/Top5schools.png)
- Sorting the bottom 5 schools on the passing rate.
![Bootom 5 School](https://github.com/urvish7/School_District_Analysis/blob/main/Bottom5schools.png)
- Average math score for each grade level for each school.
   It is been taken by counting the entities on individual grades and divided by the total number of the students and then multiplied with 100. sometimes proper formula needed to extract the right number by using count function on wrong dataframe can leads to fetch wrong information.
- Average reading score for each grade level from each school.
   it is been calculated in the same manner as the math score , in this case we use the reading column to fetch the data instead of math column.
- The school spending per student, by school size and by school type.
![Overall inclusion](https://github.com/urvish7/School_District_Analysis/blob/main/Byentitysorting.png)


# Results:
   The district summary and school summary are been affected slightly as most of the data is been covered by the other schools. some of the data have slight drop while some have slight inclination. however taking out the 9th grade does drops the ranking of the school from the top positions. 
   
   
#Summary:
 After been replace to the NAN values there is been change in all the vlaues in each of the columns of the table. The average math and reading score values went up slightly, rest there is drop in the percentage when it comes to the passing math, passing reading and overall percentage so by talking out the values the data of the Thomas High school has affected in a big way however overall have been affected slightly when it comes combining the other school in the same picture.
