# DATA PROFESSIONAL SURVEY BREAKDOWN

![image](https://user-images.githubusercontent.com/82135370/211703967-b95fff83-b8a5-4288-a388-58058be44763.png)

As a Business Analyst to help aspiring data professionals to understand the trends, preferences, and ratings of data professionals, a visualization 
dashboard is created in Power Bi using the "Data Professional Survey " dataset. This dataset was collected by performing a survey among 630 data 
professionals from different industries around the world, and was made available by the Alex The Analyst Youtube channel.

# Data Attributes:
Unique ID , Email, Date Taken, Time Taken, Browser, OS, City, Country, Time Spent,Which title best fits your current role?, Did you switch careers into 
data?,Currently Yearly salary?, What industry do you work in?, Favorite Programming language, How happy are you in your current position(salary,work life
balance,coworkers,management,learning new things,), How difficult was it for you to break into data?, If you were looking for a new job today, what would
be the most imp thing to you? male/Female?, Which country do you live in?, Highest level of education?, Ethnicity

# Data Preparation and Data Transformation:
To prepare the data for analysis, I performed data cleaning and transformation using Power Query in Power BI. This included:
  - Removed unwanted columns which were empty
  - Split certain column values by using delimitter and non digits for better analysis
  - Replaced certain column values
  - Changed datatype to perform aggregate functions
  - Added new custom column ‘Average Salary’ using DAX for better analysis

# The objective of the analysis was to answer the following questions:
- What percentage of survey takers were males and females?
- Which job title has the highest average salary?
- Which is the most favorite programming langauge based on the job title? 
- How difficult was it to break into Data?
- What is the rating of data professionals based on salary and Work Life balance? 

# Analysis Results:

- Out of the 630 data professionals, 468(74.29%) were males and 162(25.71%) were females. The average age of the survey takers was as 30.

- The overall trend shows that Data Scientist had the highest average salary of 94k followed by data Engineers and data Architects in most 
countries like India,United Kingdom , United States and in other countries. It was found that students and the people looking for jobs have the l
owest average salary of 27k. Since I currently reside in Canada I did further analysis of the data professionals in Canada and it has shown that other 
data professionals had a highest average salary of 120k followed by Data Engineers and Data Architects and the average salary of Data scientists in 
Canada are 96k which is even higher than the average salary of data scientist across different countries.

- Python was the most favorite programming language for all data professionals followed by R and other programming langauges. Data analysts and data
engineers had the highest preference for Python.

- 42.7% of the survey takers considered breaking into data as neither easy nor difficult while 24.7% considered it difficut and 21.2% percentage considered 
it easy.

- The survey has shown that data proffessionals around the world are not very satisfied with their salaries, giving a rating of 4.27 out of 10.
They were slightly more satisfied with their work-life balance, giving a rating of 5.74. Further analysis showed that United Sales had the 
highest ratings for both salary (5 out of 10) and work-life balance (6.38 out of 10). Data professionals in India had the lowest ratings, with 
3.51 out of 10 for salary and 4.79 out of 10 for work-life balance.


These findings provide valuable insights into the experiences and preferences of data professionals. As a business analyst, I believe that understanding 
these trends can help aspiring data professionsls make data-driven decisions.

Link to dashboard: https://www.novypro.com/project/data-professional-survey-breakdown
