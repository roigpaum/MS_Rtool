Limit of Detection (LOD) and Limit of quantification (LOQ) method 
-----------------------------------------------------------------
Description
-----------
Perform LOD and LOQ calculation as reported in Vial et al., (1999) using the residual standard deviation of a weighted regression between area count in function of the concentration.

> [!NOTE]
> ** CHECK CAREFELY THE EXPERIMENTAL DESIGN BEFORE STARTING.**

Experimental Design
-----------
- Area count (or intensity) should be evaluate in function of the concentration.
- Vial recommend to have at least 5 data points to make the calculation.
- Data should be spread within 200 fold (e.g., 1 to 200 or 200 to 40000) 
  to follow paper experimental setting. Better the data are closer to expected LOD better the evaluation is.
- Ideally one or two points are lower than the expected LOD.
- Do not include conc zero and area zero into the calculation.
- Data point do not necessarly need to be equaly separate (weight normalization).

Getting started
----------------
1. Download the R script and save it on an empty folder (your work directory).
3. Set parameter in the R script.
4. Check Input file: should be a csv file with no special character (e.g., - % ? ! /).
5. Check given example of input and output ... be sure to have similar structure (header, column) file.
6. Output LOD and LOQ unit are similar as the input.

Citing
-------
Vial, J.; Jardy, A. Experimental Comparison of the Different Approaches 
To Estimate LOD and LOQ of an HPLC Method. 
Anal. Chem. 1999, 71 (14), 2672-2677. DOI: 10.1021/ac981179n.
