---
title: "Data Professionals Survey Breakdown"
description: A PowerBI dashboard created to analyse and visualise the findings of an online survey taken by 630 data professionals.
datestring: June 2023
draft: false
tags: ["dashboard", "powerBI", "project", "visualisation", "survey", "power Query", "DAX", "data viz", "interactive", "drill down", "data analysis", "data transformation"]
weight: 201
cover:
      image: "projects/data_prof_survey/power_bi.jpg"
---

- View the complete project on 🔗 **[Github](https://github.com/vidushi101/data_professionals_survey)**

## Background

The dashboard was created on the results of an online survey taken by 630 data professionals in regards to the following parameters
- job title
- average salary
- job industry
- preferred programming language
- job satisfaction with respect to salary, working environment, Work/Life Balance etc.
- demographic questions such as age, highest level of education, country of residence, gender etc.

## Working
The data was retrieved in an excel sheet and thereafter cleaned for the following
- removing unneeded colums to create a subset of data
- checked for incomplete/null values
### Data Transformation
The data was then moved to powerquery to transform it to fit the final objectives:
- changed data types of columns
- renamed columns as needed
- added new columns to store the values of "other" in the answer to questions
- split columns by delimeter to seperate out the values of "other"
- created new meausres via DAX
### Data Visualisation
The following visual were created to determine:
-  highest average salary by work industry with option to "drill down" into **salary satisfaction** for the corresponding salary and industry
- numer of respondents that made a **career switch** into data
- **average salary by job title**
- comparison of **work/life balance and job title** with option to "drill down" into the work/life balance according to the gender and industry.
## Interesting results
- almost **59%** of respondents said they did not belong to this industry initially and made a career switch.
-  the highest average salary is seen for **"data scientist"** role with the highest paying industry being "education" with average salary for respondents around 171.33 USD.
- out of nearly 25 respondents working as "data scientists" two(8%) reported a work/life balance of perfect ten , while a major chunk(24%) reported it at average seven.
- nearly 18% (68/381)respondant "data analysts" rated their **work/life balance** to be three or less than it.