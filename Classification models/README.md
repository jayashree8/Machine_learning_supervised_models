# The classification models worked on are:

## 1) Advertising Dataset

#### The attributes are:

    1) Daily Time Spent on Site
    
    2) Age
    
    3) Area Income
    
    4) Daily Internet Usage
    
    5) Ad Topic Line
    
    6) City
    
    7) Male
    
    8) Country
    
    9) Timestamp
    
    10) Clicked on Ad
    
#### The classification algorithm applied are:

    1) Logistic Regression
    
    2) KNN
    
    3) SVM
    
See notebook [here]()

## 2) Diabetes Dataset

#### The attributes are:

    1) Pregnancies                 
    2) Glucose                     
    3) BloodPressure               
    4) SkinThickness               
    5) Insulin                     
    6) BMI                        
    7) DiabetesPedigreeFunction    
    8) Age                         
    9) Outcome   
    
#### The classification algorithm applied are:

    1) KNN
    
See notebook [here]()

## 3) Heart disease Dataset

#### This is a classifier model to predict if a person has heart disease or no. The datasets are cleveland.csv, hungarian.csv, switzerland.csv and long-beach-va.csv obtained from the UCI Machine Learning Repository. These datasets were merged to one. Each dataset contained 76 attributes but only 14 (including the target feature) were used in these analyses.

#### Attribute Information:
   
      -- 1. age: age in years    
      -- 2. sex: (1 = male; 0 = female) 
      -- 3. cp: chest pain type
        -- Value 1: typical angina
        -- Value 2: atypical angina
        -- Value 3: non-anginal pain
        -- Value 4: asymptomatic
      
      -- 4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)

      -- 5. chol: serum cholestoral in mg/dl     
      -- 6. fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)     
      -- 7. restecg: resting electrocardiographic results
        -- Value 0: normal
        -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
        -- Value 2: showing probable or definite left ventricular hypertrophy

      -- 8. thalach: maximum heart rate achieved
      -- 9. exang: exercise induced angina (1 = yes; 0 = no)    
      -- 10. oldpeak: ST depression induced by exercise relative to rest   
      -- 11. slope: the slope of the peak exercise ST segment
        -- Value 1: upsloping
        -- Value 2: flat
        -- Value 3: downsloping

      -- 12. ca: number of major vessels (0-3) colored by flourosopy        
      -- 13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect      
      -- 14. num: diagnosis of heart disease (angiographic disease status)
        -- Value 0: < 50% diameter narrowing
        -- Value 1: > 50% diameter narrowing
      (the predicted attribute)
    
#### The classification algorithm applied are:

    1) KNN
    
See notebook [here]()

## 4) Iris Dataset

#### The attributes are:

    1) sepal_length
    
    2) sepal_width
    
    3) petal_length
    
    4) petal_width
    
    5) species 
    
#### The classification algorithm applied are:

    1) KNN
    
    2) SVM
    
See notebook for KNN [here]()

See notebook for SVM [here]()

## 5) Kyphosis Dataset

#### The attributes are:

    1) Kyphosis
    
    2) Age
    
    3) Number
    
    4) Start
    
#### The classification algorithm applied are:

    1) Decision tree
    
See notebook [here]()

## 6) Loan Dataset

#### Here are what the columns represent:

* credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
* purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
* int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.
* installment: The monthly installments owed by the borrower if the loan is funded.
* log.annual.inc: The natural log of the self-reported annual income of the borrower.
* dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
* revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
* inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
    
#### The classification algorithm applied are:

    1) Decision tree
    
    2) Random forest
    
See notebook for decision tree [here]()

See notebook for random forest [here]()

## 7) Titanic Dataset

#### The attritubes are:

    1) Pclass-Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)

    2) survival-Survival (0 = No; 1 = Yes)

    3) name-Name

    4) sex-Sex

    5) age-Age

    6) sibsp-Number of Siblings/Spouses Aboard

    7) parch-Number of Parents/Children Aboard

    8) ticket-Ticket Number

    9) fare-Passenger Fare (British pound)

    10) cabin-Cabin

    11) embarked-Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
    
#### The classification algorithm applied are:

    1) Logistic Regression
    
See notebook [here]()