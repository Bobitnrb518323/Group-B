# Health Centre Management System

## Overview
The Health Centre Management System is a software application designed to manage the operations of a local health centre. It allows for the registration of patients, booking and cancelling appointments, managing doctors, and recording appointment outcomes and prescriptions. The system aims to streamline the workflow of health centre staff and improve patient experience. 

## Features
- **Patient Registration**: Receptionists can register new patients and assign them unique patient numbers.
- **Appointment Management**: Patients can book, cancel, and check in for appointments with their registered doctors or any available doctor.
- **Doctor Management**: The system allows for the addition and removal of doctors.
- **Prescription Management**: Doctors can record outcomes of appointments and issue prescriptions.
- **Patient De-registration**: Patients who leave the area can be de-registered by receptionists.

## Data Structures
The system uses the following data structures:
- **Patient**: Contains patient details such as name, date of birth, address, patient number, registered doctor as well as a list of appointments.
- **Appointment**: Contains appointment details such as appointment ID, date and time, doctor, status, and a list of prescriptions.
- **Doctor**: Contains doctor details such as name and a list of appointments.
- **Receptionist**: Contains receptionist details such as name.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/health-centre-management-system.git
   cd health-centre-management-system
