# Customer-Satisfaction-Analysis-Report


This repository contains a Power BI report that analyzes the CALL CENTRE dataset. The report provides insights into various aspects of call center performance, including customer satisfaction, call volume, resolution rates, and agent performance.

## Project Overview

The CALL CENTRE dataset contains information about calls received by a call center. The dataset includes the following fields:

CALLER ID: Unique identification number of each caller
AGENT: Name of the agent who handled the call
DATE: Date of the call
TIME: Time of the call
TOPIC: Topic of the call
ANSWERED: Whether the call was answered (Y/N)
RESOLVED: Whether the call was resolved (Y/N)
SPEED OF ANSWER IN SECOND: Speed of answer in seconds
AVG. TALK DURATION: Average talk duration in minutes
SATISFACTION RATE: Rating of the agent's performance
## Data Preparation

Before analyzing the data, the following data preparation steps were performed:

Replaced all null values with 0
Changed data types as needed
Extracted seconds and minutes from AVG. TALK DURATION and created a new column named Duration on calls
## Report Overview

The report provides the following insights:

Call Volume: Total number of calls, number of answered calls, and number of rejected calls
Resolution Rates: Percentage of calls resolved and percentage of calls not resolved
Agent Performance: Top 1 agent who answered the most calls and top 1 agent with the highest satisfaction rate
Call Distribution: Total number of calls by topic
Call Duration: Duration of calls by agent
Call Volume by Date: Total number of calls by day and month for the year 2021
Interactive Charts: Slicers to interact with other charts by month and day
Overall Performance Rating: Overall 2021 performance rating
Overall Satisfaction Rating: Overall 2021 satisfaction rating
