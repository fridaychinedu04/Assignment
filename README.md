# **Analysis of Global Suicide Mortality Rates (2001-2021)**  

---
## **Table of Contents**  
[INTRODUCTION](#Introduction)  
[OBJECTIVES](#Objectives)
[DATA SOURCE](#Data_source)
[KEY FINDINGS](#Key_findings)
[CONCLUSION](#Conclusion) 

---
### **INTRODUCTION**
Suicide is a critical global public health issue, with varying trends across countries and years. This report examines mortality rates from 2001 to 2021 using the *World_suicide* dataset from Kaggle. The dataset contains yearly suicide mortality figures across multiple countries, providing insight into geographical, temporal and pandemic_related patterns. Using Python's **pandas** library, this analysis explores data quality (duplicates, missing values), compares suicide trends among countries, and identifies high-risk periods and regions. The goal is to better understand global suicide patterns and provide a solid basis for further public health analysis.  

---
#### **OBJECTIVES**
This analysis aims to:
1. Determine whether the dataset contains duplicate entries
2. Identify missing values across all variables
3. Determine the year Nigeria recorded its highest suicide mortality rate
4. Count the number of countries present in the dataset
5. Identify the country with the highest suicide mortality rate globally
6. Compare suicide mortality rates between Nigeria and Niger in 2015
7. Determine the country with the highest suicide rate during the COVID-19 year (2020)
8. Identify the highest recorded mortality rate for each country
9. Count the number of countries with suicide mortality rates greater than 20 between 2005 and 2010

---
##### **DATA SOURCE**
This data was downloaded from [Kaggle]().
Columns included: `Country Name`, `Country Code`, `Year`, `Suicide Rate`.

---
###### **KEY FINDINGS**
>- Are there any missing values in the dataset?
    - Yes. There are **1,892 duplicate rows**
>- Are there any missing values in the dataset?
    - No. All columns (`Country Name`, `Country Code`, `Year`, `Suicide Rate`) have **0 missing values**
>- In which year did Nigeria record its highest mortality rate?
    - Nigeria's highest recorded suicide mortality rate in the dataset is **5.37** in **2001**
>- How many countries are in the dataset?
    - The dataset contains **233 unique countries**
>- Which country has the highest suicide mortality rate?
    - **Russian Federation** - Highest recorded rate **51.79** in **2001**
>- Between Nigeria and Niger, which country recorded a higher suicide mortality rate in 2015?
    - The dataset contains a 2015 record for **Nigeria** with a suicide rate of **4.46**. There is **no 2015 record for Niger** in the filtered result (so Nigeria is higher in 2015 between the two, due to available records)
>- Which country recorded the highest suicide rate in the COVID-19 year (2020)?
    - **Suriname** recorded the highest suicide mortality rate in **2020**, with **28.47**.
>- What is the highest mortality rate for each country?
    - Computation of the maximum suicide rate for the **top 20 countries** will be displayed with their respective suicide rates in a table format below
>- How many countries recorded suicide mortality rates greayer than 20 between 2005 and 2010?
    - **23 countries** had at least one year with a suicide mortality rate **>20** during 2005-2010

---
###### **CONCLUSION**
The dataset is complete (no missing values) but contains substantial duplicate rows. Russia shows the highest single suicide mortality rate (51.79 in 2001). Nigeria's peak in the data was modest (5.37 in 2001). During the COVID-19 year of 2020, Suriname had the highest recorded rate (28.47). Between 2005-2010, 23 countries had rates above 20.
The dataset reveals that suicide mortality is a complex global issue shaped by economic, cultural, and health-system factors. Each country follows a unique trajectory, and international comparison shows striking differences. The COVID-19 pandemic year marked significant changes, reinforcing the importance of mental-health interventions during global crises.
Overall, the analysis provides a strong basis for policymakers, researchers, and public-health practitioners to understand where intervention is most urgently needed and which countries or years require deeper investigation.