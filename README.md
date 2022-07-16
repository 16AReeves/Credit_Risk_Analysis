# Credit_Risk_Analysis
---
## Module 17: Learning about Supervised Machine Learning
---
### Background
---
#### This module looks at credit card risk, using supervised machine learning. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, six different machine learning models were used to evaluate risk. This dataset comes from LendingClub, which will be sampled using RandomOverSampler, SMOTE, ClusterCentroids, SMOTEEN, BalancedRandomForestClassifier, and EasyEnsembleClassifier. The last two models are known for helping reduce bias in the data.  
---
### Results
---
#### Below are the results from each of the above machine learning models:
| RandomOverSampler Confusion Matrix | RandomOverSampler Classification Report |
| --- | --- |
![cm_random](https://user-images.githubusercontent.com/98365963/179370866-cea3c162-a209-47a9-bfb1-ae64d5a9bc2c.PNG) | ![random_sampling](https://user-images.githubusercontent.com/98365963/179370828-b994cc3c-90a8-496d-a4f8-6a60f561cc75.PNG)
| SMOTE Confusion Matrix | SMOTE Classification Report |
![cm_smote](https://user-images.githubusercontent.com/98365963/179371098-9813846f-6629-4cd5-ab14-da7275875e7b.PNG) | ![smote_sampling](https://user-images.githubusercontent.com/98365963/179371104-fad91abd-e318-43ae-81c1-6198259bc46d.PNG)
| ClusterCentroids Confusion Matrix | ClusterCentroids Classification Report |
![cm_undersampling](https://user-images.githubusercontent.com/98365963/179371195-fd59c44d-2d84-4e32-8310-855194c99a43.PNG) | ![undersampling](https://user-images.githubusercontent.com/98365963/179371202-a49b9e82-85cd-478b-aedf-96aa9296aba2.PNG)
| SMOTEEN Confusion Matrix | SMOTEEN Classification Report |
![cm_combo](https://user-images.githubusercontent.com/98365963/179371234-cacf5e4b-5778-4423-a0e2-23534bc36590.PNG) | ![combo_sampling](https://user-images.githubusercontent.com/98365963/179371239-135bb83f-30ca-4f27-8e16-ae3cb80a06b3.PNG)
| BalancedRandomForestClassifier Confusion Matrix | BalancedRandomForestClassifier Classification Report |
![cm_balancedforest](https://user-images.githubusercontent.com/98365963/179371274-6b4287ce-73e6-4202-a7b1-bde74cb776fb.PNG) | ![balancedforest_sampling](https://user-images.githubusercontent.com/98365963/179371279-96bcb9b1-e6f0-4666-a4c7-99a1cebcbe2d.PNG)
| EasyEnsembleClassifier Confusion Matrix | EasyEnsembleClassifier Classification Report |
![cm_ensamble](https://user-images.githubusercontent.com/98365963/179371293-0fc05fb2-f6a4-4b64-a9b5-e3bf18054c0f.PNG) | ![ensamble_sampling](https://user-images.githubusercontent.com/98365963/179371299-7b6d6386-c1c7-4051-ac82-6060091290a9.PNG)
---
* #### The RandomOverSampler machine learning model has an accuracy score of 0.65, percision score of 0.99, and a recall score of 0.66.
* #### The SMOTE machine learning model has an accuracy score of 0.65, a percision score of 0.99, and a recall score of 0.66.
* #### The ClusterCentroids machine learning model has an accuracy score of 0.65, a percision score of 0.99, and a recall score of 0.44.
* #### The SMOTEEN machine learning model has an accuracy score of 0.51, a percision score of 0.99, and a recall score of 0.61.
* #### The BalancedRandomForestClassifier machine learning model has an accuracy score of 0.79, a percision score of 0.99, and a recall score of 0.91.
* #### The EasyEnsembleClassifier model has an accuracy score of 0.93, a percision score of 0.99, and a recall score of 0.94.
---
### Summary
---
#### The machine learning model that has the highest likelyhood of a good outcome is the last model: EasyEnsembleClassifier. EasyEnsembleClassifier is better than the others in this case because it has a high accuracy score along with high percision and recall. This means the EasyEnsembleClassifier model is aggressive with determining accurate credit risk. This model does have a high number of false positives, however it has the lowest number out of the other 5 models. This model does have the lowest false negative results out of the other models, meaning only a few fraud credit cases will get through. 
