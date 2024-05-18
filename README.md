# DataMining_Fianl
In the wake of an unprecedented global health crisis, the impact of COVID-19 has been profound, with over one million cases reported in the United States alone (CDC, 2023). The pervasive threat of contracting the virus and its severe consequences underscore the urgent need for a comprehensive understanding of its dynamics. This project aims to delve into the depths of COVID-19 data, employing a meticulous analysis to extract insightful perspectives. The overarching goal is to construct a predictive model that can discern whether a patient is at high risk or not, facilitating enhanced preparedness and patient care. Through this endeavor, the focus will be on identifying the major factors that significantly contribute to placing individuals in the high-risk category, thereby contributing valuable insights to the ongoing battle against the pandemic.


# Prepocessing
**1. Changing DATE_DIE into DIED and a numerical feature**

![picture of me](./images/image1.jpg "Me")
![picture of me](./images/image2.jpg "Me")

![picture of me](./images/image3.jpg "Me") 
![picture of me](./images/image4.jpg "Me")

**2. Checking missing values**
- INTUBED
- PREGNANT
- ICU


![picture of me](./images/image5.jpg "Me")

### Preprocessing - INTUBED ###
**The missing values of (97) are all corresponding with (2) Patients who have never been hospitalized couldn't possibly be connected to the ventilator.**

<!-- ![picture of me](./images/image6.jpg "Me") -->
![picture of me](./images/image7.jpg "Me") 
![picture of me](./images/image8.jpg "Me")

### Preprocessing - PREGNANT ###
**All values of 98 are of the missing values corresponding to the female values. Replace all the corresponding values to the male section (97) with (2); since men can't be pregnant.**

![picture of me](./images/image9.jpg "Me")
![picture of me](./images/image10.jpg "Me")
![picture of me](./images/image11.jpg "Me")

### Preprocessing - ICU ###
**The missing values of (97) are all corresponding to the values of PATIENT_TYPE = 1 Patients who have never been hospitalized couldn't possibly be admitted to the ICU.**

![picture of me](./images/image12.jpg "Me")
![picture of me](./images/image13.jpg "Me")

# Data Analysis

# Feature selection 

# Modeling

# conclusion
