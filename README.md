# Water-Quality-Prediction

Water is a basic human need. Also, water is a key requirement for the agriculture and industrial sectors as well. Around 1.7% of the ground water is available in the world but only around 0.8% of the earth’s water is fresh  water.Even though people have a limited amount of fresh water to use, the water pollution makes thatamount even scarcer. Unsafe water kills more people each year than war and all other forms of violence combined. Hence, water pollution has become a major crisis in the world.The main objective of this analysis is to build a model to predict the potability of water of are source using water quality metrics. We are also interested in finding out which factors affect the most for the potability of the water.


Logistic regression, Decision Tree, Random Forest and XGBoost machine learning models were fitted. The PH value, Sulfate, Hardness, Solids, and chloramines are the factors that mostly impact whether the water body can be used for the consumption or not since these variables were chosen as the important variables in most of the techniques. The XGBoost model was selected as the best model with 0.65 AUC score and 0.70 accuracy to predict whether the water body is safe for human consumption. 
A website was created with the prediction feature using the best model.

https://user-images.githubusercontent.com/66732458/162116651-3b525b0a-94f3-44f9-b223-131a4bbcdf3e.mp4

