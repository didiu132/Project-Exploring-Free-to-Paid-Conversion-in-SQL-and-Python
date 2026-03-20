# Project-Exploring-Free-to-Paid-Conversion-in-SQL-and-Python
 In this project, I explore the free-to-paid conversion trends among students who’ve engaged with video content on the 365 platform.

## Key Insights
- The Free-To-Paid conversion rate is 11% which is higher than the industry average for freemium
- Most students watch their first video the same day they register
- Most students make their first purchase soon after watching their first video
- All factors indicate that the platform is easy to use and engaging and current upselling tactics are working

## Recommendations
- Conduct further research to determine why aren't making purchases through student interview/surveys

## Approach
The data I worked with three tables storing information about students’ registration dates, engagement dates, and subscription purchase dates.
1. The first step was aggregating data from the 3 tables into 1 table.
2. I created 2 new fields: date_diff_reg_watch and date_diff_watch_purchase to examine the durations registration to engagement and engagement to first purchase
3. I calculated the Free-To-Paid conversion rate and the average durations
4. Further analysis of the durations was needed so I calculated the means, medians, and modes in Python
5. I visualized the duration distributions using seaborn in python.
