# Student-Attendance-Database
##  📄 Project Overwiew
**Student-Attendance-Database** is a simple and smart database which primary goal is to log and to manage data collected for colleting student attendance. This database can be used and will be used in future for another project(For Embedded Systems-RFID Smart Attendance System), which will then help us acomplish merging two different projects into one.(This is still under development). The primary objective of the Smart Attendance System is to automate and streamline the process of recording, tracking, and analyzing student attendance at the International University of Sarajevo (IUS). The system aims to replace traditional manual or semi-automated methods (e.g., paper-based or Excel tracking) with a smart, centralized, and secure database-driven approach.

## 👨‍💻 Authors

This project was collaboratively developed by:

- **Aldin Ćimić**
- **Samir Laličić**
- **Bekir Ćorić**
## 🚀 Goals
  -  Accurately record attendance using a digital interface (RFID, biometric, or manual login).
  -  Reduce errors and manipulation in attendance records.
  -  Provide real-time access to attendance reports for students, professors, and administrators.
  -  Ensure data integrity and security through a well-designed database management system.

## ⚙️ Functional Requirements
| Functional Requirement  |Description|
| ------------- | ------------- |
| **Record Attendance** | Allow instructors or devices to record attendance for a sesssion  |
| **View Attendance**  | Allow students and instructors to view  |
| **Generate Reports** | Monthly/semester attendance reports per student/course |
| **Add/Edit Entries** | Admin can add/edit students, instructors, sessions |
| **Authentication** | Secure login for students, instructors, and admins |
| **Device Integration** | (Optional)(Later on will be required for different project) Support for RFID or biometric devices |

## Non-Functional Requirements
| Non- Functional Requirement  |Description|
| ------------- | ------------- |
| **Performance** | System must handle high load during peak hours(class start times) |
| **Security**  | Only authorized users can access/edit data. All data should be encrypted  |
| **Availability** | 99.9% uptime to ensure system is available during academic hours |
| **Scalability** | Able to support future expansion – more students, departments, devices |
| **Usability** | User-friendly interfaces for different user types |
| **Data Integrity** | Prevent duplicate or inconsistent entries |

## 📊 Data Requirements
| Data Category  |Details|
| ------------- | ------------- |
| **Student data** | ID, name, surname, program, semester, email |
| **Instructor data**  | ID, name, department, email, phone |
| **Course data** | ID, name, code, department, credit hours, assigned instructor |
| **Attendance data** | student ID, session ID, date, time, status |
| **Class Session data** | session ID, course ID, date, time, room ID |
| **Room data** | roomID, location, type (lab, lecture), capacity |

## 🧑 User Roles
| Role |Permissions|
| ------------- | ------------- |
| **Student** | View attendance, personal profile |
| **Instructor**  | Take attendance, view and export reports for their courses |
| **Admin** | Add/edit/delete users, courses, rooms; full access to system data |
| **SuperAdmin(IT)** | Advanced settings, device integrations, DB management |







