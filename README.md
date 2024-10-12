# Cardiovascular-Disease-CVD

## Problem Statement

Cardiovascular diseases are the leading cause of death globally. To identify the causes and to develop a system to predict heart attack in an effective manner is necessary. The presented data has all information about all the relevant factors that might have an impact on heart health. The data needs to be explained in detail for any further analysis.

| **Variable** | **Description**                                                                 |
|--------------|---------------------------------------------------------------------------------|
| age          | age in years                                                                    |
| sex          | (1 = male; 0 = female)                                                          |
| cp           | chest pain type                                                                 |
| trestbps     | resting blood pressure (in mm Hg on admission to the hospital)                  |
| chol         | serum cholestoral in mg/dl                                                      |
| fbs          | (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)                        |
| restecg      | resting electrocardiographic results                                            |
| thalach      | maximum heart rate achieved                                                     |
| exang        | exercise induced angina (1 = yes; 0 = no)                                       |
| oldpeak      | ST depression induced by exercise relative to rest                              |
| slope        | the slope of the peak exercise ST segment                                       |
| ca           | number of major vessels (0-3) colored by flourosopy                             |
| thal         | 3 = normal; 6 = fixed defect; 7 = reversible defect                             |
| target       | 1 or 0                                                                          |


### 1.Preliminary analysis:
     
    
   1.Perform preliminary data inspection and report the findings as the structure of the data, missing values, duplicates etc.
  
   2.Based on the findings from the previous question remove duplicates (if any) , treat missing values using appropriate strategy.

### 2.Prepare an informative report about the data explaining distribution of the disease and the related factors. You could use the below approach to achieve the objective
     
     
   1.Get a preliminary statistical summary of the data. Explore the measures of central tendencies and the spread of the data overall.
   
   2.Identify the data variables which might be categorical in nature. Describe and explore these variables using appropriate tools e.g. count plot
   
   3.Study the occurrence of CVD across Age.
   
   4.Study the composition of overall patients w.r.t . Gender.
   
   5.Can we detect heart attack based on anomalies in Resting Blood Pressure of the patient?
   
   6.Describe the relationship between Cholesterol levels and our target variable.
   
   7.What can be concluded about the relationship between peak exercising and occurrence of heart attack.
   
   8.Is thalassemia a major cause of CVD?
   
   9.How are the other factors determining the occurrence of CVD?
   
   10.Use a pair plot to understand the relationship between all the given variables.


### 3.Build a baseline model to predict using a Logistic Regression and explore the results.   
