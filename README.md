# Hospital-Antibiotics-Usage
 An Analysis on Drug Resistance and Antibiotics with MS Excel
## Project Overview
Drug resistance to antibiotics is increasing around the world every day. Generations of antibiotics are dynamically changing in treatment.The dataset focuses on the retrospective study of the usage of antibiotics and diseases and find possible resistance patterns.
## Data sources
The data set was obtained from kaggle.In 2019, a group of medical students in Myanmar, Mandalay researched antibiotics usage in hospitals. The research won first prize at the University of Medicine, Mandalay 3rd MBBS research competition, 2019
The data set contains;•	age and gender of the patient,diagnosis of the patient,Antibiotics used to treat patient,Dosage of the antibiotics in grams,Route of application of antibiotics,Frequency of usage of antibiotics,Duration of treatment using antibiotics in days,Indiction of antibiotics
## Tools used
In this project i utilised Microsft Excel;
Pivot Tables, Charts, Graphs and Formulas
## Understanding the Data
Before any proceudure we had to understand the data first, so that we can ensure the analysis is relevant, accurate and leads to meaningful insights. There are some columns on the data that had been filled using medical terms/abbreveations that could be used understood only medics,So we delved into the and fish out their meanings for easier understanding by everyone.They inlcude;
1.frequency of antibiotics usage
OD-Once a Day
BD-Twice a Day
TDS- Three Times a Day
QID-Four Times a Day

2.IV- Intravenous.This refers to the administration of fluids, medications, or other substances directly into a vein
IM- Intramuscular. It refers to the administration of medication by injection into a muscle. 
Oral- It's commonly used to describe the administration of medications or treatments that are given by mouth, such as pills, capsules, or liquids

## Data preparation and Standardization
In this process we ensured that the data is of consistent and uniform format.This process ensures thata thr data is more reliable, ananylzable and valuable by rsolving inconsistencies and errors.We did the following steps as for data preparation;
 ### 1. Removing Duplicates
 We checked for duplicates and several rows were found and removed leaving only unique values.
 
   <img width="1161" height="310" alt="removing duplicates" src="https://github.com/user-attachments/assets/1ed2c539-cbcc-4ac7-adaa-d06a33ce0d44" />

 ### 2. Checking missing values
 we checked for blanks but found none
   <img width="490" height="219" alt="finding blanks" src="https://github.com/user-attachments/assets/9c9a246f-edf4-469d-9697-4b46a50d986e" />

 ### 3. Data standardization
 
 ### 4. Creating Age Bands
  In this step we added a new column H "Age Bands" using Excel formula IF
  <img width="1215" height="76" alt="age bands" src="https://github.com/user-attachments/assets/2fc22b8f-87aa-4c7b-bfe6-02108a228894" /> 
we then filled the formuala down the column H that we named "Age Bands"
<img width="149" height="440" alt="age bands 2" src="https://github.com/user-attachments/assets/76852e14-7f65-489d-9071-dbac951641a6" />

## Pivot tables
## Analysis
### KPIs

