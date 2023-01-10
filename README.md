# Lung-Cancer-Prediction-using-XGBoost


Introduction

This project report is about lung cancer prediction using XGBoost. XGBoost is a machine learning algorithm developed by Tianqi Chen and Carlos Guestrin 
in 2016. It is an efficient and accurate algorithm that has been used in many applications, including medical diagnosis. 
In this project, I will be using XGBoost to predict lung cancer from a dataset of individuals' characteristics. 

Specifically, we will use a dataset of individuals' 1000 non-null   int64
 1   age                       1000 non-null   int64
 2   gender                    1000 non-null   int64
 3   air_pollution             1000 non-null   int64
 4   alcohol_use               1000 non-null   int64
 5   dust_allergy              1000 non-null   int64
 6   occupational_hazards      1000 non-null   int64
 7   genetic_risk              1000 non-null   int64
 8   chronic_lung_disease      1000 non-null   int64
 9   balanced_diet             1000 non-null   int64
 10  obesity                   1000 non-null   int64
 11  smoking                   1000 non-null   int64
 12  passive_smoker            1000 non-null   int64
 13  chest_pain                1000 non-null   int64
 14  coughing_of_blood         1000 non-null   int64
 15  fatigue                   1000 non-null   int64
 16  weight_loss               1000 non-null   int64
 17  shortness_of_breath       1000 non-null   int64
 18  wheezing                  1000 non-null   int64
 19  swallowing_difficulty     1000 non-null   int64
 20  clubbing_of_finger_nails  1000 non-null   int64
 21  frequent_cold             1000 non-null   int64
 22  dry_cough                 1000 non-null   int64
 23  snoring                   1000 non-null   int64
 24  level                     1000 non-null   int64 
 
Data

The dataset used for this project is from https://data.world/cancerdatahp/lung-cancer-data. 
This dataset includes demographic, medical, and lifestyle data from over 1,000 individuals. The variables we will be using to predict lung cancer are: age, gender, smoking status, and other characteristics.

Methodology

The XGBoost algorithm was used to create a model to predict lung cancer. First, the dataset was split into training and test sets. 
The training set was used to develop and optimize the model. The model was then evaluated on the test set to assess its accuracy.

Results

The XGBoost model achieved an accuracy of 98.18% on the test set. This model was able to accurately predict whether an individual had lung cancer or not based on their age, gender, smoking status, and other characteristics.

Conclusion

In conclusion, XGBoost was able to accurately predict whether an individual had lung cancer or not based on their age, gender, smoking status, and other characteristics. 
The model achieved an accuracy of 98.18%, which is a highly accurate result. This model can be used to help identify individuals who may be at risk for lung cancer and can be used to assist in early diagnosis and treatment.
