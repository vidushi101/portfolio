---
title: Omdena real world projects
description: Collaborated on two Omdena projects to solve real-world issues with innovative data sceince and AI based approach
datestring: March/April 2023
weight: 203
tags: ["project", "AI", "data cleaning", "data collection", "deep learning" , "machine learning", "notion", "project management"]
cover:
  image: "projects/Omdena/omdena_cover.png"
---

## Resources
- View the complete project of automated left ventricular EF using deep learning on 🔗 **[GitHub](https://github.com/OmdenaAI/topeka-chapter-ejection-fraction)**
- view the complete project of Mitigating air pollution in Poland using machiene learning on 🔗 **[LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7053737252077596672/)**

## Bachground
Omdena is the collaborative platform to build innovative, ethical, and efficient **AI and Data Science** solutions to real-world problems. The platform helps mission-driven organizations and startups build impactful AI solutions through **global collaboration** and empowering AI engineers worldwide to become change makers. Omdena has  more than 15000 collaborators and 175 local chapters in 70 countries.

## project I : Automated Left Ventricular Ejection Fraction Assessment using Deep Learning

- **certification of completion:**
![](/projects/Omdena/omdena_topeka.png)

The Omdena Topeka Chapter team developed a Deep Learning model that will predict left ventricular ejection fraction (LVEF) values from ultrasound images . The project's primary goal was to accurately predict LVEF measurement.
With a duration of 8-weeks, this project achieved:

- Data Collection and Exploratory Data Analysis
- Preprocessing
- Feature Extraction
- Model Development and Training
- Evaluate Model
- App development
### Learning Outcomes
- Medical Image Processing
- Computer Vision
- Biomedical Image Analysis
- Project Managment

### My participation:

- acted as a task lead for the data collection phase of the project and made active contribution in other phases
- Collected resources, reference articles and datasets
- evaluated the suitability of datasets and their models with reference to our project
- maintained the tasks notion folder and all the datasets that were shortlisted
- represented the task's contributors in weekly meetings and presented progress report
- summariesed key discussion points for other teams and task members after task meetups.
- Continued to act as SME on various datasets throughout the project's cycle.
## project II: Mitigating Air Pollution in Poland Through Machine Learning

- **certification of completion:**
![](/projects/Omdena/omdena_warsaw.png)

The aim of this project was to investigate the primary factors responsible for air pollution in Poland and develop an effective tool to predict air quality. To achieve this, three datasets were utilized: daily air quality data, daily weather data, and Static annual data from the Polish Central Statistical Office, all from 2017 to 2021. The annual data provided information on various features related to human acitivities, such as area by land use, crop production, emission of particulates and pollutant gases, forest area and fires, population density, production of electricity, vehicle types, and air pollution reduction systems. To achieve the project's objectives, a methodology was adopted, which involved translating and cleaning the data, combining data from different years and pollutants, followed by data analysis and machine learning. The cleaned datasets were analyzed to identify the key factors contributing to air pollution in Poland.

### Results

- The results revealed that the concentration of pollutants varies during different times of the year. PM10 and PM2.5 are primarily emitted from sources such as solid fuel combustion, road traffic, dust from construction sites etc.
- NO2 is primarily emitted from combustion processes in energy production, manufacturing industry, and road transport, with diesel engines being a significant contributor to nitrogen oxide emissions.
-  O3 is a secondary pollutant formed by the influence of solar radiation on a combination of airborne pollutants, including NOx and VOCs.

### Process

To standardize the measurement of air quality and communicate it to the public, the Common Air Quality Index (CAQI) was used. It considers various pollutants, including PM10, PM2.5, O$_3$, NO$_2$, and SO$_2$, and assigns a value to indicate the level of air pollution. The CAQI levels are higher during weekdays and lower during weekends, potentially indicating that weekly pollutant concentrations depend on human activities.

The dataset was preprocessed, and two datasets were created for training classification and regression models. Various techniques, including feature engineering, feature selection, cross-validation, and hyperparameter optimization, were utilized. A range of models were trained and tested to predict CAQI classes and indexes, and their performance was evaluated using metrics such as F1 score and RMSE. Finally, an XGBoost regressor model was used to forecast future CAQI levels of Warsaw, and the model’s short-term forecasts was really close to the actual CAQI levels for the forecasting period.