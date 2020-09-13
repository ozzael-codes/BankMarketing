# Bank Marketing prediction model :bank:
### The main objective of this project is to adopt a data driven approach for analyzing bank loan data and upscaling bank telemarketing. 

## Project Definition
### Predict if a client will subscribe (yes/no) to a term deposit — *defined as a classification problem.*

## About the dataset :shipit:
### There's a mix of categorical and numerical columns in the data so the data has been split accordingly. (usage of one hot encoding for categorical features) 
### Heres a link to the dataset that's being used in this project. [http://archive.ics.uci.edu/ml/datasets/Bank+Marketing]
### The data that is used in this project originally comes from the UCI machine learning repository.This dataset is related contains about 40,000 direct marketing campaigns of a Portuguese banking institution from May 2008 to November 2010. The marketing campaigns were based on phone calls and more than one contact to the same client was required, in order to assess if the customer would open a term deposit in the bank or not. 

### Dataset
#### Input variables: 
      * age (numeric)
      * job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-         employed','services','student','technician','unemployed','unknown')
      * marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
      * education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')
      * default: has credit in default? (categorical: 'no','yes','unknown')
      * housing: has housing loan? (categorical: 'no','yes','unknown')
      * loan: has personal loan? (categorical: 'no','yes','unknown')

#### Related with the last contact of the current campaign:
      * contact: contact communication type (categorical: 'cellular','telephone')
      * month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
      * day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
      * duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

#### Output variable (desired target):
    * y - has the client subscribed a term deposit? (binary: 'yes','no')

Source:https://archive.ics.uci.edu/ml/machine-learning-databases/00222/

This dataset has about 40,000+ rows of data.


## Notebook walkthrough :notebook:
### - Data exploration and understanding using visualizations (matplotlib, seaborn)
### - Feature Engineering : classifying features such as numerial and categorical into groups in order to analyze the data for results in machine learning algorithms
### - Gradient boosting algorithm model prediction (scikit-learn)
### - Model performance evaluation

## Future improvements :soon:
- Testing out with different predictive models and comparing model metrics
- Correlation map for numerical features within the dataset
