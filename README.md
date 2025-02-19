# HOSPITAL MANAGEMENT

### PROJECT OVERVIEW
The goal of this project is to design and implement a database management system using MySQL to manage key aspects of a healthcare facility. The system will manage information related to patients, doctors, appointments, and medical records. The primary aim is to streamline healthcare operations by ensuring easy scheduling of appointments, tracking patient visits, and maintaining medical records securely. The system will also facilitate efficient management of medical staff.

### FEATURES:
1. Patient Management:
- Add, update, and delete patient records.
- Query patient details by patient ID or name.
  
2. Doctor Management:
- Add, update, and delete doctor details.
- View available doctors based on specialty.

3. Appointment Management:
- Schedule new appointments, reschedule, or cancel appointments.
- View a doctor’s available slots.
- Track the status of appointments (e.g., pending, completed).

4. Medical Records Management:
- Create, update, and view medical records for each patient.
- Link medical records to specific appointments.
- Track history of diagnoses, treatments, and medications.

### TECHNOLOGIES USED
- SQL (MySQL)
- Relational Database Management System (RDBMS)

### QUERIES AND ANALYSIS
The project includes various SQL queries and data analysis tasks to extract valuable insights from the hospital management data. Some of the key queries implemented include:

1. JOIN:
   Fetching a list of all appointments with patient and doctor details.
  
2. VIEW:
   Creating a view to simplify fetching completed appointments with patient and doctor details.
   
4. SUBQUERY:
   Here, the subquery is used to retrive the data of patients who have more than 3 appointments.
   
5. STORED PROCEDURE:
   A stored procedure retrives the count of appointments for a specific doctor.
