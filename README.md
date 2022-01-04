# EC-Tower_Data_Organizing
This repository mainly contains two scripts:
- One script for data extraction from the EC-tower processed data in order to support the footprint-area calculation
- One script from Dr. [Ayman Nassar](https://github.com/aymnassar) for footprint-area calculation (Slight changes in algorithm have been made based on Ayman's original script)

## Brief introduction about the EC-Tower data extraction
This simple script used in python aims at extracting information from the EC tower (processed) data, a part of the GRAPEX project. The product from this programm can be used to generate the corresponding footprint area, and can also (conveniently) used for TSEB modeling verification.
- Running this script successfully, it requires an EXCEL table providing searching index in order to find the correct record from the EC-tower processed table. Year, month, day, hour, and minute are keys to locate the record in the EC-tower after processed data (table).
- "Request_Demo.xlsx" is a demo data from users' request.
- Manual work are still required, since the processed tables from the GRAPEX project are not exactly the same. Thus, slight modification for this script or the original table (not recommend) is required accordingly.

## Footprint calculation
Please refer Ayman's published paper:<br>
[To what extend does the Eddy Covariance footprint cutoff influence the estimation of surface energy fluxes using two source energy balance model and high-resolution imagery in commercial vineyards?](https://www.researchgate.net/publication/341654936_To_what_extend_does_the_Eddy_Covariance_footprint_cutoff_influence_the_estimation_of_surface_energy_fluxes_using_two_source_energy_balance_model_and_high-resolution_imagery_in_commercial_vineyards)

## Note
Details about this repository (or how to run those python programms) can be found in [Footprint area generating based on eddy covariance records](https://www.hydroshare.org/resource/9118e2c1034e40e4ba4721cd17702f70/#citation) either on the HYDROSHARE platform or the "Manual.pdf" in this repository.

## How to cite:
Please cite the paper below when you are using any script in this repository.<br>
- [Footprint area generating based on eddy covariance records](https://doi.org/10.4211/hs.9118e2c1034e40e4ba4721cd17702f70)<br>
Gao, R., A. Nassar, A. F. Torres-Rua, L. Hipps, M. Aboutalebi, W. A. White, M. Anderson, W. P. Kustas, M. M. Alsina, J. Alfieri, N. Dokoozlian, F. Gao, H. Nieto, L. McKee, J. H. Prueger, L. Sanchez, A. J. Mcelrone, N. B. Ortiz, I. Gowing, C. Coopmans (2021). Footprint area generating based on eddy covariance records, HydroShare, https://doi.org/10.4211/hs.9118e2c1034e40e4ba4721cd17702f70
- [To what extend does the Eddy Covariance footprint cutoff influence the estimation of surface energy fluxes using two source energy balance model and high-resolution imagery in commercial vineyards?](https://www.researchgate.net/publication/341654936_To_what_extend_does_the_Eddy_Covariance_footprint_cutoff_influence_the_estimation_of_surface_energy_fluxes_using_two_source_energy_balance_model_and_high-resolution_imagery_in_commercial_vineyards)<br>
Nassar, A., Torres-Rua, A., Kustas, W., Nieto, H., McKee, M., Hipps, L., ... & Dokoozlian, N. (2020, May). To what extent does the Eddy Covariance footprint cutoff influence the estimation of surface energy fluxes using two source energy balance model and high-resolution imagery in commercial vineyards?. In Autonomous Air and Ground Sensing Systems for Agricultural Optimization and Phenotyping V (Vol. 11414, p. 114140G). International Society for Optics and Photonics.
- [Evapotranspiration partitioning assessment using a machine-learning-based leaf area index and the two-source energy balance model with sUAV information](https://www.researchgate.net/publication/350820947_Evapotranspiration_partitioning_assessment_using_a_machine-learning-based_leaf_area_index_and_the_two-source_energy_balance_model_with_sUAV_information)<br>
Gao, R., Torres-Rua, A., Nassar, A., Alfieri, J., Aboutalebi, M., Hipps, L., ... & Agam, N. (2021, April). Evapotranspiration partitioning assessment using a machine-learning-based leaf area index and the two-source energy balance model with sUAV information. In Autonomous Air and Ground Sensing Systems for Agricultural Optimization and Phenotyping VI (Vol. 11747, p. 117470N). International Society for Optics and Photonics.


Create date: October 14th, 2021<br>
Latest update date: January 3rd, 2022<br>
Main contact: Rui.Gao@usu.edu<br>
