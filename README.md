# NGSIM Data Evaluation Toolkit
This is a toolkit that provides evaluation an input NGSIM dataset 
base on the comparison with ground truth data (I-80 16:00-16:15 camera 6) provided by Coifman et al.

To use the toolkit, run the jupyter notebook with customized configuration.

##TODO Evaluation Results
Result Tabular | Raw NGSIM data | Punzo's Reconstructed Data | EMD-based Reconstructed Data
--- | --- | --- | --- |
Mean of speed | 26.21 | 26.55 | 26.03
Std of speed | 12.90 | 12.92 | 12.99
Max speed | 95.30 | 88.57 | 92.00
Min speed | 0.00 | 0.00 | 0.00
Mean of accleration | -0.09 | -0.17 | 0.04
Std of accleration | 5.43 | 3.03 | 1.89
Max accleration | 11.20 | 14.83 | 11.20
Min accleration | -11.20 | -46.25 | -11.20
MSE of position | 24.71 | 23.13 | 24.34
MSE of speed | 7.98 | 4.94 | 3.26
MSE of accleration | 29.97 | 7.33 | 2.45
