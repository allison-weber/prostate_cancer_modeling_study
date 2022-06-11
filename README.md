# prostate_cancer_modeling_study

Data and patient fitting images for the paper "High accuracy indicators of treatment failure for
prostate cancer – a modeling study".

## Contents

The orginal_data folder holds the original data from a clinical trial of intermittent treatment with androgen deprivation therapy for prostate cancer from the Vancouver Prostate Centre (1). We obtained from https://github.com/ttphan4/cell_quota_model_of_prostate_cancer under "Core fitting and forecasting". Each csv file represents the data for one patient.  

The clean_data folder holds the same files as the orginal_data folder but they have been slightly modified to clean the data.

The figures folder holds all the images of the plots we created from applying our mathmatical model to every patient. 
- The ParamFig_Ptn<#> images show the values of 3 of our model's key parameters.
- The SlnFig_Prn<#> images show the actual model fitting and the predicted tumor sizes. 

## Columns in Patient Data Files
1. patient number
2. day
3. blood concentration PSA
4. androgen + hormones
5. cycle number of treatment (1 full cycle includes time on treatment and off treatment)
6. whether patient on/off (1=on, 0=off... in code switch to 0=on)

## References
1. Bruchovsky N, Klotz L, Crook J, Malone S, Ludgate C, Morris WJ, et al. Final results of the Canadian prospective phase II trial of intermittent androgen suppression for men in biochemical recurrence after radiotherapy for locally advanced prostate cancer. Cancer. 2006;107:389–95. 

