# Analyzing-NYC-High-School-Data
One of the most controversial issues in the U.S. educational system is the efficacy of standardized tests and whether they're unfair to certain groups. Hence, the aim of this project is to;

Correlate between SAT scores and demographics. The study would seek to find correlation between SAT scores and factors like race, gender etc.
The SAT, or Scholastic Aptitude Test, is an exam that U.S. high school students take before applying to college. Colleges take the test scores into account when deciding who to admit, so it's important to perform well.

The test consists of three sections, each of which has 800 possible points. The combined score is out of 2,400 possible points (while this number has changed a few times, the dataset for this project is based on 2,400 total points). Organizations often rank high schools by their average SAT scores. The scores are also considered a measure of overall school district quality.

New York City makes its data on high school SAT scores available online, as well as the demographics for each high school. Unfortunately, combining both of the datasets won't give us all of the demographic information we want to use. We'll need to supplement our data with other sources to do our full analysis.

Before we move into coding, we'll need to get some backgroung information to give us a better understanding of how to combine and analyze the data.

he below information are necessary;
Only high school students take the SAT, so we'll want to focus on high schools.
New York City is made up of five boroughs, which are essentially distinct regions.
New York City schools fall within several different school districts, each of which can contain dozens of schools.
Our datasets include several different types of schools. We'll need to clean them so that we can focus on high schools only.
Each school in New York City has a unique code called a DBN or district borough number.
Aggregating data by district allows us to use the district mapping data to plot district-by-district differences.

The focus of this study is narrowed on high schools in New York City
New York City makes its data on high school SAT scores available online, as well as the demographics for each high school. Below are the link to all the datasets used in this project;



1. [ap_2010.csv](https://data.cityofnewyork.us/Education/2010-AP-College-Board-School-Level-Results/itfs-ms3e) Data on AP test results

2. [class_size.csv](https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3) Data on class size

3. [demographics.csv](https://data.cityofnewyork.us/Education/2006-2012-School-Demographics-and-Accountability-S/ihfw-zy9j)  Data on demographics

4. [graduation.csv](https://data.cityofnewyork.us/Education/2005-2010-Graduation-Outcomes-School-Level/vh2h-md7a)  Data on graduation outcomes

5. [hs_directory.csv](https://data.cityofnewyork.us/Education/2014-2015-DOE-High-School-Directory/n3p6-zve2)  A directory of high schools

6. [sat_results.csv](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4) Data on SAT scores

7. [survey_all.txt](https://data.cityofnewyork.us/Education/2011-NYC-School-Survey/mnz3-dyi8) Data on surveys from all schools

8. [survey_d75.txt](https://data.cityofnewyork.us/Education/2011-NYC-School-Survey/mnz3-dyi8) Data on surveys from New York City district 75
