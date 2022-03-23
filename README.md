# This folder contains all of the geospatially related scripts for the analyses conducted in the manuscript "Contribution of soil algae to the global carbon cycle"


Manuscript reference: Jassey V., Walcker, R., Kardol, P., Geisen, S., Heger, T., Lamentowicz, M., Hamard, S., Lara, E. (2022) Contribution of soil algae to the global carbon cycle. New Phytologist. https://doi.org/10.1111/nph.17950.

Analysis presented here have been performed using the Jupyter notebook programed in Python and R language.

!! Please note: this repository contains the scripts used to run the actual analysis presented in the manuscript. Since the time of publication, aspects of Google Earth Engine may have changed and thus some of these scripts could create errors that did not originally occur.

# Here is a an outline describing how the analyses took place:

1- Sample the covariate layers at each unique soil algae sample point; the associated script is:
  Covariate_sampling_102pts.ipynb
  
2- Perform variable reduction analyses to acquire potential variable lists; the associated script is:
  Variable_Reduction.ipynb
  
3- Grid search across all models of interests and variable lists of interests; the associated script is:
  XXXXXXX
  
4- Choose the "best model", ensemble it with itself (in the case of random forest), and produce the final maps; associated scripts are:
  XXXXXXX
  XXXXXXX
  SoilAlgaeProductivity_10_Model_Run.ipynb
  SoilAlgaeProductivity_Average_Map_Creation.ipynb
  
5- Perform post hoc analyses, including total productivity calculations, interpolation/extrapolation mapping, and predicted/observed assessment; associated scripts are:
  SoilAlgaeProductivity_Global_Abundance_Calculations.ipynb
  Nematode_Map_of_ExtInt.ipynb
  XXXXXXXX
  XXXXXXXX
