This repository contains code written in Jupyter Notebooks to analyze school data on a district- and school-level.

Merging the two csv file in  the Resources folder, the code will output a district summary table with the following metrics:

      Total Schools
      
      Total Students
      
      Total Budget
      
      Average Math Score
      
      Average Reading Score
      
      % Passing Math (The percentage of students that passed math.)
      
      % Passing Reading (The percentage of students that passed reading.)
      
      % Overall Passing (The percentage of students that passed math and reading.)
      
      
For a deeper look at individual schools, the code will then output a summary table that summarizes the following metrics for each individual school:

      School Name
      
      School Type
      
      Total Students
      
      Total School Budget
      
      Per Student Budget
      
      Average Math Score
      
      Average Reading Score
      
      % Passing Math (The percentage of students that passed math.)
      
      % Passing Reading (The percentage of students that passed reading.)
      
      % Overall Passing (The percentage of students that passed math and reading.)
      

To facilitate comparisons, the code then creates a top 5 and bottom 5 table based on a school overall passing percentage. These tables include the following metrics:

      School Name
      
      School Type
      
      Total Students
      
      Total School Budget
      
      Per Student Budget
      
      Average Math Score
      
      Average Reading Score
      
      % Passing Math (The percentage of students that passed math.)
      
      % Passing Reading (The percentage of students that passed reading.)
      
      % Overall Passing (The percentage of students that passed math and reading.)
      
 
The code then compares math and reading scores for each school by grade level by displaying the average math or reading score in respective tables by school for each grade.


I then look at scores by school spending by binning each school into one of four spending/student categories: <$600, $600-624, $625-650, >$650.
This table displays the following metrics:
      
      Average Math Score
      
      Average Reading Score
      
      % Passing Math (The percentage of students that passed math.)
      
      % Passing Reading (The percentage of students that passed reading.)
      
      % Overall Passing (The percentage of students that passed math and reading.)
      
I then reveal how those same metrics compare to schools by size. Each school is binned into one of the following categories based on total students: <1000, 1000-2499, 2500-4000, >4000.

Then I look at the same metrics by school type: District or charter.
      
