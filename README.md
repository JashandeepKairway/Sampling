# Sampling Assignment :

## Download the Dataset

The dataset is fetched from Creditcard_data.csv

## Data Preprocessing

- The dataset is converted into a balanced class dataset.  
- The target variable is balanced to avoid bias in the models.  

## Sampling Techniques Applied

Five different sampling techniques are used to create variations of the dataset:

1. **Sampling1:** Random sampling  
2. **Sampling2:** Stratified sampling  
3. **Sampling3:** Systematic sampling  
4. **Sampling4:** Cluster sampling  
5. **Sampling5:** Reservoir sampling  

## Machine Learning Models

The following models are trained and evaluated:

- **M1:** Gradient Boosting Classifier
- **M2:** K-Nearest Neighbors (KNN)
- **M3:** Logistic Regression   
- **M4:** Random Forest
- **M5:** SVC 

## Performance Evaluation

- **Accuracy** is used to measure model performance.  
- The best sampling technique for each model is determined.

## Accuracy Results Table:

| Model                | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|---------------------|-----------|-----------|-----------|-----------|-----------|
| Gradient Boosting    | 0.993447  | 0.995902  | 0.967319  | 0.982946  | 0.966063  |
| K-Nearest Neighbors  | 0.851902  | 0.845902  | 0.702591  | 0.803414  | 0.768319  |
| Logistic Regression | 0.927267  | 0.922951  | 0.878953  | 0.905667  | 0.862098  |
| Random Forest       | 0.996068  | 0.995082  | 0.993443  | 0.993438  | 0.984347  |
| SVC                 | 0.675583  | 0.674590  | 0.656954  | 0.666968  | 0.645865  |
