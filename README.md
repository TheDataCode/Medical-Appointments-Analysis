## MEDICAL APPOINTMENTS ANALYSIS
Analysis on information gathered on medical appointments in Brazil in April,2016.


### SUMMARY
This project focuses on factors that may contribute to patients honouring their appointments.
Prior to the wrangling phase, the dataset contained 110527 rows and 14 columns namely:
PatientId          
AppointmentID     
Gender                 
ScheduledDay  : The day appointments were scheduled    
AppointmentDay       
Age                  
Neighbourhood : where the health facilities were located        
Scholarship           
Hipertension           
Diabetes               
Alcoholism             
Handcap                
SMS_received :whether patients received a notification prior to their appointment date           
No-show  : Did patients show up for appointments or not    

#### NB: The Scholarship column denotes whether a patient is a beneficiary of [BOSNIA FAMILIA](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia) 
It is a social welfare program of the Government of Brazil which provided financial aid to poor Brazilian families.


After data transformation, the dataset contained 110327 rows and 11 columns:

Gender                
Age                     
Neighbourhood           
Scholarship             
Hypertension          
Diabetes                
Alcoholism               
Handicap                 
SMS_received       
Showed_up        
Scheduled_day   
Appointment_day                                                                                                                        

I changed the No-show column to Showed_up for consistency.


#### Insights, conclusions and Limitations of the data can be found in the 'medical_appointment_analysis,pynb' file.
