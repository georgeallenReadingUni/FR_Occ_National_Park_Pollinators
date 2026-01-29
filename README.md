# FR_Occ_National_Park_Pollinators
R scripts, Output Files and Figures used in the spatial dataset generation, occupancy modelling and analysis of polliantor data from France's national parks. Project lead is George Allen. Research is part of a PhD project in collaboration with the University of Reading (UK), UK Centre for Ecology and Hydrology and POLLINIS (France).


# Scripts:

# 1 - Multispecies distributional trends
Script for calculating occupancy trends and composite growth rates for the full dataset across all years in each zone, as well as repeating this for the converged dataset and plotting together.

# 2 - Rare vs Common species analysis
Script for giving species rare/common labels, then calculating and plotting of trends, composite growth rates, species richness and richness over time for these two groups.

# 3 - Multispecies distributional trends - Pollinator groups
Script for calculating and plotting group-wise occupancy trends for all insect groups (N=12).

# 4 - NMDS and Turnover
Script for calculating NMDS community level indices, change over time and directionality of change.

# 5 - Resolving taxonomic inconsistencies
Script for appending names to species that underwent taxonomic changes over the period. Mainly butterflies. Also for merging Leptidea sinapis/juvernica species group. 

# Supplementary Material 2. Occupancy Modelling Script
Script used to model pollinator occupancy from 2000-2023, using the 'sparta' package developed by Isaac et al. (2024). Outputs the necessary species occupancy estimates per zone, per year, per species, used for final analyses. 






# Input files: 
Contains the necessary files for generating occupancy estimates using GBIF records, conducting analyses on occupancy data, and appending guilds/groups to species data.



# Figures
Contains figures produced by scripts 1-5



# Data outputs
Contains parameters and values for analyses produced by scripts 1-5 (e.g. HDIs for zone-wise comparsions of species occupancy)
 
