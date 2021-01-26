# Master-thesis about museums_economic_impact

The research statistically assesses the strength and direction of local relationships between the Moscow museums and economically active citizens living or walking around their neighbourhood. Drawing on consulting reports (Deloitte, 2019; Feedvisor, 2019) about Russian market we used numbers of active youth and rich people as a proxy of economically active citizens. 

Methodology
The attribution to one of these groups was made by company Locomizer based on the one-month history of GPS signals of smartphones occurred inside Moscow boarders. According to their patented methodology, they give affinity scores to users based on the distance from POI’s of particular category statistic as well as frequency of observations. Then, their monthly numbers for the period from January 2019 till July 2020 were aggregated by H3 system hexagons of 9-th dimension.

To digitize museums their coordinates were extracted from OSM and Moscow open and mapped against hexagon centroids. Two variables, numbers of museums within 350m and within 1-km distance, were calculated. Secondly, it was indispensable to account for other features of build-up environment that may attract target groups of residents. To this list we added walkability score, street connectivity and transport accessibility levels. To match them with other variables they were also calculated for each hexagon centroid. Last, month feature was transformed into two categorical variables, one related to season number and another one related to different movement restrictions set by the government due to COVID-19 pandemic: normal, lockdown and recover periods.

Having all features ready, we, first, built two OLS regressions, one per each affinity score, and then, six GWRs on cross-section of the residents’ target groups and three time periods related to movement restrictions. The results were mapped and coloured by the direction of relationships and individually analysed. 
