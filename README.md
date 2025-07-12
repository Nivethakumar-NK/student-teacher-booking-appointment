## Student-Teacher Booking Appointment System (Client-Side Simulation)
## Project Overview
This project is a client-side web application simulating a Student-Teacher Booking Appointment System. It allows administrators to manage teachers and student registrations, teachers to schedule and manage appointments, and students to register, search for teachers, book appointments, and send messages.
## Important Note:
 This is a purely client-side application. All data (teachers, students, appointments, etc.) is stored in the browser's memory and will be lost when the page is refreshed or the browser tab is closed. It serves as a demonstration of the front-end functionality only. For a production-ready system, a persistent backend database (like Firebase, SQL, or MongoDB) would be essential.
## Technologies Used
HTML5: For the structure of the web pages.
CSS3 (Tailwind CSS): For styling and responsive design. Tailwind CSS is loaded via a CDN.
JavaScript (Vanilla JS): For all interactive functionalities and in-memory data management.
## Features
The system is divided into three main modules: Admin, Teacher, and Student.
## Admin Module
Login: Secure login for administrators.
Add Teacher: Add new teacher profiles, including name, department, and subject.
Manage Teachers:
View a list of all registered teachers.
Edit existing teacher details.
Delete teacher profiles (also cancels associated appointments).
Approve Student Registrations: Review and approve student accounts before they can log in.
## Teacher Module
Login: Teachers can log in using their assigned email and password.
Schedule Appointment Slots: Add available time slots for students to book.
View Appointments & Messages:
See all their scheduled slots.
View a list of all appointments booked by students.
Approve or cancel pending appointments.
View messages sent by students regarding appointments.
## Student Module
Register: Students can create new accounts (requires admin approval).
Login: Access the student dashboard after account approval.
Search Teacher: Find teachers based on name, department, or subject.
Book Appointment: Select an available slot from a teacher and specify the purpose of the appointment.
Send Message: Send messages to teachers regarding their booked appointments.
View My Appointments: Track the status of their booked appointments (pending, approved, cancelled) and view messages.
Cancel My Appointment: Students can cancel their own appointments.
## How to Run the Application
Click on DOWNLOAD ZIP.
Extract the ZIP file on your computer.
Open the extracted folder.
Double-click "index.html" or right-click and choose "Open with" Your Browser(e.g.,chrome,firefox).
## Login Credentials
Admin:
Username: admin
Password: password
Teacher:
Teacher 1- email(dr.emilywhite@example.com) 
Teacher 2- email(davidlee@example.com)
Teacher 3- email(sarahchen@example.com)
Password: password123 (This is a hardcoded default for all added teachers).
Student:
Go to the Student Panel.
Use the "Student Register / Login" section to Register a new student (e.g., Name: Bob Smith, Email: bob@example.com, Password: studentpass).
Log in as Admin.
Go to the "Approve Student Registrations" section in the Admin Panel and click "Approve" next to the registered student's name.
Once approved, switch back to the Student Panel and use the registered email (bob@example.com) and password (studentpass) to Login.
## Limitations
No Data Persistence: Data is lost upon page refresh or closing the browser.
Simplified Security: Authentication and data handling are basic and not suitable for real-world production use.
Client-Side Only: No server-side logic or database integration.
No Real-time Sync: Changes made by one user role are only reflected in another user role's view after a relevant action triggers a re-render (e.g., an admin approving a student will update the admin's view, but the student needs to try logging in again to see the effect).
This project provides a foundational understanding of building a multi-role web application's front-end interaction.
