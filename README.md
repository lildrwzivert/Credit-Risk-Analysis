# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
The purpose of this analysis is to build & evaluate different Machine Learning models to predict credit risk.

## Results:

* NR Oversampling model:
- balanced accuracy score = 64%
- precision score = 99%
- recall score = 41%

![Screen Shot 2022-02-20 at 11 40 21 PM](https://user-images.githubusercontent.com/91990957/154890277-ad3749b6-4bf7-41dd-adc6-d91ea2be1c39.png)

* SMOTE model: 
- balanced accuracy score = 63%
- precision score = 99%
- recall score = 63%

![Screen Shot 2022-02-20 at 11 41 52 PM](https://user-images.githubusercontent.com/91990957/154890439-f447e897-85d9-4e03-805a-06501d77d0a4.png)

* Undersampling Cluster Centroid model: 
- balanced accuracy score = 52%
- precision score = 99%
- recall score = 40%

![Screen Shot 2022-02-20 at 11 42 19 PM](https://user-images.githubusercontent.com/91990957/154890485-64f3e55f-2687-45ac-96bd-3d8a9f3e3a4b.png)

* Combination Sampiling SMOTEENN model:
- balanced accuracy score = 66%
- precision score = 99%
- recall score = 63%

![Screen Shot 2022-02-20 at 11 42 41 PM](https://user-images.githubusercontent.com/91990957/154890522-084f47fe-8fbf-43cc-8948-9a933631838c.png)

* Balanced Random Forest Classifier model:
- balanced accuracy score = 79%
- precision score = 99%
- recall score = 91%

![Screen Shot 2022-02-20 at 11 43 14 PM](https://user-images.githubusercontent.com/91990957/154890585-7fd4c7c0-a641-49d7-9408-626c991bfe76.png)

* Easy Ensemble Classifier model:
- balanced accuracy score = 93%
- precision score = 99%
- recall score = 95%

![Screen Shot 2022-02-20 at 11 44 07 PM](https://user-images.githubusercontent.com/91990957/154890673-165815d0-4e0b-4330-9fca-10442795b1b5.png)

## Summary:
Ensembled classifier models have the safest prediction rates and would be most trustworthy for initial credit risk assessment.
