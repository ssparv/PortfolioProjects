

# Space Mission dashboard

![Space Mission Dashboard](https://user-images.githubusercontent.com/82135370/226754029-e309ef77-bd8c-4e28-b847-d6ac72f52a1c.png)



The dashboard is created based on the Maven's 'Space mission' dataset, which is available on the Maven's Data playground. 
The Space Mission dashboard was developed based on FP20 Analytics Data Challenges, Challenge 3. The challenge was to remake the 
most popular report in NovyPro by Federico Pastor on Space missions.

## Data Attributes
The data contains all space missions from 1957 to August 2022.


* Company : Company responsible for the space mission
* Location : Location of the launch
* Date : Date of the launch
* Time : Time of the launch (UTC)
* Rocket : Name of the rocket used for the mission
* Mission : Name of the space mission (or missions)
* RocketStatus : Status of the rocket as of August 2022 (Active or Inactive)
* Price : Cost of the rocket in millions of US dollars
* MissionStatus : Status of the mission (Success, Failure, Partial Failure, Prelaunch Failure)

Link to dataset : https://www.mavenanalytics.io/data-playground

## Tool used
Power BI

## Steps Performed 
* Performed Data Cleaning and ETL using Power Query
* Data Modelling in Power BI
* Used DAX to create new measures, calculated columns and tables
* Created the report in Power BI

## Insights

1. Between 1957 and August 2022, there were 4,555 space missions launched by 22 countries, at a total cost of $162.34 billion.
2. The top five countries based on the number of space missions launched are the USA, Russia, Kazakhstan, China, and France.
3. While the USA had the highest number of space missions launched, France had the highest success rate at 95.53%, followed closely by Russia at 95.46%.
4. From 1970 to 1978, the top five countries launched the highest number of space missions, with Russia contributing the highest proportion (57+ missions per year).
5. The majority of rocket launches took place at 12 pm.
6. The top five organizations that spent the most on rockets are NASA, Arianespace, ULA, SpaceX, and RVSN USSR. However, NASA stands out as the organization that spent the most on rockets, with a total of $77 billion, which is 59% higher than Arianespace's spending.


Link to dashboard: https://www.novypro.com/project/space-mission-1
