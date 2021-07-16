# Credit_Risk_Analysis

## Project Overview

Assist the lead data scientist who is working in the Fast Lending company to predict credit card risk using several machine learning algorithms. I used the following algorithms to evaluate models and predict credit risk. Then, I evaluated the performance of these models to see how well the models predict data.

 - The oversampling RandomOverSampler and SMOTE algorithms.
 - The undersampling ClusterCentroids algorithm.
 - Combinatorial approach of over-and undersampling models: The SMOTEENN algorithm.
 - Ensemble Classifiers: BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms.


## Rescources

 - Data Source: LoanStats_2019Q1.csv
 - Software: Python 3.8.3, Anaconda Navigator 1.9.6, Jupyter Notebook 6.0.3

## Results

 - ### Naive Random Oversampling
 
 
 ![Naive Random Oversampling](https://user-images.githubusercontent.com/71282697/106302282-9b07ab00-620d-11eb-9d76-0a43fd040c49.png)
 
 
   - The accuracy score is 65%.
   - The overall precision score is 99% and the overall recall score is 57%. The precision score for high-risk loans is 1% that indicates a large number of false positives.
   
 
 - ### SMOTE Oversampling
 
 
 ![SMOTE Oversampling](https://user-images.githubusercontent.com/71282697/106300565-82969100-620b-11eb-84b5-ede1c38e862a.png)
 
   - The accuracy score is 66%.
   - The overall precision score is 99% and the overall recall score is 68%. The precision score for high-risk loans is 1% that indicates a large number of false positives
 
 
 - ### Cluster Centroids Undersampling 
 
 ![Undersampling](https://user-images.githubusercontent.com/71282697/106300905-e456fb00-620b-11eb-9290-cdf98a0b6d9d.png)
 
 
   - The accuracy score is 54%.
   - The overall precision score is 99% and the overall recall score is 42%. The precision score for high-risk loans is 1% that indicates a large number of false positives.
   
   
 - ### SMOTEENN Combination Sampling
 
 
![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/71282697/106301167-3dbf2a00-620c-11eb-8373-4d49d683f8b2.png)

   - The accuracy score is 65%.
   - The overall precision score is 99% and the overall recall score is 57%. The precision score for high-risk loans is 1% that indicates a large number of false positives.
   
   
 - ### Balanced Random Forest Classifier 
 
 ![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/71282697/106301671-d655aa00-620c-11eb-8749-d4eb6a0b43ae.png)
 
 
   - The accuracy score is 79%.
   - The overall precision score is 99% and the overall recall score is 87%. The precision score for high-risk loans is 3% that indicates a large number of false positives.
   
 
 - ### Easy Ensemble AdaBoost Classifier 
 
 ![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/71282697/106302047-49f7b700-620d-11eb-8e2c-d8cb91812bcc.png)
 
 
   - The accuracy score is 93%.
   - The overall precision score is 99% and the overall recall score is 95%. The precision score for high-risk loans is 9% that indicates a large number of false positives.
   
   
## Summary

Based on the performance of these machine learning algorithms, the best model in predicting loan risks would be the model with high accuracy and a good balance of recall and precision score. As the above results show, Easy Ensemble AdaBoost Classifier has the highest accuracy, overall precision, and recall scores. It means this model is more accurate and it has the most true positives. So, I would recommend Easy Ensemble AdaBoost Classifier model to use for predicting high-risk loans.





