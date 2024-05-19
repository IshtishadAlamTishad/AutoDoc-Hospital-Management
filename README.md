# AutoDoc-Hospital-Management


## Prerequisites

## Introduction 

Revolutionizing Hospital Management System with C# and DBMS Integration. Our innovative solution not only empowers patients to effortlessly purchase medicine, items and access detailed reports but also facilitates secure, encrypted chat for seamless collaboration among users, ensuring efficient communication even within medical rooms. Admin oversight guarantees data integrity, while doctors deliver personalized care. Nurses and staff provide essential support, ensuring operational excellence. This efficient application represents a significant advancement in healthcare technology, streamlining processes and enhancing patient care.


## User Stories
This hospital management system, developed using C#, supports an Admin and four other user roles: Doctor, Patient, Staff, and Nurse. The Admin has comprehensive control over user information, including the ability to add and remove users, manage inventory (medicines and health kits), view and delete patient report times, manage room availability, check patient reports, manage emergency rooms, and securely change passwords. Patients can securely log in, search for doctors, make appointments, purchase prescribed medicines, view report history, and communicate with other users via the chat panel. Doctors can manage appointments, write patient reports, manage medicine lists, and communicate through the chat panel. Staff can manage inventory, access patient schedules, and use the chat panel for communication. Nurses can check room availability, view duty schedules, manage patient medicines, and use the chat panel. The system prioritizes robust security measures and an intuitive interface, ensuring a user-friendly experience that empowers Admin and staff to efficiently manage information. New users must sign up before logging in.

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
The system validates credentials and allows access upon correct input. 
Incorrect entries prompt error messages for wrong user ID or password.

![login](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/b645049c-7c09-4565-8063-6abf2eba311a)

## Signup:
Every user needs to register his/her data through Signup panel otherwise the user cannot login. 
Signup panel Consist of Picture, Name, Password, Date of birth, gender, type (Type of user). 
The system generate ID for user and for balance and salary initially it will be zero because it can only control by Admin.

![signup](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/0636b91e-78aa-4d06-832f-74e68ffeb8a7)

# ...................................................................................................................................

# User : Admin 

### Admin Main Form

![a1](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/b1e9d3dd-fb4b-480e-9969-a53e815aa75b)

![a4](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/f8b5a76e-2d2d-48c5-a3fa-37afc275137a)

![a2](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/20498ebc-541c-4197-9ed8-74029a68fe2c)

![a3](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/1ca64da5-67ca-4f31-bc17-0b0b81fbd0c0)

![a5](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/8fb40ab5-fa1e-4e8f-acb4-5da67d79663c)

![a6](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/2faf49e7-013b-4d25-8f20-b06fffba85c9)


![a7](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/46a33265-186e-4d0c-85d4-f4b7f4c7efb5)

# ...................................................................................................................................

# User : Doctor

### Doctor Main Form

![d1](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/22971e5d-c65d-4140-b7f5-55eae6edfde5)


![d2](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/db8c1406-6a94-4f6f-b514-80d3c9131df9)


![d3](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/7a734f91-c015-4b1b-a567-de23bfddfc76)


![d4](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/3ee109ef-7c14-4782-b86f-eb167be5f248)


![d5](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/d5ef5acd-38e2-4d1a-8838-634c76a9ef6a)

# ...................................................................................................................................
# User : Patient

### Patient Main Form

![p1](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/fcdd3fd1-6bf6-4afa-b71f-6d94862e8cdf)


![p2](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/5d6084c7-a53a-488f-86c6-53d9d6ba7717)


![p3](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/7cddb976-06d6-4058-a4ef-57515977938b)


![p4](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/4535c2a5-1067-4229-8ea2-cc4cf158c600)


![p5](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/04b0ec3c-334c-4cf9-aefc-bcfe6842e0dd)


![p6](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/559dc2ee-d0e6-4c90-9e7a-2c3056137a17)

# ...................................................................................................................................

# User : Stuff : 

### Stuff Main Form

![s1](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/272c4086-7912-4dba-86bf-27a40f025e50)


![s2](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/74abb415-0694-435e-a381-2bcaf60a7398)


![s3](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/bc988b88-ee39-4f4e-8df6-adad6ef7fa7f)


![s4](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/16976098-188e-4af1-8c23-066d167dd22c)


![s5](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/7078f18d-ed1f-49d9-aefe-bf5dc75e1a66)


![s6](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/f58e4c14-e253-4d23-bfbe-d8b7d3c04a2d)

# ...................................................................................................................................

# User : Nurse :

### Nurse Main Form

![n1](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/a4a7922d-de13-4e10-9102-4b4a08bbb3c9)


![n2](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/ec36cc3d-f51b-4dc9-9763-f00faa5362df)


![n3](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/0943ac6a-9a55-4142-8ef5-c778ae20bc6e)


![n4](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/acf88f5b-1d1f-48a2-bb8e-5fdb4b718d05)


![n5](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/ab5209b4-a200-4b5c-9a25-263ffab80e57)

# ...................................................................................................................................

# ER Diagram
![image](https://github.com/IshtishadAlamTishad/AutoDoc-Hospital-Management/assets/96460346/6b94e409-baf8-4e76-aaba-a756a1956470)

# ...................................................................................................................................


# Conclusion 
In summary, this C#-based hospital management system caters to Admin, Doctor, Patient, Staff, and Nurse roles, offering comprehensive control over user information, appointment scheduling, inventory management, and secure communication channels. Through robust security measures and an intuitive interface, the system ensures efficient operations, facilitating enhanced patient care and streamlined administrative processes. It stands as a testament to technological innovation in healthcare management, empowering users to deliver quality care within a secure and user-friendly framework.





