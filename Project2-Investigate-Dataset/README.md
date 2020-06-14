## PROJECT TITLE: INVESTIGATE A DATASET

The objective of this project is to show my understanding of the data analysis process using the data "No-show appointments", available here ( [No-show appointments](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv&sa=D&ust=1532469042118000)). 

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.

The subsections in the project are:
	Data Wrangling 
	Exploratory Data Analysis
	Conclusions
	
###### The data contains 14 columns:
    1.PatientID - Unique identification for the patients
    2.AppointmentID - Unique identification for the appointment
    3.Gender - F or M (Female or Male)
    4.ScheduledDay - Day the appointment was schduled
    5.AppointmentDay - Day of the appointment
    6.Age - Age of the patient
    7.Neighbourhood - Location of the hospital
    8.Scholarship - whether or not the patient is enrolled in Brasilian welfare program Bolsa Família
    (9,10,11,12)- ('Hipertension','Diabetes','Alcoholism','Handcap')- Underlining medical condions    for the patients (0 - indicates patients does not have, 1 - patient has)
    13 - SMS Received - If patients received SMS for their appointment
    14 - No-show - indicates if patient showed up or not.

###### Questions explored with the data:
1.	What is the correlation between age and showing up for appointment?
2.	If scheduled date is same as appointment date, does that affect the rate of show up?
3.	Do Patients with Underling health conditions show up more than others without?
4.	Does gender affect the rate of showing up for appointments?
5.	Do Patients with Scholarships show up more than those without?