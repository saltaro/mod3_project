# Mod-3-Project

#### Ben Inoyatov

## Introduction
---
Under represented groups suffer more from disease and illness in America than others. This project will focus on predicting diabetes in Pima Native American Woman Can we accurately predict diabetes in minority groups? We will use patient statistics like glucose level, insulin level, age, BMI, family history, blood pressure and others. 

- Data comes from Kaggle ([link](https://www.kaggle.com/uciml/pima-indians-diabetes-database)). 
- Most visualizations were done using ``` seaborn ``` and ``` matplotlib ```. For regression I used ``` sklearn ```, ``` pandas ``` and ``` numpy ```.

For more detailed visualizations and exploratory analysis refer to ``` workbook ```. 
---

###  Select Observations/Findings and Conclusions
---
![gluce](https://user-images.githubusercontent.com/44031998/94872152-d938bd80-0419-11eb-90d1-8cd064189526.png)
- This pair plot shows relation to glucose level, an important factor to diabetes. You can clearly see the difference between outcomes.

![insulin](https://user-images.githubusercontent.com/44031998/94872157-db9b1780-0419-11eb-91b8-6cbf42d2fb37.png)
- Similiar results for insulin levels. Note: insulin values were among most of the missing values. Imputation will make our models more biased but numbers were imputed keeping the original distributions in mind. 

![target_count](https://user-images.githubusercontent.com/44031998/94872165-e190f880-0419-11eb-8f37-449ce44ad986.png)
- Target variable- diabetes

![rfgs_coefs](https://user-images.githubusercontent.com/44031998/94872161-e05fcb80-0419-11eb-86fb-57d33ace39a3.png)
- The best model and its coefficients

![image](https://user-images.githubusercontent.com/44031998/94873050-2ddd3800-041c-11eb-83c4-e5c66cd48b39.png)
- Parameters for the Random Forest

###  Recommendations 
---
- Diabetes is one of the world’s leading contributors to heart disease, the leading cause of death in the world. Yet, medicine does not exactly know the relationship between diabetes and heart disease. Under-represented groups suffer from these diseases even worse
- High sugar levels and high insulin will predict diabetes especially when interacted with BMI and age

## Links 
- Google Slides Presentation: https://tinyurl.com/y5xz89dj

- Data: https://www.kaggle.com/uciml/pima-indians-diabetes-database
