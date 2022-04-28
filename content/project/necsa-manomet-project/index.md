---
date: "2022-04-25T00:00:00Z"
external_link: 
image:
  caption: Monitoring temperature and biodiversity at coastal stations across Maine
  focal_point: Smart
summary: Creating a data pipeline for monitoring temperature and biodiversity along the coast of Maine and New Hampshire with NeCSA and Manomet
tags:
- Coastal Monitoring
- Temperature
- Quality Control
- Environmental Data 
- Biodiversity
- Citizen Science
title: Creating a data pipeline for monitoring temperature and biodiversity along the coast of Maine and New Hampshire with NeCSA and Manomet
---

Northeastern Coastal Station Alliance (NeCSA) is a collaboration of coastal field stations in the Gulf of Maine working together to understand climate change impacts in this rapidly changing system.

Member field stations have been working with volunteers to gather temperature and intertidal data since 2016.

The goal of this community project is several-fold. First, to create and design meaningful ways to visualize and explore trends in the data (water temperature data, biological community data – species occurrence, species counts and more) to build understanding of climate changes across the Gulf of Maine. Second, to develop a protocol and script for carrying out quality assurance of the data, including developing a data workflow for future NeCSA data collection efforts and analysis. Third,

Specific milestones for the short-term include:

1. Create a data pipeline that takes the data from collection through to analysis ready:
   - Designing data visualizations and scripts for quality assurance and quality control checking:
        - pre-process the water temperature data to remove inaccurate temperature readings resulting from low tides.
        - double checking data entry values (what are errors and how can we design code to catch them)?
2. Identify ways to improve the data collection process based on:
   - Issues that arise in the data processing
   - Design of data collection sheets. 
   - Record questions and a codebook for the data. 
   - Create a sketch of all the steps of the process including quality checks that should occur at each stage. 
  
3. Summarize, analyze, and present key preliminary findings:
    - Develop an Rmarkdown template to report overall NeCSA and Manomet data trends and results for individuals sites. 
    - Explore biological questions including:
        - What species are most common? 
        - How do they vary across sites and through time?
        - Do we see evidence of increases in invasive species like green crabs over time?
        - TWhat changes do we see in intertidal crab survey data collected by [Manomet](https://www.manomet.org). 
        - How do the abundance and biodiversity measures vary across different sites? over time? and are these differences explained by environmental variables like temperature? or other site-specific characteristics?
    - Taking a deeper dive into Manomet's crab data surveys:
        - How does crab density change over time and within and between sites? Are the differences statistically meaningful?
        - What species of crabs are found, native crabs or other invasives (Asian shore crab), changing sex ratios, shell status and timing of pre-molt/soft shells, size distributions etc.
        - How do the above trends correlate with environmental data (salinity and temperature)? What available environmental data might be most suitable for the site (hobo loggers at Robinhood Cove, Kennebec Estuary Land Trust, Friends of Casco Bay station off sandy point for the New Meadows site). 
    - Develop an interactive shiny application that allows users to explore and query the Gulf of Maine data.
 

Student efforts will be continued this summer by an Environmental Data Initiative (EDI) Fellow, who will expand the analysis to collate and clean all five years of data from 10 members stations.