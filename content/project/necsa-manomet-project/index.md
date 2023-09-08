---
date: "2022-04-25T00:00:00Z"
external_link: 
image:
  caption: Recorded water temperature (celsius) by NeCSA Field Station from July 2016 to September 2018. Field stations along the Maine and New Hampshire coast show similar broad seasonal trends but different daily fluctuations in temperature.
  focal_point: Smart
summary: Developing a data pipeline for monitoring temperature and intertidal marine communities in the Gulf of Maine collected by the Northeastern Coastal Station Alliance and Manomet. 
tags:
- Coastal Monitoring
- Temperature
- Quality Control
- Environmental Data 
- Biodiversity
- Citizen Science
title: Developing a data pipeline for monitoring temperature and intertidal biodiversity data in the Gulf of Maine. 
---

Northeastern Coastal Station Alliance (NeCSA) is a collaboration of coastal field stations in the Gulf of Maine working together to understand climate change impacts in this rapidly changing system. With the help of volunteers, member field stations have been working to gathering temperature and intertidal community data at different sites along the Gulf of Maine since 2016, to establish valuable baseline data on changes in the Gulf of Maine. 

Manomet is a non-profit organization that uses science and collaboration to improve the health of flyways, coastal ecosystems, and working lands and seas. The Fisheries Division works to sustain New England’s fishing heritage in a changing Gulf of Maine by restoring fisheries and diversifying opportunities in fishing and aquaculture.

The aims of this community project are several-fold:

1. Develop a protocol and data pipeline for carrying out quality assurance of the data, including developing a data workflow for future NeCSA data collection efforts and analysis. 

2. Identify ways to improve NeCSA's data collection process including developing standards and methodologies for data recording. 

3. Create and design meaningful ways to visualize, explore, and present trends in the data (water temperature data, biological community data – species occurrence, species counts, biodiversity indices, and more) collected by NeCSA and Manomet to build a greater understanding of the Gulf of Maine's intertidal communities and how they're changing. 


Specific milestones for the short-term for each of these goals include:

1. Create a data pipeline that takes the data from collection through to analysis ready:
   - Designing data visualizations and scripts for quality assurance and quality control checking:
        - Pre-process the water temperature data to remove inaccurate temperature readings resulting from low tides.
        - Create automated checks to flag unusual data entries.
2. Identify ways to improve the data collection process based on:
   - Issues that arise in the data processing.
   - Design of data collection sheets. 
   - Record items that are unclear during the data process.
   - Create a codebook for the data that will aid in further data processing and volunteer collection effforts.  
   - Bring the pieces above together to create a sketch of all the steps of the process including quality checks that should occur at each stage. 
  
3. Summarize, analyze, and present key preliminary findings:
    - Develop an Rmarkdown template to report overall NeCSA and Manomet data trends and results for individuals sites. 
    - Explore biological questions including:
        - What species are most common? 
        - How do they vary across sites and through time?
        - Do we see evidence of increases in invasive species like green crabs over time?
        - What changes do we see in intertidal crab survey data collected by [Manomet](https://www.manomet.org). 
        - How do the abundance and biodiversity measures vary across different sites? over time? and are these differences explained by environmental variables like temperature? or other site-specific characteristics?
    - Taking a deeper dive into Manomet's crab data surveys:
        - How does crab density change over time and within and between sites? Are the differences statistically meaningful?
        - What species of crabs are found, native crabs or other invasives (Asian shore crab), changing sex ratios, shell status and timing of pre-molt/soft shells, size distributions etc.
        - How do the above trends correlate with environmental data (salinity and temperature)? What available environmental data might be most suitable for the site (hobo loggers at Robinhood Cove, Kennebec Estuary Land Trust, Friends of Casco Bay station off sandy point for the New Meadows site). 
    - Develop an interactive shiny application that allows users to explore and query the Gulf of Maine data.
 
Student efforts will be continued this summer by an Environmental Data Initiative (EDI) Fellow, who will use the pipeline developed to collate, clean, and analyze all five years of data from the 10 member stations.

### What skills you can expect to learn:

- Importing, cleaning and preparing data
- Design tests for checking data quality
- Data Visualization
- Automated report writing with Rmarkdown
- Statistical analysis techniques for working with biological data
- Science communication
- Knowledge exchange including documenting and sharing coding knowledge with community partners on analyzing environmental data from start to finish. 

### Data

- Overview of the data on [Github](https://laurielbaker.github.io/NeSCA-Field-Stations/NeCSA-Data-Exploration.html) and the [GitHub repository](https://github.com/LaurieLBaker/NeSCA-Field-Stations).

### Resources

These resources are a starting place which you can add to.

**Manomet**

- [Impacts of Green Crabs on Softshell Clams by the Downeast Institute](https://downeastinstitute.org/uncategorized/impacts-of-green-crabs-on-soft-shell-clams/)
- [Article: Life History and Population Dynamics of Green Crabs (Carcinus maenas)](crab_life_history.pdf)
- [Manomet crab sampling protocol: Assessing Intertidal Populations of the Invasive European Green Crab](manomet_green_crab_protocol.pdf)

**NeCSA**

- [Gulf of Maine Warming Update: 2021 from the Gulf of Maine Research Institute](https://www.gmri.org/stories/gulf-of-maine-warming-update-summer-2021/)

### Acknowledgments

Special thanks to [Matt Clayton '23](https://github.com/mlclayton6) for preparing and creating initial visualizations of the data. 
