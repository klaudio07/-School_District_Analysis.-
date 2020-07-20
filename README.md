## Purpose of this analysis.


-  *Repeat School district analysis that were done in the module and observe additional changes to identify evidence of academic dishonesty.

-  I will do this using Jupyter Notebook and the Pandas library, to read raw data from CSV files, inspect and clean data, merge datasets, perform mathematical calculations, and visualize the data to tell a story.
   

### Results:


1. **How is the district summary affected?**

*The average score in most districts has dropped as below*

-   Average Math Score: Decreased by 0.1, from 79.0 to 78.9

-   % Passing Math: Decreased by 1%, from 75 to 74

-   % Passing Reading: Decreased by 1%, from 86 to 85

-   % Overall Passing: Decreased by 1%, from 65 to 64

2. **How is the school summary affected?**

*Thomas High School passing percentages have decreased considerably*

-   % Passing in Math, Reading and Overall have dreoped from around 90% to aroung 60% - 70%

3.  **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

-   Thomas High School dropped from **2nd place to 8th** place out of 15 schools in **% Overall Passing Rate** 

-   Schools from 3rd to 8th place gained one spot because of the dropping of Thomas High School

4.  **How does replacing the ninth-grade scores affect the following:**

-   Math and reading scores by grade: 

*Thomas High School changed from 83.6 to NaN for the 9th grade*

*Thomas High School changed from 83.7 to NaN for the 9th grade*

-   Scores by school spending:

*% Passing Math  for the $630-$644 range decreased from 73% to 67%*

*% Passing Reading for the $630-$644 range decreased from 84% to 77%*

*% Overall Passing for the $630-$644 range decreased from 63% to 56%*

-   Scores by school size

*%Passing Math for the Medium (1000-2000) category decreased from 94% to 88%*

*%Passing Reading for the Medium (1000-2000) category decreased from 97 to 91%*

*%Overall Passing for the Medium (1000-2000) category decreased from 91% to 85%*

-   Scores by school type

*% Passing Math for Charter decreased from 94% to 90%*

*% Passing Reading for Charter decreased from 97 to 93%*

*% Overall Passing for Charter decreased from 90% to 87%*


# Summary:

-   Suprisingly, in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, as seen in tha above analysis, the performance changes dramatically. It is negative change that undermines the performance and drops Thomas High School from the top of the table to average and low performance.

-   Grade, spending, school size and school type are major indicators analyzied above and show the lower performance of Thomas High School. All this factors taken sparately and individually indicate a different and proper analysis needs to be taken into consideration. It is clear for example that schools with less than 1000 students perform better. Most importantly around 30% drop in % Passing in Math, Reading and Overall indicate a dramatic change of analysis for academic performance. 
