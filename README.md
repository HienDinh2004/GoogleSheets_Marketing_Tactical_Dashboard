**I. Introduction**
________________
This project presents a marketing performance dashboard built entirely in Google Sheets, designed to track daily and weekly advertising metrics with clarity and automation. It enables marketing teams to monitor key KPIs such as cost, reach, CTR, frequency, and CPM with built-in trend lines and performance comparisons (e.g., D-1 vs. D-7 or W-1 vs. W-4).

**II. Data Source**
________________
Raw Data: 

(https://docs.google.com/spreadsheets/d/1h_yMbeEfiIKkV2YgRQuK_0E7nowEQUWamgJlBqsVX1M/edit?gid=0#gid=0)

**III. Project objectives**
________________
- Track and monitor daily and weekly advertising performance in real time

- Visualize key marketing metrics (e.g., Cost, Reach, CTR, Frequency) for faster decision-making

- Compare short-term and long-term trends (e.g., D-1 vs D-7, W-1 vs W-4) to evaluate campaign effectiveness

- Automate data updates and calculations using built-in formulas and functions in Google Sheets

- Provide a lightweight, shareable dashboard solution without the need for advanced BI tools

- Support marketing teams in identifying opportunities, inefficiencies, and optimization points

**IV. Requirements**
________________
- Google Sheets (no add-ons required)

- Functions: IMPORTRANGE, QUERY, IFERROR, SUMIFS, TEXTJOIN, IFS, REGEXMATCH, SPARNKLINE

- Features: Pivot Tables, Slicer, Data Validation, Conditional Formatting, Charts

**V. Step to step guide**
________________
1. Import clean data
- Create a sheet and name it "Clean Data"
- Choose cell F1 and enter:

=IMPORTRANGE("https://docs.google.com/spreadsheets/d/1h_yMbeEfiIKkV2YgRQuK_0E7nowEQUWamgJlBqsVX1M/edit?gid=775243907#gid=775243907", "Clean Data!A:V") 

2. Create Dashboard
   
Using sumifs and sparkline to create dashboard according on key metrics

**VI. Link Result**
________________

https://docs.google.com/spreadsheets/d/1ZOz_4RbIUjv-jkDRDdLQdDjTS7H0jHCJkkjKpxR0g3k/edit?gid=2094965417#gid=2094965417
