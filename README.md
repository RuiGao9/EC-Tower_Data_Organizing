# EC-Tower_Data_Organizing
This repository mainly contains two scripts:
- One script for data extraction from the EC-tower processed data in order to support the footprint-area calculation
- One script from Dr. Ayman Nassar for footprint-area calculation (Slight changes have been made based on Ayman's original script)

## Brief introduction about the data extraction
This simple script used in python aims at extracting information from the EC tower (processed) data, a part of the GRAPEX project. The product from this programm can be used to generate the corresponding footprint area, and can also (conveniently) used for TSEB modeling verification.
- Running this script successfully, it requires an EXCEL table providing searching index in order to find the correct record from the EC-tower processed table. Year, month, day, hour, and minute are keys to locate the record in the EC-tower after processed data (table).
- "Demo_Request.xlsx" is a demo data from users' request.
- Manual work are still required, since the processed tables from the GRAPEX project are not exactly the same. Thus, slight modification for this script or the original table (not recommend) is required accordingly.

## Footprint calculation
Please refer Ayman's published paper:<br>
[To what extend does the Eddy Covariance footprint cutoff influence the estimation of surface energy fluxes using two source energy balance model and high-resolution imagery in commercial vineyards?](https://www.researchgate.net/publication/341654936_To_what_extend_does_the_Eddy_Covariance_footprint_cutoff_influence_the_estimation_of_surface_energy_fluxes_using_two_source_energy_balance_model_and_high-resolution_imagery_in_commercial_vineyards)

## How to cite:
Please also cite the paper below when you are using any script in this repository.<br>
[Evapotranspiration partitioning assessment using a machine-learning-based leaf area index and the two-source energy balance model with sUAV information](https://www.researchgate.net/publication/350820947_Evapotranspiration_partitioning_assessment_using_a_machine-learning-based_leaf_area_index_and_the_two-source_energy_balance_model_with_sUAV_information)


Create date: October 14th, 2021<br>
Latest update date: October 14th, 2021<br>
Main contact: Rui.Gao@usu.edu<br>
