# Project_heart_disease
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. 

Project goal is to predict if someone has disease or not. I will explore what parameters affects on heart disease and visualize connections between them.

For analyting this dataset we used pandas library,numpy,matplot,sckit-learn,seaborn.

Results
|    Model           | Accuracy_score | Cross_val_score|
|--------------------|----------------|----------------|
|KNeighbors          |     88.3 %     |       88.5 %   |
|LogisticRegression  |     89.4 %     |       85.6 %   |
|RandomForest        |     97.3 %     |       95.8 %   |
