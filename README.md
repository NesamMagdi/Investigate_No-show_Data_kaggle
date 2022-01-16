# Investigate_No-show_Data_kaggle
This dataset available in https://www.kaggle.com/joniarroba/noshowappointments
Using Python at Jupyter NoteBook for Udacity Professional Track Project

## Introduction

### Dataset Description 

> This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row. **The following variables are used for the analysis:**
* **ScheduledDay:** tells us on what day the patient set up their appointment.
* **Neighborhood:** indicates the location of the hospital.
* **Scholarship:** indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
* **Noshow:** it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.


### Question(s) for Analysis

> Many factors may predict that a patient will not appear in the hospital on his appointment. **A lot of question could be answered through this dataset:**
* **Q1:** Is there a correlation between chronic diseases like Hypertension, Diabetes, and Alcoholism on the patient's commitment to his appointment?
* **Q2:** Was patients' commitment to the hospital appointment associated with their Demographic Characteristics (Age, Gender, Handicap, and Location of the hospital)?
* **Q3:** Is there an association between receiving SMS before the hospital appointment and and patients' commitment to the hospital appointment?
* **Q4:** Is there an association between patient enrollment in the "Bolsa Familia" Program and patients' commitment to the hospital appointment?


## Conclusions

* Endemic diseases like Hypertension, Diabetes, or Alcoholism are not associated with the commitment of patients to their hospital appointment.
* Female patients are more likely to commit to their appointment.
* Older ages are more committed to their hospital appointment than younger ages.
* Bolsa Familia program has no effect on the follow-up of their health in the hospital.
* Patients without any Handicap are more committed to their hospital appointment.

### Limitations

* A lot of factors must be involved in this data to illustrate the reasons for missing appointments. Some of these factors related to Patient Hospital relationships as the distance between patients and hospital location, if the hospital is clean and quits if there are many different prices on the patients if they appeared in their appointments, and so on. Some factors could be related to the patients' doctor relationships, like involving in their treatment plan if physicians listen and care to them. All these factors must be involved in the data.
* A lot of statistical tests like independent sample t-test, Chi-square, and ANOVA test should be done.
* Regression analysis should predict the actual reasons for missing appointments.
