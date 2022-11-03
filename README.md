# OpenMC
Modeling reactor criticality and depletion using OpenMC library

Files in this repository:

pincell_example.txt - Creating a simple model of a pincell geometry to test all my simulation ideas on before applying them to the more complicated RBMK model. Used openmc_data_downloader library to download the ENDFB-7.1-NNDC cross-section data (and TENDL-2019 data for O18 which was absent from EDFB).

pincell_postprocessing.txt - Read simulation results from statepoint file and create plots of flux spectrum and spatial distributions of flux, absorption, and fission.

pincell_depletion.txt - Use depletion interface to simulate fuel pin depletion over 6 months and evaluate how k_eff changes over time

pincell_depletion_post_processing.txt - Read simulation results from statepoint file and plot k_eff(t) and concentrations of U235 & Xe135 over time.

RBMK_tutorial.txt - Following the tutorial for creating an RBMK reactor model. 
                    Used openmc_data_downloader library to download the ENDFB-7.1-NNDC cross-section data and parametrized uranium enrichment & boron concentration

RBMK_criticality_search.txt - Use search_for_keff() function to perform a criticality search as a function of boron concentration on the parametrized RBMK model
