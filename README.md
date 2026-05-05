# college_football_recruiting_analysis

## College Football Recruiting Analysis

### Team 15
### Andrew Shroder, Ben Burns, Andrew Wolfson, Cole LaCamera

---

Tableau Link: https://public.tableau.com/app/profile/andrew.wolfson/viz/CollegeFootballRecruitingAnalysis/Story1?publish=yes

Youtube Link: youtube.com/watch?v=P0VLp4zy7TU&feature=youtu.be

---


## Project Summary

This project explores the relationship between college football recruiting performance and team success. Instead of using a pre-built dataset, we developed a full end-to-end data pipeline in R that pulls, cleans, and integrates multiple data sources into a single structured dataset.

The pipeline combines:
- Game-level data from the CollegeFootballData API  
- Recruiting rankings from 247Sports (via web scraping)  
- AP poll rankings from the College Poll Archive  

We standardized team names across sources, handled missing and inconsistent data, and built team-level performance metrics. A key feature of the project is the creation of lagged recruiting variables, which allow us to analyze whether recruiting impacts performance immediately or over time.

The final dataset is structured at the team-year level and includes performance metrics, recruiting data, lag features, and ranking information. This dataset supports both visualization and further modeling, and demonstrates the value of building a reproducible data pipeline from raw, real-world data.
