# Credit Risk Analysis

##Overview of the analysis: 
Explain the purpose of this analysis.
  The purpose of this analysis is to be able to create a machine learning model that can predict if a credit application is high risk or low risk. Since data is mostly skewed to low risk applications we are using different types of samling methods to determine an accurate machine learning method. 

##Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
  - Naive Random Oversampling 

   ![image](https://user-images.githubusercontent.com/90172307/155834514-e687b1a1-2108-44d2-8c8a-786163f136d6.png)

  - SMOTE Oversampling
  ![image](https://user-images.githubusercontent.com/90172307/155834542-cae2a08f-e6ca-486b-afb6-33525952f8f3.png)


  - Undersampling 
  ![image](https://user-images.githubusercontent.com/90172307/155834554-58bc3be9-1074-4403-ae38-c6d30f94b1ac.png)

  
  - SMOTEENN
  ![image](https://user-images.githubusercontent.com/90172307/155834712-43b32f35-7627-42e1-8a17-1e1a9797b7ae.png)


  - Balanced Random Forest Classifier
    ![image](https://user-images.githubusercontent.com/90172307/155834744-6f3b4e9f-d46c-4c7a-bd28-251e2f867555.png)

  - EasyEnsemble
  ![image](https://user-images.githubusercontent.com/90172307/155834755-97337c8e-506a-4da8-b60f-61681bcada90.png)

  

##Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
  Overall the under sampling and over sampling proved to be a less effective method to view the data. While the Easy Ensemble classifier and the RFC classifer had accuracy scores in the 90 percentile. 
