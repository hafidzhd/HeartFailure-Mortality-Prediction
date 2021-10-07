# HeartFailure-Mortality-Prediction

This project purpose is to create a model prediction for Heart Failure Mortality based on patient condition.


## Dataset
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide.
Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

__Attributes :__
1. age
2. anaemia : Decrease of red blood cells or hemoglobin (no anemia=0 , has anemia=1|)
3. creatinine_phosphokinase : Level of the CPK enzyme in the blood (mcg/L)
4. diabetes  : If the patient has diabetes (no diabetes =0 , has diabetes = 1)
5. ejection_fraction: Percentage of blood leaving the heart at each contraction (percentage)
6. high_blood_pressure  :If the patient has hypertension (no hypertension = 0 , has hypertension=1)
7. platelets : Platelets in the blood (kiloplatelets/mL)
8. serum_creatinine : Level of serum creatinine in the blood (mg/dL)
9. serum_sodium : Level of serum sodium in the blood (mEq/L)
10. sex : woman or man (female=0 , male =1)
11. smoking ( no smoking=0, smoking =1)
12. time : Follow-up period (days)
13. death_event ( not dead=0 , dead=1)



_Citation_<br>
_Davide Chicco, Giuseppe Jurman: Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making 20, 16 (2020). [Link](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5)_


You could download dataset from [here](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data).<br>


## Goals

Goals of this notebook is to create a model that could predict mortality caused by Heart Failure and found out how the mortality trends against age , gender and others cormobid disease.