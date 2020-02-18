Welcome to MCICAD!

Overall Introduction:

The main GUI(MCICAD) has 4 fundamental pushbuttons: 
1.Preprocessing
2.Network Analysis
3.Model Building
4.Diagnosis

wich are related to 4 subGUIs:
1.DPARSFA
2.FEAX
3.MDBDX
4.CAD

For doctors,
you need to go through the process of 'Preprocessing', 'Network Analysis' and 'Diagnosis'
These process will help you with selecting the important features from patients' fMRI images,
and 2 default model(dfaucmodel.mat & dfthdmodel.mat) are provided for discrimination, 
this two model were built according to our lately research:
(Computer Aided Diagnosis of Mild Cognitive Impairment Based on SVM) 
which discussed the optimal  feature selection method and parameter settings.

For researchers,
firstly, you need to go through the process of 'Preprocessing', 'Network Analysis', 'Model Building' first
to extract features from your train data and get your own model.
Secondly, you need to go through the process of 'Preprocessing' and 'Network Analysis'
to selecting the important features from test data.
Thirdly, load your own model and processed test data into the subGUI--CAD to discriminate the test data.



