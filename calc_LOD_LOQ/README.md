Limit of Detection (LOD) and Limit of quantification (LOQ) method 
-----------------------------------------------------------------
Description
-----------
Perform LOD and LOQ calculation as reported in Vial et al., 1999.

> [!NOTE]
> ** CHECK CAREFELY THE EXPERIMENTAL DESIGN BEFORE STARTING.**

Experimental Design
-----------
- Area count (or intensity) should be evaluate in function of the concentration
- Vial recommend to have at least 5 data points to make the calculation
- Data should be spread within 200 fold (e.g., 1 to 200 or 200 to 40000) 
  to follow paper experimental setting. Better the data are closer to expected LOD better the evaluation is.
- Ideally one or two point are lower than the expected LOD.
- Do not include conc 0 and area 0 into the calculation.
- Data point do necessarly need to be equaly separate (weight normalization).

Getting started
----------------
1. Download the R script
2. set parameter in the R script
3. ## Input should be a csv file with special character (e.g., - % ? ! /)
## Exemple of input and output ... be sure to have similar structure file


Citing
-------
Vial, J.; Jardy, A. Experimental Comparison of the Different Approaches 
To Estimate LOD and LOQ of an HPLC Method. 
Anal. Chem. 1999, 71 (14), 2672-2677. DOI: 10.1021/ac981179n.
