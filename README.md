# cyclistic
This repository contains all of the project files I created to complete the capstone experience for the **Google Data Analytics Professional Certificate** on Coursera.

This project demonstrates applied analytics skills including data wrangling, geospatial reasoning, visualization, and stakeholder-ready communication.

# Background
Cyclistic is a Chicago-based bike-sharing company with a GPS-enabled fleet connected through a city-wide network of stations. The company’s marketing team seeks insights into current ridership behaviors and recommendations to convert casual riders into annual members.

# Project Goal
Analyze one year of trip data to uncover usage patterns and recommend actionable, data-driven marketing strategies for boosting annual memberships.

# Key Recommendations
Chicago’s expansive bike infrastructure, combined with a vibrant cultural and recreational scene, creates an ideal opportunity to market Cyclistic to both commuters and leisure riders. The recommended strategy has three parts:

1. **Storytelling and Social Proof**: Leverage user-generated content and testimonials to highlight real-world usage and experiences.
2. **Local Partnerships**: Collaborate with local businesses to offer incentives for members, such as discounts or exclusive perks.
3. **Themed Campaigns**: Design seasonal rides and curated urban bike adventures to make memberships more attractive and experiential.

# Outputs
- Phase-based analysis published to RPubs:
  - [Ask](https://rpubs.com/dtminnick/cyclistic_ask)
  - [Prepare](https://rpubs.com/dtminnick/cyclistic_prepare)
  - [Process](https://rpubs.com/dtminnick/cyclistic_process)
  - [Analyze](https://rpubs.com/dtminnick/cyclistic_analyze)
  - [Share](https://rpubs.com/dtminnick/cyclistic_share)

And an [executive summary presentation deck](https://github.com/dtminnick/cyclistic/blob/main/inst/extdata/reference/Cyclistic%20Marketing%20Strategy%20Recommendations.pdf)

# Challenges & Solutions

| Challenge                   | Problem                                                                 | Solution                                                                 |
|-----------------------------|-------------------------------------------------------------------------|--------------------------------------------------------------------------|
| Data Redundancies           | Duplicate or inconsistent station names                                 | Cleaned and normalized during the **Process** phase                      |
| Geotracking Inconsistencies | Slight variations in lat/long coordinates for the same locations        | Determined variation was minor and did not significantly affect results  |
| Active Trips by Hour        | Needed to calculate trips active during each hour, including overlaps   | Developed a custom function to calculate overlapping trip intervals      |

# Notes on Reproducibility

Due to the size of the original source files, they are not included in this repo. However, the full workflow and preprocessing steps are documented in the **Prepare** and **Process** notebooks available both [here in the repo](./inst/extdata) and on RPubs (linked above).
