# AutoDoc-Hospital-Management


## Prerequisites

## Introduction 

Revolutionizing Hospital Management System with C# and DBMS Integration. Our innovative solution not only empowers patients to effortlessly purchase medicine, items and access detailed reports but also facilitates secure, encrypted chat for seamless collaboration among users, ensuring efficient communication even within medical rooms. Admin oversight guarantees data integrity, while doctors deliver personalized care. Nurses and staff provide essential support, ensuring operational excellence. This efficient application represents a significant advancement in healthcare technology, streamlining processes and enhancing patient care.


## User Stories
The system validates credentials and allows access upon correct input. 
Incorrect entries prompt error messages for wrong user ID or password.This hospital management system, developed using C#, supports an Admin and four other user roles: Doctor, Patient, Staff, and Nurse. The Admin has comprehensive control over user information, including the ability to add and remove users, manage inventory (medicines and health kits), view and delete patient report times, manage room availability, check patient reports, manage emergency rooms, and securely change passwords. Patients can securely log in, search for doctors, make appointments, purchase prescribed medicines, view report history, and communicate with other users via the chat panel. Doctors can manage appointments, write patient reports, manage medicine lists, and communicate through the chat panel. Staff can manage inventory, access patient schedules, and use the chat panel for communication. Nurses can check room availability, view duty schedules, manage patient medicines, and use the chat panel. The system prioritizes robust security measures and an intuitive interface, ensuring a user-friendly experience that empowers Admin and staff to efficiently manage information. New users must sign up before logging in.

## Structure

### Dashboard:
Admin, Doctor, Patient, Staff, and Nurse can view their own details.

### Menu:
### Manage Inventory:
Admin, Staff:
Medicines: View, Insert, Update, Delete
Health Kits: View, Insert, Update, Delete

### Chat Panel:
Admin:
Communicate with patients, doctors, staff, and nurses.
Doctor:
Communicate with patients, staff, and admin.
Patient:
Communicate with admin, doctor, staff, nurse.
Nurse:
Communicate with admin, patient, doctor, staff.

### User Management:
Admin:
Manage user details (ID, name, password, Date of Birth, gender, type, picture, salary, balance)
Insert, update, delete users
Set initial balance and salary to zero on signup
Search users by unique ID

### Appointments:
Doctor:
View appointment list with details.
Patient:
Make appointments and search for doctors.
Staff:
Access patient schedule for coordination.

### Schedule:
Admin:
View and delete patient report times and details.
Nurse:
View duty schedule.

### Control Rooms:
Admin:
Insert, update, delete rooms
Search room types (e.g., ICU)
Nurse:
Check room availability and type.

### Medicine Management:
Admin, Doctor, Staff, Nurse:
View patient medicines list to ensure optimal patient care and safety.

### Reports:
Doctor:
Write and document patient information and treatment plans.
Admin:
Check patient reports and delete as needed.

### Miscellaneous (Admin):
Check patient reports
Manage emergency rooms
Manage medicines
Change password securely

### Buy Medicine:
Patient:
Purchase prescribed medicines.

### History:
Patient:
View report history.

### Terms & Conditions:
Available on all user panels to ensure compliance with hospital management system rules.
# ...................................................................................................................................

# View Forms

### Login Functionality
Admin can securely log in using a unique Admin ID and password. 


# ...................................................................................................................................

# ER Diagram
![image](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/6b94e409-baf8-4e76-aaba-a756a1956470)

# ...................................................................................................................................


# Conclusion 
In summary, this C#-based hospital management system caters to Admin, Doctor, Patient, Staff, and Nurse roles, offering comprehensive control over user information, appointment scheduling, inventory management, and secure communication channels. Through robust security measures and an intuitive interface, the system ensures efficient operations, facilitating enhanced patient care and streamlined administrative processes. It stands as a testament to technological innovation in healthcare management, empowering users to deliver quality care within a secure and user-friendly framework.





