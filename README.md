# Sepsis-Coagulopathy
Assessment & Prediction of Mortality in ICU Patients with Sepsis Coagulopathy

## What and Why 
Multiple approaches exist to predict mortality in the ICU. This approach takes computes risk of mortality and likelihood of bleding for patients with Sepsis Coagulopathy.
It generates the working framwork for an app deisgned to predict the morbidity and mortality.
Coagulation abnormality is found in sepsis patients. Bleeding-related complications are also common. Study hypothesis involving whether or not to be aggressive in correcting high INR is a consistent bedside question. Identify ICU patients with sepsis who are at higher risk and quantify a relationship between sepsis coagulopathy, hemorrhage and mortality

## Input
input: Team Lead, 3 person cross-functional project team, Mimic iv ICU dataset( https://mimic.mit.edu/iv/ ), deidentified longitudinal, cross sectional EHR data: 53,423 critical care admissions, 26 tables, 324 variables Charted Events, laboratory measurements (LOINC), over 2 million rows of unstructured data (provider notes) coded with SNOMED CT, ICD-9, ICD-10 and LOINC codes.

## Algorithm
Algorithm: R, SQL, Data extraction, inclusion/exclusion criteria, exploratory analysis, logistic regression, random forest decision tree modeling, correlation matrix

## Output
Relationship between INR levels & bleeding, mortality. Identify high risk ICU patients with sepsis.
Mortality risk score for decision support tool. 
Decision tree bedside tool
Regression model: Predict mortality, hemorrhage with INR levels.Predicts likelihood of sepsis-induced coagulopathy




