# LAPD-ArrestsSpatialAnalysis
Arrest records from the LAPD: Do arrest locations have a statistical significant tendency to cluster in certain communities?
In this analysis, we take on the policing in Los Angeles, specifically looking at arrest records from the LAPD. Do arrest locations have a statistical significant tendency to cluster in certain communities? To answer this question, we not only look at the location of recorded arrests in the city, but compare these locations with other arrests. In short, we are seeking to see where spatial correlations occur based on the data. Our approach is:

1. Import census block group boundaries for Los Angeles
2. Import arrest data from the LA Open Data Portal
3. Spatially join the two datasets
4. Normalize the data to create arrests per 1000
5. Conduct global spatial autocorrelation using Moran's I

Map of arrests in LA in the year 2023


![image](https://github.com/user-attachments/assets/c99c8fcd-a750-481c-ace5-0a7f194bfa43)
