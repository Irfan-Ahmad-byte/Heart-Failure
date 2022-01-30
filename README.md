# Data Science with Heart Disease Data Set
### **Science;** 
*Seeking knowledge through insight and resources, and then applying that knowledge for personal interest.*

### **Scientist;** 
*The person who does science.*

### **How does science work?**
*The scientist gains information, builds theories, tests them to prove until a right idea emerges, and then applies that for gains of interest. aka Scientific Method*

### **Data Science;** 
*For the sake of a particular interest(i.e gaining profit), using data to get insights, building theories based on the insight, proving those theories, and then applying them.*

> **Throughout this notebook I'll try to go through all the stages that are the base of science i.e The Scientific Method**


### **The Scientific Method:** 
*The Scientific Method includes:*
- Defining problem to be solved/ interest to be gained/ Question to be answered
- Getting data
- Making observations/getting insight from data
- Build Theories bases on observations
- Experimenting/Testing the Theories
- Applying proved theories
- Determine Solution

## The Procedures I'm Going to Follow

### **1- Determine the Scientific Problem/ Question to be answered/ The Gain I want**
Determine the problem that is to be solved or question that is to be answered or an interest that is to be gained.

### **2- Get Data**
Get the related data through any source i.e web scraping, documents, data bases, charts, web sources, records etc.

### **3- Make Observations**
- clean data
- keep required data and discard unnecessary
- use different techniques 
    - statistics
    - mathematics
    - visualizations etc, 
    
    to get insight from data

#### **Observations**
***High Cholesterol, +ve Diabetes, Heart Patients (DCD/Disease Cholesterol Diabetes)***
- **all** of heart patients with higher cholesterol, +ve diabetes are of **age 55-75**
- **75%** DCD category patients have **Abnormal Heart Rate**
- **21%** have **0 Oldpeak**
- **79%** have **Oldpeak > 0**
- **83%** have **Flat ST_Slope**

- ***Out of 79% DCD High Oldpeak patients, 75% have abnormal Heart Rate***

- ***Out of 21% DCD 0 Oldpeak patients, 76% have abnormal heart rate***

- ***DCD with Oldpeak > 0, Abnormal Heart Rate (DCDGPAH/DCD+greater peak, abnormal heart-rate)***
  Out of 75% abnormal heart rate patients from high oldpeak DCD patients;
  - **79%** have **Flat Slope**
  - **15%** have **Down Slope**

- ***DCDGP+Normal Heart-Rate / DCDGPNH***
  Out of 25% normal heart rate patients from high oldpeak DCD patients;
  - **87%** have **Flat Slope**

- ***DCD+0 peak+AH/ DCDZPAH***
  Out of 76% abnormal heart rate 0 oldpeak DCD patients;
  - **85%** have **Flat Slope**

- ***DCDZPNH***
  Out of 24% normal heart rate 0 oldpeak DCD patients;
  - **100%** have **Flat Slope**

> Most of Heart Patients which have high cholesterol, +ve diabetes, have Oldpeak > 0 and 'Flat' ST_Slope

> For DCD type patients, those who have 0 Oldpeak and 'Up/Down' ST_Slope, other factors are also contributing to these features.

> Most of Heart Patients Exist in Age 55-75

***DNCD/ Diseased, normal cholesterol, +ve diabetese***
- **most** patients are b/w **50-70 of Age**, **below 40** also exist
- **21%** have **0 Oldpeak**
- **79%** have **Oldpeak > 0**
- **69%** have **Abnormal Heart Rate**
- **61%** have **Flat ST_Slope**
- **26%** have **Up Slope**
- **13%** have **Down Slope**

- ***Out of 79% High Oldpeak DNCD patients, 65% have Abnormal heart Rate***

- ***Out of 21% 0 Oldpeak DNCD patients, 58% have  abnormal heart rate***

- ***DNCD with Oldpeak > 0, Abnormal Heart Rate (DNCDGPAH/DCD+greater peak, abnormal heart-rate)***
  Out of 65% abnormal heart rate patients from high oldpeak DNCD patients;
  - **50%** have **Flat Slope**
  - **30%** have **Down Slope**

- ***DNCDGP+Normal Heart-Rate / DNCDGPNH***
  Out of 35% normal heart rate patients from high oldpeak DNCD patients;
  - **50%** have **Flat Slope**
  - **30%** have **Down Slope**

- ***DNCD+0 peak+AH/ DNCDZPAH***
  Out of 58% abnormal heart rate, 0 oldpeak DNCD patients;
  - **91%** have **Flat Slope**

- ***DNCDZPNH***
  Out of 42% normal heart rate 0 oldpeak DNCD patients;
  - **100%** have **Flat Slope**

- ***100% patients with non Flat Slope, 0 Oldpeak have Abnormal heart rate***

- ***65% patients with non Flat Slope, higher Oldpeak have Abnormal Heart Rate***

> With decreased Cholesterol level, %age of Flat ST_Slope occurance has also dropped in Diabetes patients

### **4- Deduce Theories**
Based on the observations deduce your theory/ies about relationships in data and outcomes.

#### **Deductions**


### **5- Test Theory/ies**
Test your theory/ies to prove what you deduced from the observations.

### **6- Apply**
Once deduced and proved a theory, apply it for the gain of interest, answer your question/s or to find solutions.

# About This Notebook
> In this notebook I'm trying to explore the relationship between different factors and occurance of a heart disease.


### **Data Set Source**
This data set was downloaded from [kaggle](https://www.keggle.com).

I could not locate the exact link again from where I got this data set.

There are other data sets too related to the same problem. But, i'm using this data set because this contains relatively less features, OK for me to start with the ***Scientific Method***.