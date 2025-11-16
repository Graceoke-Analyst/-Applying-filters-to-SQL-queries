# -Applying-filters-to-SQL-queries
# Summary
This project demonstrates expertise in data retrieval and security analysis by using advanced SQL filtering techniques. For this lab work i will be examining the organization’s data in their employees and log_in_attempts tables.I need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.
# Tools
SQL (It’s a programming language used to store, manage, and retrieve data from databases).
# Challenge
A security issue was recently discovered involving employee machines and user login attempts across the organization. As a security professional i am to investigate this activity by using SQL filtering and joining techniques across two separate datasets (employees and log_in_attempts). The objective was to identify security anomalies, such as an unusually high number of failed login attempts or successful logins associated with potentially compromised employee machines, to keep the system secure.
# Action and Analysis
- Using the "WHERE" clause with an "AND" operator to filter my results from the  log_in_attempts table to output only login attempts that occurred after 18:00 and were unsuccessful. To investigate potential security incident that occurred after business hours (after 18:00)
- Using the "WHERE" clause with an "OR" operator to filter my results  from the log_in_attempts to output only login attempts that occurred on either 2022-05-09 or 2022-05-08,to investigate a  suspicious event that occurred on 2022-05-09.
- Using the "WHERE" clause with "NOT" to filter for countries other than Mexico in the log_in_attempts tables since it has been established that the security event didnt happen in mexico, countries aside mexico needs to be investigated.
- To perform security updates on employers machine, i would be getting information on these employee machines and will need to query the Employees table using filters im SQL.
- Using the "WHERE" clause with "AND" to filter for employees who work in the Marketing department and in the East building from the Employees table.
- Using the "WHERE" clause with "OR" to filter for employees who are in the Finance and Sales departments from the Employees table.
- Using the "WHERE" clause with "NOT" to filter for employees not in the IT department from the Employees table.
# Result & Impact
Successfully retrieved datas needed to investigate the security events that took place.
The filtering logic developed can be directly translated into SIEM correlation rules to generate real-time alerts, significantly reducing the mean time to detect (MTTD) malicious activity, securing the organization system and mitigaing risk.
# Project artifact
See detailed labwork @ (# Applying_filters_SQL.md) (
