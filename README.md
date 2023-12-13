# cyclistic
This repository contains all of the project files I created to complete the capstone experience for the Google Data Analytics Professional Certificate program on Coursera.

## Background
Cyclistic is a Chicago-based bike-sharing company that has a fleet of bicycles geotracked via a network of stations.  The company's marketing team needs an analysis of current ridership and recommendations to develop marketing strategies to convert casual riders to annual members.

## Recommendations
Insert summary here...

## Outputs
I generated the following outputs as part of this project:
* detailed analysis notebooks published on RPubs for each phase of analysis: [Ask](https://rpubs.com/dtminnick/cyclistic_ask), [Prepare](https://rpubs.com/dtminnick/cyclistic_prepare), Process, Analyze, Share, and Act,
* an executive presentation deck summarizing findings and recommendations, and
* an interactive Tableau dashboard.

## Analysis Challenges & Solutions
Here are the challenges I needed to overcome to complete this work and a summary of how I addressed each.

| Challenge                   | Problem    | Resolution |
| --------------------------- | ---------- | ---------- |
| Data Redundancies           |            |            |
| Geotracking Inconsistencies | Source data included latitude and longitude that pinned the start and end of each trip made by a customer.  I found variation in coordinates for the same start and end points and needed to resolve them to maintain accuracy of geography-related analysis and visuals. | I implemented a custom R function to resolve the differences.  See Process notes and function documentation for details. |
