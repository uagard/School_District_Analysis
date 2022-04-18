# School_District_Analysis

##Overview of the school district analysis:

Based off of the students_complete.csv file it has shown us that there is evidence of academic dishonesty; specifically, reading and math grades for Thomas High School It is believed that the ninth graders appear to have found a way to  alter the data. We have been given the task to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then by using the Pandas NumPy module to change the reading and math scores to NaN.

We will utilize the (loc) method in order to select all the reading and math scores from the ninth grade at Thomas High School. When we use the loc method, the following are completed:

A comparison operator is used to retrieve all the rows with Thomas High School in the "school_name" column of the student_data_df A comparison operator is used to retrieve all the rows with the ninth grade in the "grade" column of the student_data_df Logical and comparison operators are used to retrieve all the rows with the "reading_score" column for Thomas High School ninth graders from the student_data_df Logical and comparison operators are used to retrieve all the rows with the "math_score" column for Thomas High School ninth graders from the student_data_df The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs

First Deliverable

First Deliverable_2

Deliverable 2

The District summary: Recalculated total student count by subtracting the number of ninth-grade students in Thomas High School from the total student count, then recalulated the passing math and passing reading percentages and overall passing percentage.

How is the school summary affected? I used the same methods from previous examples. I then created a data frame, the data metrics: School Type, total studemts, total school budget, per student budget, average math score, average reading score, passing math percentage, passing reading percentage and overall passing percentage. I used the tools I learned and formatted the school budget and per student budget to include the dollar sign and set the values to show to the hundreds place. 

First, calculate the number of 10th-12th graders in Thomas High School. Next we will create three new DataFrames for the 10th, 11th, and 12th graders from Thomas High School. We will find students who passed math, students who passed reading, and students who passed both math and reading. Using these DataFrames, I will recalculate the percentage of students who passed math, passed reading, and passed both math and reading for Thomas High School only. Finally, I was able to calculate and replace the % Passing Math, % Passing Reading, and % Overall Passing scores in the current School Summary DataFrame with the new passing percentages for Thomas High School. Utilizing the (loc) method with logical and comparison operators, retrieve the student count for Thomas High School ninth graders in the school_data_complete_df DataFrame. subtract the number of students retrieved from Step 1 from the total student count to get the new total student count. I was able to calculate the math and reading passing percentages based on the new total student count. I was able to calculate the overall passing percentage with the new total student count. 


