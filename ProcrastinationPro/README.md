# Project name:

## Loss analysis of the ProcrastinatePRO+ application


| Skills and Tools Used: | Tasks: | Project description: |
| :-------------------- | :--------------------- |:---------------------------|
| Matplotlib, Pandas, Python, Seaborn, Сohort Analysis,Product Metrics | A task for the marketing analyst of the entertainment app Procrastinate Pro+. Despite a huge investment in advertising, the company has been suffering losses for the past few months. Your task is to figure out the reasons and help the company turn a profit. | Analysis of data from ProcrastinatePRO+ was done. Calculated various metrics and used cohort analysis: LTV, CAC, Retention rate, DAU, WAU, MAU, etc. Multiple functions for metrics calculation were used. Conclusions from the data have been correctly drawn. |

We have 3 dataframes at our disposal: server log with information about site visits, information about orders, information about marketing costs 

*Table visits_log_short*:

 User Id - unique identifier of the user
 Device - user's device category
 Session start - start date and time of the session
 Session End - date and time of the session end
 Channel - identifier of advertising source the user came from
 Region - user's country
 
 *Table orders_log_short:*

User Id - unique id of the user who placed the order
Event Dt - date and time of purchase
Revenue - revenue

*Table costs_short:*

 Channel - advertising source ID
 Dt - date
 Costs - costs for this advertising source on this day
