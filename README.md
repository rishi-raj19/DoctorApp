# DoctorApp

1. Language and Framwork - Java , SpringBoot , JPA , MYSQL database
   
2. Data Flow
   - Controller (API)
     a. AdminController -
     b. AppointmentController) - getAllAppointments()
     c. DoctorController - addDoctor(), getAllDoctor()
     d. PatientController - signUpPatient(), sigInPatient(), sigOutPatient(), getAllPatients(), scheduleAppointment(), cancelAppointment()
   - Service
     a. AdminService -
     b. AppointmentService - getAllAppointments(), saveAppointment(), getAppointmentForPatient(), cancelAppointment()
     c. AuthenticationService - authenticate()
     c. DoctorService - addDoctor(), getAllDoctors()
     d. PatientService - signUpPatient(), getAllPatients(), signInPatient()

3. Model - Admim(), Appointment(), AuthenticationToken(), Doctor(), Patient()
4. Repository - IAdmim(), IAppointment(), IAuthenticationToken(), IDoctor(), IPatient()

5. Data Structure Used - MYSQL as database

6. Project Summary

Practicing mapping, APis, SignIn, and SignUp on Doctor App is part of this assignment. Springboot allows you to create Post and get Post by Id.
