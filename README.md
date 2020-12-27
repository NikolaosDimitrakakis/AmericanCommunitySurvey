# American Community Survey
Visualizations of American Community Survey

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)
6. [CRISP-DM process](#CRISP-DM)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested to work with a dataset on the job outcomes of students who graduated from college between 2010 and 2012, to understand:

1. Do students in more popular majors make more money?

2. How many majors are predominantly male? Predominantly female?

3. Which category of majors have the most students?

## File Descriptions <a name="files"></a>

There is 1 notebooks available here with work related to the above questions. The notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

## Results<a name="results"></a>

From the charts we have found the following:

1. No grads from popular major seems that they don't make much more money, except for some cases with a salary above 60.000$ 

2. There is no correlation between money and major in a subject where the majority are females.

3. It seems that there is some correlation between full-time employees and median salary, but we need to investigate more.

4. The most common median salary is between 30.000-40.000. A few people are getting paid above 65.000$.

5. The unemployment rate is between 5%-7%

6. 60%-80% of the grads are females.

7. As we can see in some majors areas the grads are equal women and men like Physical sciences, Business etc. While in some others women are graduating more than men like Humanities and Liberal arts or Communications and Journalism. And in Engineering and Computers and Mathematics men grads are almost the double of the women.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The original data on job outcomes was released by [American Community Survey](https://www.census.gov/programs-surveys/acs/), which conducts surveys and aggregates the data. Must give credit to FiveThirtyEight cleaned the dataset and released it on their [Github repo](https://github.com/fivethirtyeight/data/tree/master/college-majors). Otherwise, feel free to use the code here as you would like! 

## CRISP-DM process <a name="CRISP-DM"></a>

1. Business Understanding

1. Do students in more popular majors make more money? Do students that majored in subjects that were majority female make more money? Is there any link between the number of full-time employees and the median salary?

2. What is the most common median salary? What is the unemployment rate? What percentage of grads are females?

3. How many majors are predominantly male? Predominantly female?

2. Data Understanding

Here we used the FiveThirtyEight cleaned dataset, original data on job outcomes was released by American Community Survey, to attempt to answer our questions of interest.
Each row in the dataset represents a different major in college and contains information on gender diversity, employment rates, median salaries, and more. Here are some of the columns in the dataset:

1. Rank - Rank by median earnings (the dataset is ordered by this column).
2. Major_code - Major code.
3. Major - Major description.
4. Major_category - Category of major.
5. Total - Total number of people with major.
6. Sample_size - Sample size (unweighted) of full-time.
7. Men - Male graduates.
8. Women - Female graduates.
9. ShareWomen - Women as share of total.
10. Employed - Number employed.
11. Median - Median salary of full-time, year-round workers.
12. Low_wage_jobs - Number in low-wage service jobs.
13. Full_time - Number employed 35 hours or more.
14. Part_time - Number employed less than 35 hours.

3. Prepare Data

In this notebook, we don't need to prepare our data since the FiveThirtyEight cleaned the dataset and released it on their [Github repo](https://github.com/fivethirtyeight/data/tree/master/college-majors). The only thing we will do is to remove rows containing null values.
Credits to them!

4. Model Data

Create Visualizations to answer our questions.

5. Results

From the charts we have found the following:

1. No grads from popular major seems that they don't make much more money, except for some cases with a salary above 60.000$ 

2. There is no correlation between money and major in a subject where the majority are females.

3. It seems that there is some correlation between full-time employees and median salary, but we need to investigate more.

4. The most common median salary is between 30.000-40.000. A few people are getting paid above 65.000$.

5. The unemployment rate is between 5%-7%

6. 60%-80% of the grads are females.

7. As we can see in some majors areas the grads are equal women and men like Physical sciences, Business etc. While in some others women are graduating more than men like Humanities and Liberal arts or Communications and Journalism. And in Engineering and Computers and Mathematics men grads are almost the double of the women.
