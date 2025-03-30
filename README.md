# Nigerian_traffic_crashes
## About Dataset

Nigerian Traffic Crashes (2020-2024)

Overview:

This dataset offers a detailed examination of road traffic crashes in Nigeria, covering the period from Q4 2020 to Q1 2024. It includes quarterly data on the total number of crashes, injuries, fatalities, and vehicles involved, along with key contributing factors such as speed violations, driving under the influence, and poor weather conditions. The data is sourced from official traffic records and provides insights into the factors influencing road safety in Nigeria.

Features:

Quarter  >> Description: The quarter in which the data is recorded (e.g., Q4 2020, Q1 2021). This field serves as the temporal reference for the dataset.

State  >> Description: The Nigerian state where the traffic crashes occurred. This variable allows for regional analysis of crash data.

Total Crashes  >> Description: The total number of road traffic crashes reported per quarter for each state.

Number Injured  >> Description: The total number of individuals injured in road traffic crashes per quarter. This metric indicates the severity of the crashes.

Number Killed  >> Description: The total number of fatalities resulting from road traffic crashes per quarter.

Total Vehicles Involved  >> Description: The total number of vehicles involved in the crashes per quarter. This variable can be used to analyze traffic volume and crash rates.

Speed Violation (SPV)  >> Description: The number of crashes attributed to speed violations. This factor is critical in understanding the role of speeding in road traffic crashes.

Driving Under Alcohol/Drug Influence (DAD)  >> Description: The number of crashes where driving under the influence of alcohol or drugs was a contributing factor.

Poor Weather (PWR) >> Description: The number of crashes that occurred under poor weather conditions, providing insights into weather-related risks.

Fatigue (FTQ) >> Description: The number of crashes attributed to driver fatigue. This variable highlights the impact of driver alertness on road safety.

This dataset is ideal for researchers, policymakers, and traffic safety analysts interested in exploring the dynamics of road traffic crashes in Nigeria, assessing risk factors, and developing data-driven strategies for improving road safety.

## About the project

I have made a Data Science project using a Kaggle dataset.

🎯 Agenda : In this project we are predicting number of people killed in accidents given the dataset of Nigerian traffic crashes.

🎯 Method : 

🔥 First we do EDA and visualise the dataset using different graphs to explore the data.

🔥 We are predicting number of people killed given the information like States, Total crashes, people injured, Total vehicles involved and factors for crashes.

🔥 We are using XGB Regressor algorithm to predict the number of people killed.

🎯 Tools Used : Numpy, Pandas, Matplotlib, Seaborn, Machine Algorithm(XGB Regressor)

🎯 Conclusion : We were able to predict the number of people killed with an accuracy of 81.5 % .
