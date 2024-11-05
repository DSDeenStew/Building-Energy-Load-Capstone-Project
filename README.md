# Building-Energy-Load-Capstone-Project
Energy Efficiency Analysis-> Predict Heating and Cooling Loads of Buildings 

Abstract: 
This study looks into assessing the heating load and cooling load requirements of buildings (that is, energy efficiency) as a function of building parameters.

Project Goal: 
- Develop a model to best predict the heating and cooling load of different buildings based on their characteristic parameters. 
- Examine if the same qaulity of results can be obtained using both Regression and Classification.

Model Building:
- Ridge and Lasso Regularization will be used to create Regression models
- Random Forest and KNN classifiers will be used to develop Classification models.

</br>Dataset:  [dataset](ENB2012_data.xlsx)

Dataset obtained from  the UCI ML Repository: https://archive.ics.uci.edu/dataset/242/energy+efficiency


Source:
The dataset was created by Angeliki Xifara and was processed by Athanasios Tsanas, Oxford Centre for Industrial and Applied Mathematics, University of Oxford, UK).

Data Set Information:

We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is rounded to the nearest integer.

Attribute Information:
The dataset contains eight attributes (or features, denoted by X1...X8) and two responses (or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each of the two responses. 

Specifically: 
-	X1	Relative Compactness 
-	X2	Surface Area 
-	X3	Wall Area 
-	X4	Roof Area 
-	X5	Overall Height 
-	X6	Orientation 
-	X7	Glazing Area 
-	X8	Glazing Area Distribution 
-	y1	Heating Load 
-	y2	Cooling Load
 
