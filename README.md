# OpenMC
Modeling reactor criticality using OpenMC library

Files in this repository:

RBMK_tutorial.txt - Following the tutorial for creating an RBMK reactor model. 
                    Used openmc_data_downloader library to download the ENDFB-7.1-NNDC cross-section data and parametrized uranium enrichment & boron concentration

RBMK_criticality_search.txt - Use search_for_keff() function to perform a criticality search as a function of boron concentration on the parametrized RBMK model

pincell_example.txt - Creating a simple model of a pincell geometry to test all my simulation ideas on before applying them to the more complicated RBMK model. Used openmc_data_downloader library to download the ENDFB-7.1-NNDC cross-section data (and TENDL-2019 data for O18 which was absent from EDFB).
