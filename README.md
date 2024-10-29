# Classifying Readmission and Non-Readmission Events Among  Diebetic Patients 
A simple classification analysis of readmission and non-readmission events among diabetes patients using supervised machine learning techniques in Python. This project was a graded coursework for [MSDS 599](https://catalog.usfca.edu/preview_course_nopop.php?catoid=22&coid=234730) .

## Background 
Readmission rates for diabetic patients  vary between  4.4 and 22.7% which is higher than the rate for all hospitalized patients which ranges between 8.5–13.5% according to
[Ostling et al.](https://pubmed.ncbi.nlm.nih.gov/28702257/)





High readmission rates not only translate to increased healthcare costs but can also lead to fines and penalties from CMS ( Centers for Medicare and Medicaid Services) if readmission rates are deemed “excessive”. Therefore, specifying a model that can accurately identify diabetic patients with the highest likelihood of being readmitted might be impactful in reducing the readmission rates among diabetic patients. 

## Data Source and Introduction  
This diabetes dataset includes 10 years (1999–2008) of clinical care at 130 hospitals and integrated delivery networks throughout the United States: Midwest (18 hospitals), Northeast (58), South (28), and West (16).
The database consists of 41 tables and 117 features. The database includes 74,036,643 unique encounters (visits) that correspond to 17,880,231 unique patients and 2,889,571 providers. The dataset includes inpatient and outpatient data, including emergency department, for the same group of patients. However, data from out-of-network providers is not captured.

Information was extracted from the database for encounters that satisfied the following criteria:
It was an inpatient encounter (a hospital admission).
It was a “diabetic” encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
The length of stay was at least 1 day and at most 14 days.
Laboratory tests were performed during the encounter.
Medications were administered during the encounter.

These criteria were applied to remove admissions for procedures and so forth, which were of less than 23 hours of duration and in which changes in diabetes management were less likely to have occurred.
A dataset with 101,766 encounters was created after applying the above criteria.

Source: https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008
 
## Project Status 
**Completed**  As noted in the Limitation section of this project, some features can be cleaned and reintegrated to our model to see if the f1 scores of the  models will improve. A preliminary literature review can also be conducted to investigate other factors that might be relevant to our inquiry.A literature review was not required to do this project but ideally should be done prior to EDA. 


  

