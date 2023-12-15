# Capstone01
Repository for Capstone
Executive Summary

The project aims to tackle the issue of how communicable disease and various CDC health metrics like vaccination rates impact educational enrollment, performance, and funding.  My background in biotechnology motivated me to address the question of how disease impacts education.  The data will come from CDC APIs and the urban education data API.  There may be gaps in data that must be filled by seeking other datasets that relate to location data for mapping. 

Motivation

My graduate degree was in biotechnology and a large portion of my coursework focused on immunology, virology, and immunology so I have an existing interest in the subject from that.  In terms of how it relates to school performance, I just find the possible relationship interesting but I’m open to finding new data points along the way to investigate.  I think it would be interesting to find insight into the effects of a few communicable diseases on any metric I can find.

Data Question

 I want to investigate the link between different communicable diseases, vaccination rates, and other health metrics and the effects on school performance/school type (ie. Are areas with more elementary schools more prone to certain health outcomes?) in those areas.  I want to start with visualizing these trends on a national level (regional/state categories) and then doing a deeper dive into Tennessee on a county level.  What states tend to test the highest and is this correlated to any of the above health metrics? Do states with more negative health metrics perform better?  What does the distribution of schools in these states look like vs the state population and does this have an effect on health?  In Tennessee, are counties with more schools more likely to have increased or lowered vaccination rates in comparison to other counties? 

Minimum Viable Product (MVP)

MVP:  I would like to make a dashboard in Tableau that begins with graphing regional relations between health metrics/disease and school statistics.  The initial graphs will be broader scope to show differences between regions (likely split into 5 regions ie. Midwest, southeast, Northeast, southwest, northwest regions of the US). It will contain graphs comparing the relationships between school distribution, school population, and some testing criteria with health metrics like vaccination rates, rates of diabetes, and other disease markers.  From that point I want to have another portion of the dashboard that shows a narrower view of the Tennessee area to allow for identification of trends in TN and to show differences between TN trends and national trends.    I then want to spend time highlighting a few diseases or health metrics of interest that show novel associations with education performance, funding, or distribution of schools.  This section should also highlight any counties/states that stand out in terms of association with a particular metric.  For example if a particular district has abnormally low vaccination rates compared to the national average I would show that visualization here by graphing vaccination rate vs. testing scores or school distribution/funding.  Visuals for this section will likely be a mix of maps to show areas of density and some histograms/bar graphs to show distributions.  I may also include some line graphs to show if a particular metric changes over time.  Finally, I want to have a section that is largely dedicated to mapping and answering the question of which areas are most affected when accounting for student populations and possibly median income level.  The intended audience could be local school districts or governing bodies involved in education.  Also showing how schools can act as vectors for disease to spread can be of interest to an audience interested in epidemiology in youth.

Schedule (through <1/4/24 >)
1.	Get the Data (11/22/23)
2.	Clean & Explore the Data (12/2/23)
3.	Create Presentation of your Analysis (12/13/23 -12/15/23)
-	Should be a presentation, but could include a Jupyter Notebook or dashboard in Excel, Tableau, or PowerBI
4.	Internal demos (12/15/23)
5.	Demo Day!! (1/4/24)

Data Sources
https://open.cdc.gov/data.html  -- data for notifiable diseases and other health metrics from API
https://educationdata.urban.org/documentation/#direct_access – school data 
https://www.tn.gov/education/districts/federal-programs-and-oversight/data/data-downloads.html
https://www.nationsreportcard.gov/profiles/stateprofile?chort=1&sub=RED&sj=AL&sfj=NP&st=MN&year=2022R3


Known Issues and Challenges
Explain any anticipated challenges with your project, and your plan for managing them. Be sure to include:
●	If you need to request data or an api key
●	Based on your data sources, known data cleaning steps

•	I will likely need to clean the data in order to derive usable location data
•	It’s possible that it will be difficult to show any significant effect with many of the diseases so I may have to use other health metrics that are tracked in the CDC data.
•	There may be gaps in the data that I need to fill with some other dataset.  
