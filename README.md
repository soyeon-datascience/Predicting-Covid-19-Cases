## Goal
The purpose of this project is to predict whether or not a patient has COVID-19 based on medical data provided by Hospital Israelita Albert Einstein (HIAE). This prediction will better inform the HIAE as to which patients should be administered COVID-19 tests, in an effort to conserve this limited resource.

## Background
The World Health Organization (WHO) characterized the COVID-19, caused by the SARS-CoV-2, as a pandemic on March 11, while the exponential increase in the number of cases was risking to overwhelm health systems around the world with a demand for ICU beds far above the existing capacity, with regions of Italy being prominent examples.
Brazil recorded the first case of SARS-CoV-2 on February 26, and the virus transmission evolved from imported cases only, to local and finally community transmission very rapidly, with the federal government declaring nationwide community transmission on March 20.
Until March 27, the state of São Paulo had recorded 1,223 confirmed cases of COVID-19, with 68 related deaths, while the county of São Paulo, with a population of approximately 12 million people and where Hospital Israelita Albert Einstein is located, had 477 confirmed cases and 30 associated death, as of March 23. Both the state and the county of São Paulo decided to establish quarantine and social distancing measures, that will be enforced at least until early April, in an effort to slow the virus spread.
One of the motivations for this challenge is the fact that in the context of an overwhelmed health system with the possible limitation to perform tests for the detection of SARS-CoV-2, testing every case would be impractical and tests results could be delayed even if only a target subpopulation would be tested.

## Data
The data is supplied by Hospital Israelita Albert Einstein (HIAE) from their Kaggle competition The dataset is available [here](https://www.kaggle.com/einsteindata4u/covid19/version/7)

## General Approach 
1. Clean and extract relevant data features
2. Address missing and unbalanced data
3. Test various types of prediction models
4. Evaluate final output with best model

## Results
1. A model with high recall rate in predicting whether or not a patient has COVID-19
: We used K-Nearest Neighbors (KNN). The recall rate is 92.8% on validation data.
<img width="1241" alt="Screen Shot 2021-10-20 at 7 53 27 PM" src="https://user-images.githubusercontent.com/92895639/138197144-58b266f9-4184-4b71-a442-c3c722f91ad6.png">

2. The most important features to predict COVID-19
: Here is the list of the most important features. It turned out that age is the most crucial feature to predict COVID-19, other features are related to blood. Frome this result, we realized that blood test is important to predict COVID-19 patients.
<img width="828" alt="Screen Shot 2021-10-20 at 7 54 22 PM" src="https://user-images.githubusercontent.com/92895639/138197253-ab4bb3e4-3163-464a-937d-cb6b9779df7f.png">

## Values
1. Faster prediction of COVID-19 patients
2. Less waste of COVID-19 tests
3. More efficient preparation of patient care (beds, medicine, etc)

## Contributors
Soyeon Park, M.S. in Data Science Candidate  
Vanderbilt University  
soyeon.park@Vanderbilt.Edu  

Logan King, M.S. in Data Science Candidate  
Vanderbilt University  
logan.a.king@Vanderbilt.Edu  
  
Myranda Uselton, M.S. in Data Science Candidate  
Vanderbilt University  
myranda.uselton@Vanderbilt.Edu  
  
Wenqi Lyu, M.S. in Data Science Candidate  
Vanderbilt University  
lyu.wenqi@Vanderbilt.Edu  
  
Xin Li, M.S. in Data Science Candidate  
Vanderbilt University  
xin.li@Vanderbilt.Edu  
