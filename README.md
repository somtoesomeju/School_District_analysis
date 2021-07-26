# School_District_analysis

# Overview
In this analysis, I am assisting Maria, a data analyst, in aggregating data of students in various high school dsitricts. The purpose of this analysis is to show how the Python programming language can filter out, clean and modify data. Anaconda, an open source software that runs in python, will be use in this analysis.

After the initial analysis was completed, the data was found to be altered, particularly the math and reading scores for some of the ninth graders in Thomas High School (this is one of the 15 schools in the analysis). Instead of ignoring the data, I am going to replace the altered grades with the words "NaN". This indicates that the grade of the student was altered. After correcting and cleaning the data, I was able to reproduce the initial analysis. The results are listed below.

# Resources
Software: Python 3.7. Anaconda 4.10.3.

# Results.
After replacing the data for the 9th graders with "NaN", the overall data for Thomas High school was altered. This put thomas high school with an overall passing grade of [65%](https://github.com/somtoesomeju/School_District_analysis/blob/somtoesomeju-patch-thomas/Thomas_high_School_raw.png). In reality, this is much lower than the actual passing grade. From reading the data, the trend shows that the schools that perform better tend to have lower budgets relative to the school size. Thomas High school has a relatively low budget so a higher overall grade should be listed. Using python, I calculated the data again, this time omitting the 9th grade data completely. The new data was tallied and Thomas High school finished with a higher overall passing grade of [90.6%](https://github.com/somtoesomeju/School_District_analysis/blob/somtoesomeju-patch-thomas/Thomas_High_School_corrected.png). This grade matches with the budget and can be used for the final analysis. From the data, a few conclusions can be made;

- The smaller sized schools (usually the charter) performed better than the larger sized schools (the district level).
- There is no correlation between the passing grade and the budget, even though schools with a lower budget produce better student results.
- Thomas High school is the second best perfoming school in the list with 90.6% of students finishing with a passing grade.
- There is a positive correlation between the school size and the budget. The schools with the highest number of students had the largest budget.
- Altering and correcting the data of Thomas High School did not change the data of the other schools.
- The charter schools did much better than the district schools. The overall passing grade in the charter was 90% as opposed to 54% in the district schools.

# Summary
From the overall data, it shows that schools with a smaller number of students perform better than the larger schools. While this may be a coincidence, the data suggests otherwise. It can be assumed that students either work better in smaller groups, or there is a better relationship between students and teachers in smaller classes. The overall passing grade also increased when Thomas High School's data was changed. Initially, all 15 schools had a % overall passing of 64% (due to the lower overall grade % from Thomas High). After correcting the data, the overall passing grade increased to 71% ([% overall passing grade in charter + % overall passing grade in district] / 2). This analysis shows the efficiency of using Python to clean data.

