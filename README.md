Divvy Bikes Analysis (2019–2020)
Published report:

https://peter-mouw.github.io/Divvy_Bikes_Analysis_2019-2020/
 
Overview
This project analyzes publicly available Divvy Bikes trip data from Q1 2019 and Q1 2020. The goal is to compare usage patterns between casual riders and annual members and identify factors associated with subscription behavior.
The project was completed as a practice case study for the Google Data Analytics Professional Certificate.

Business Questions
The analysis addresses the following questions:
1. How do annual members and casual riders use Divvy bikes differently?
2. What factors are associated with casual riders becoming subscribers?
3. How might digital marketing be used to encourage membership adoption?

Data Sources
The analysis uses Divvy’s public trip datasets:
- Q1 2019 - Includes rider demographics (gender, birth year)
- Q1 2020 - Includes geographic coordinates for distance estimation
Raw data files are not included in this repository. They are publicly available at: https://divvybikes.com/system-data

Tools
R Markdown (tidyverse, lubridate, ggplot2)

Methods
- Data cleaning and standardization across datasets with different schemas
- Duplicate and missing-value removal
- Feature creation (trip duration, estimated distance, age groups)
- Aggregation and comparison by user type
- Time-of-day usage analysis
- Demographic analysis (2019 data only)
- All analysis and visualizations are contained in the R Markdown file and rendered as an HTML report.

Key Findings
- Subscribers take significantly more trips than casual riders
- Casual riders tend have longer average trip durations.
- Subscribers travel similar distances in less time.
- Subscriber usage follows weekday commuting patterns.
- Ride frequency is more strongly associated with membership than trip length or distance.
- Subscribers are disproportionately male and concentrated in the 25–44 age range.


Conclusions
Membership is most closely associated with frequent, transportation-oriented use rather than trip distance or duration. Casual riders who use the service regularly and for commuting appear most likely to convert to annual membership.

