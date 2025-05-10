# GEOG5990M

There are many observed links between residential mobility - the change of occupants in a home or area over time, henceforth referred to as churning (1) - and poverty (1-6). For those who stay in neighbourhoods while others move frequently, the lack of community links and social bonds can exacerbate poor mental health (2) or maintain a concentration of poverty due to in-migration of poor households and out-migration of wealthier households (1, 3). For those migrating households driving churning rates, such high-frequency moves can lead to negative education and health outcomes for children (4) or general dissatisfaction with housing conditions, especially when combined with other drivers of deprivation such as unemployment and substance abuse (5). These dynamics can determine general changes and continuities in areas: Coulton et al.'s (6) study of 10 neighbourhoods and their change over time found that changes in in- and out-migration in neighbourhoods were a more important driver of change in neighbourhoods than any changes in the habits, attributes, or behaviours of those who live in neighbourhoods in the long term. Therefore, for policymakers in Leeds, exploring the relationship between churning and poverty will offer insight into whether churning concentrates poverty in some areas, and therefore presents the opportunity for targeted interventions to relieve deprivation and social isolation.

This code makes use of four data sources:

* Index of Multiple Deprivation (IMD) data by Lower Super Output Area (LSOA), published by the Ministry for Housing, Communities, and Local Government (7). This data shows the IMD decile of each LSOA (usually comprised of 400-1200 households (8)), giving a rough estimate of poverty in each area.
* Churning data by LSOA, published by the Consumer Data Research Centre (CDRC) (9). This data shows the percentage of households by LSOA which have changed occupants between 1997, 1998, 1999 etc. and 2023 - a useful cipher for residential churn over time.
* LSOA centroids, published by the Office for National Statistics (ONS) (10). This data consists of centroids for each LSOA, useful for spatial visualiations.
* LSOA boundaries, published by the ONS (11). This data consists of LSOA boundaries, also useful for spatial visualisations.

This code aims to visualise the relationship between churning (between 1997-2023, 2007-2023, and 2017-2023) and IMD deciles by LSOA, using non-spatial and spatial visualisations. First it merges IMD and churning data and visualises the relationship through a box plot, before creating two spatial datasets based on LSOA centroids and boundaries and using them to visualise the spatial relationships between these two variables, condensing the IMD decile data into three clusters representing low, medium, and high average deprivation.

**Reference List**

1. Fransham, M. 2019. Income and population dynamics in deprived neighbourhoods: measuring the poverty turnover rate using administrative data. *Applied Spatial Analysis and Policy.* [Online]. **12**(2), pp.275-300. [Accessed 10 May 2025]. Available from: https://doi.org/10.1007/s12061-017-9242-6

2. Handley, C.E., Oakley, D. and Saville, C.W. 2020. Residential churn moderates the relationship between economic deprivation and psychiatric admission: evidence from Wales. *J Epidemiol Community Health.* [Online]. **74**(7), pp.560-564. [Accessed 10 May 2025]. Available from: https://doi.org/10.1136/jech-2019-213351 

3. Foulkes, M. and Newbold, K.B. 2008. Poverty catchments: Migration, residential mobility, and population turnover in impoverished rural Illinois communities. *Rural Sociology.* [Online]. **73**(3), pp.440-462. [Accessed 10 May 2025]. Available from: https://doi.org/10.1526/003601108785766525

4. Kingsley, G.T., Jordan, A. and Traynor, W. 2012. Addressing residential instability: Options for cities and community initiatives. *Cityscape.* [Online]. **14**(3), pp.161-184. [Accessed 10 May 2025]. Available from: https://www.jstor.org/stable/41958944

5. Phinney, R. 2013. Exploring residential mobility among low-income families. *Social Service Review.* [Online]. **87**(4), pp.780-815. [Accessed 10 May 2025]. Available from: https://doi.org/10.1086/673963

6. Coulton, C., Theodos, B. and Turner, M.A. 2012. Residential mobility and neighborhood change: Real neighborhoods under the microscope. *Cityscape*. [Online]. **14**(3), pp.55-89. [Accessed 10 May 2025]. Available from: https://www.jstor.org/stable/41958940

7. MHCLG. 2019. English Indices of Deprivation 2019 - LSOA Level. *MHCLG* [Online]. [Accessed 10 May 2025]. Available from: https://opendatacommunities.org/data/societal-wellbeing/imd2019/indices

9. ONS. 2021. *Census 2021 geographies.* [Online]. [Accessed 10 May 2025]. Available from: https://www.ons.gov.uk/methodology/geography/ukgeographies/censusgeographies/census2021geographies 

9. James, T. 2024. CDRC Residential Mobility Index LSOA 1997-2023. *CDRC* [Online]. [Accessed 10 May 2025]. Available from: https://data.cdrc.ac.uk/dataset/cdrc-residential-mobility-index

10. ONS. 2024. Lower layer Super Output Areas (December 2011) EW Population Weighted Centroids. *ONS* [Online]. [Accessed 10 May 2025]. Available from: https://www.data.gov.uk/dataset/5ac2aae6-4f82-4d71-92d6-95e648b085e1/lower-layer-super-output-areas-december-2011-ew-population-weighted-centroids

11. ONS. 2016. Lower Layer Super Output Area (LSOA) boundaries. *ONS* [Online]. [Accessed 10 May 2025]. Available from: https://www.data.gov.uk/dataset/fa883558-22fb-4a1a-8529-cffdee47d500/lower_layer_super_output_area_lsoa_boundaries 
