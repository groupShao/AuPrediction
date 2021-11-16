# Dataset descriptions  
This dataset was originated from experimental data involving process parameters of seed-mediated growth synthesis of gold nanorods/spheres (GNRs/GNSs) solutions and their performance indicators captured from UV-vis-NIR absorption spectrometer.  

The experimental processes (310 groups) consisting of 19 features and absorption spectra data of GNRs/GNSs solutions were preprocessed firstly, then the treated data were randomly divided into training set (80%) and independent test set (20%) for machine learning (ML). Subsequently, 11 ML classifiers were adopted to train the data and make prediction. All the parameters were initialized and adjusted with a 5-fold grid-search cross validation method to find the optimal hyperparameters. The prediction results with 11 classifiers were obtained by comparing such evaluation metrics as accuracy, precision, recall, and receiver operating characteristic (ROC) curves. In addition, coefficient of determination (R<sup>2</sup>) was adopted as the primary performance indicator for XGBoost regressor, which measures the proportion of variance of the outcome that is predictable from the features. 

The column names in the file **'Gold_nanorods_data.csv'** are explained as follows:  
f0：the amount of silver nitrate (AgNO<sub>3</sub>) in the growth solution  
f1：the amount of ascorbic acid (AA) in the growth solution  
f2：the number of prepared seeds in the growth solution  
f3：the age of the reduced growth solution  
f4：the temperature of the reduced growth solution  
f5：the time of stirring mixture solutions after seeds added into growth solution  
f6：the rate of stirring mixture solutions after seeds added into growth solution  
f7：the total volume of the growth solution  
f8：the amount of cetyltrimethylammonium bromide (CTAB) in the growth solution  
f9：the total volume of the seed solution  
f10：The amount of CTAB in the seed solution  
f11：the time of stirring mixtures in the seed solution   
f12：the rate of stirring mixtures in the seed solution  
f13：the age of the seed formation solution  
f14：the temperature of the seed formation solution  
f15：the amount of hydrochloric acid (HCl) in the seed solution  
f16：the amount of sodium borohydride (NaBH<sub>4</sub>) in the seed solution  
f17：the amount of HCl in the growth solution  
f18：the amount of sodium hydroxide (NaOH) in the growth solution  

W<sub>LSPR</sub>：longitudinal surface plasmon resonance absorption peak wavelength  
A<sub>LSPR</sub>/A<sub>TSPR</sub>：the ratio between the maximum absorbance of the longitudinal and transverse SPR bands  
 
