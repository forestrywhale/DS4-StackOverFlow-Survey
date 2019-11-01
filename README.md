# DS4-StackOverFlow-Survey
DSND term2 Blogger Project
This repository is for analyzing StackOverFlow 2019 developer survey. The analysis blog can be found in here:
https://medium.com/@kikyo91/insights-into-2019-stack-overflows-annual-developer-survey-36d1ac5fb75d

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [To Excute The Notebook](#excute)
5. [Results](#results)
6. [Acknowledgements](#licensing)

## 1. Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## 2. Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2019 to better understand:

1. Does High Salary Meaning Lots of Working Hours?
2. What Are Factors That Contribution to High Salary?
3. Does People with High Salaries Are Using Different Social Media Comparing to People with Moderate Salaries?

## 3. File Descriptions <a name="files"></a>

- *stackoverlow19_Blog.ipynb*: Python notebook containing functional code for the analysis.
- *.png*: Figure files generated facilitating blog analysis.
- *developer_survey_2019.zip*: data downloaded from StackOverflow website: https://insights.stackoverflow.com/survey
- */Archives*: This is an archive folder containing code for a thorougher analysis.

## 4. To Excute The Notebook <a name="excute"></a>

- Extract the *developer_survey_2019.zip* into *./* folder.
- Excute.

## 5. Results

In this analysis, using data from 17 columns within the survey, I did following analysis:

- PCA: Obtain data distances and reduce feature numbers.
- K-mean Clustering: PCA distances were used for clustering.
- Histogram for social media: for highsalary and common salary cluster, observe and perform pairwise comparison for data in those 17 columns.

With distances provided by PCA, k-mean cluster was performed with number of clusters as 5, then a lasso model was created to explain the factors contributing to high annual salary. The most advantagous factor is to reside in United States, while the most disadvantagous factor is being women. We could also see that working professionally, review codes, and good work plan also positively contribute to high salary. Then the comparison of social media usage comparison shows a higher usage of Instagram, and WhatsApp comparing to the high salary group.

This model is useful for us to form better working habbits and become more efficient in programming.

## 6. Acknowledgements<a name="licensing"></a>

Survey data downloaded from StackOverflow website: https://insights.stackoverflow.com/survey
