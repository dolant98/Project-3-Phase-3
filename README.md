# Project-3-Phase-3

### Substance Use Treatment Analysis
#### Key Determinants of Treatment Outcomes

## Overview
According the National Survey on Drug Use and Health (NSDUH), over 20 million people in the United States over the age of 12 had a substance use disorder 
(SUD)*. This is pre-pandemic and doesn't account for any increase due to the stressors of the past two years.  Effective SUD treatment not only addresses 
the substance use itself, but also socio economic factors which contribute to the SUD. 

*Substance Abuse and Mental Health Services Administration: Substance Use Disorders Recovery with a
Focus on Employment and Education. HHS Publication No. PEP21-PL-Guide-6 Rockville, MD: National
Mental Health and Substance Use Policy Laboratory. Substance Abuse and Mental Health Services
Administration, 2021.*

## Business Case

**Stakeholder:** Substance use treatment organization with locations providing group-based and care navigator supported programs throught the country.

**Situation:** Tailor care model to focus on the most critical factors for treatment completion.  Care navigator resources are limited.  As a result, their 
their activities should be directed to the areas which will have the greatest impact on a successful outcome. 

**Objective:** Identify the top 3 contributing factors impacting treatment completion so that the organization can tailor programs accordingly. 

## Data

- Data Source
  - Substance Abuse and Mental Health Services Administration (SAMHSA)
  - Treatment Episode Data - Discharges - 2019
  - Outpatient Therapy, Age GT 18
  - N =  736,562

## Analysis 
 
- **Logistic Regression**
  - Target Variable = Treatment Completed (No (0)/ Yes (1))
  - 75 Features encompassing each of the categories below:
    - Social
    - Behavioral
    - Clinical
    - Demographic 

<img width="799" alt="Screen Shot 2022-07-15 at 6 42 19 PM" src="https://user-images.githubusercontent.com/100314469/179321055-3aa7f3e7-703a-416b-ae91-b58b3482de34.png">

- **Feature Importance**

<img width="796" alt="Screen Shot 2022-07-15 at 6 45 35 PM" src="https://user-images.githubusercontent.com/100314469/179321330-0ec0702b-1eee-4a20-bd3e-6a67f4b4ebe8.png">

  **Region**
  <img width="600" alt="Screen Shot 2022-07-26 at 3 06 18 PM" src="https://user-images.githubusercontent.com/100314469/181091547-93a56a0e-04e8-43db-94b6-9533b0fa5bcb.png">

  **Substance**
  <img width="746" alt="Screen Shot 2022-07-26 at 3 09 14 PM" src="https://user-images.githubusercontent.com/100314469/181091780-9a0006ed-1e44-42cc-b125-24d688b0eb66.png">

  **Employment**
  <img width="743" alt="Screen Shot 2022-07-26 at 3 09 31 PM" src="https://user-images.githubusercontent.com/100314469/181091858-f8bc87ba-d929-4ee0-9d52-6761c3d228ec.png">

  - The key features with the greatest impact on treatment completion include: 
    -  **Region** - The West Coast has a higher completion rate - this requires more research into the population as well as treatment protocols
    -  **Substance** - Members whose primary substance is heroin and opiates have a lower completion rate
    -  **Employment** - Members who are able to find full-time employment have a higher completion rate than those who are unemployed
   
