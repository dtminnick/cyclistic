# cyclistic
This repository contains all of the project files I created to complete the capstone experience for the Google Data Analytics Professional Certificate program on Coursera.

## Background
Cyclistic is a Chicago-based bike-sharing company that has a fleet of bicycles geotracked via a network of stations.  The company's marketing team needs an analysis of current ridership and recommendations to develop marketing strategies to convert casual riders to annual members.

## Recommendations
Given the extensive network of bike routes throughout the city, making it feasible for users to travel safely and efficiently, as well as the abundance of parks and recreation opportunities and concentration of culturally significant landmarks, I recommended a marketing strategy that attracts both those seeking a reliable daily commute solution and those looking for exciting ways to experience their city as the best approach to converting casual riders to members.

This strategy has three parts:
* leveraging storytelling and customer-generated social media content to showcase the bike-sharing service,
* partnerhips with local businessed that can provide added benefits and incentives to purchase memberships, and
* promotions in the form of themed rides and curated urban adventures for members.

## Outputs
I generated the following outputs as part of this project:
* detailed analysis notebooks published on RPubs for each phase of analysis: [Ask](https://rpubs.com/dtminnick/cyclistic_ask), [Prepare](https://rpubs.com/dtminnick/cyclistic_prepare), [Process](https://rpubs.com/dtminnick/cyclistic_process), [Analyze](https://rpubs.com/dtminnick/cyclistic_analyze), and [Share](https://rpubs.com/dtminnick/cyclistic_share),
* an [executive presentation deck[(https://github.com/dtminnick/cyclistic/blob/main/inst/extdata/reference/Cyclistic%20Marketing%20Strategy%20Recommendations.pptx) summarizing findings and recommendations.

## Analysis Challenges & Solutions
Here are the challenges I needed to overcome to complete this work and a summary of how I addressed each.

| Challenge                   | Problem    | Resolution |
| --------------------------- | ---------- | ---------- |
| Data Redundancies           | Duplication of or slight variations in station names. | I identified and removed these redundancies during the Process phase of the project. |
| Geotracking Inconsistencies | Source data included latitude and longitude that pinned the start and end of each trip made by a customer.  I found variation in coordinates for the same start and end points and needed to resolve them to maintain accuracy of geography-related analysis and visuals. | Most of these variations were slight and didn't impact my ability to perform geographical analysis, so I left them. |
| Active Trips by Hour | Trip start and end data was captured in a manner that required a solution for counting active trips by hour interval, accounting for trips that overlap intervals. | I created a function to count active trips for each hour, considering the start and end hours of trips. This function accounted for trips that overlapped multiple hour intervals to avoid counting them more than once. |

## Notes


