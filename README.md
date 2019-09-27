# GA-DSI-Project-01

# Overview
This project involves the analysis of SAT and ACT data, for the 50 US states (plus the District of Columbia), for the years 2017 and 2018. The objective is to gain insights in order to make recommendations to the College Board on steps to take to increase the SAT participation rate in the state of Missouri.

# Description of Data
A total of 4 datasets were provided:

- 2017 SAT
- 2017 ACT
- 2018 SAT
- 2018 ACT

Each dataset comprises state-wise data on participation rates, sub-test mean scores, and mean total/composite scores.

# Data Verification and Cleaning
Data provided was checked against public-domain sources such as websites and scores/values found to be incorrect were updated.

# Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|The name of the state pertaining to this row of data|
|act_participation|float|ACT|The participation rate for ACT|
|act_english|float|ACT|The mean score for ACT English|
|act_math|float|ACT|The mean score for ACT Math|
|act_reading|float|ACT|The mean score for ACT Reading|
|act_science|float|ACT|The mean score for ACT Science|
|act_composite|float|ACT|The mean composite score for ACT|
|sat_participation|object|SAT|The participation rate for SAT|
|sat_ebrw|integer|SAT|The mean score for SAT Evidence Based Reading and Writing|
|sat_math|integer|SAT|The mean score for SAT Math|
|sat_total|integer|SAT|The mean total score for SAT|

# Conclusion
Based on the findings of our analysis and further research, we developed recommendations to the College Board on steps to consider in order to increas the SAT participation rate for Missouri.
