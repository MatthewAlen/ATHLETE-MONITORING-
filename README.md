# BatStateU ARASOF Athlete Monitoring System A Data-Driven Approach to Performance, Health, and Compliance Management

##  Group Members
- Botones, John Dave B.
- Pereyra, Matthew Alen P.
- Dimafelix, Dane Joshia B.

## Introduction / Summary
###
Athlete monitoring is important in sports to keep athletes performing well, avoid injuries, and meet training and academic requirements, but many schools still use manual methods like paper and spreadsheets, causing delays and poor communication. At Batangas State University, tracking athlete performance, health, and compliance is still manual, leading to late training changes, inconsistent records, and weak coordination between coaches and staff. To solve these problems, this study proposes the BatStateU Athlete Monitoring System—a centralized, automated, and web-based platform that uses real-time data, digital records, and performance analytics to improve athlete tracking, training, and overall sports management.

### Scope
The platform allows:
- Athlete registration 
- Training/game scheduling
- Practice and Game Tracking
- Practice Compliance Monitoring
- OCR for Documents Management
- Athlete Injury Status Tracking(Mobile App)
- Attendance Location Tracking
- Academic compliance monitoring
- Role-based access for athletes, coaches, admins

### Definitions, Acronyms, and Abbreviations
- **AMS**: Athlete Monitoring System
- **CHED**: Commission on Higher Education
- **OSDP**: Office of Sports Development Program
- **OCR**: Optical Character Recognition
- **PU**: Perceived Usefulness
- **PEU**: Perceived Ease of Use

## Overall Description


## System Architecture
![Blank diagram](https://github.com/user-attachments/assets/496e1a1c-31ae-4986-89fc-b2fcb7a98020)
The BatStateU Athlete Monitoring System allows admins, athletes, and coaches to access and manage athlete data through desktop and mobile devices connected to a central web server and database. Admins handle academic compliance and records, athletes check schedules and performance while uploading documents via OCR, and coaches manage training and monitor progress in real time. This setup ensures smooth data flow, better decision-making, and more efficient sports program management.

### Software Perspective & Functions
The BatStateU ARASOF Athlete Monitoring System is a web-based and mobile-accessible platform developed to streamline the management of athlete data within the university’s sports programs. It follows a modular, role-based structure, where different user types (athletes, coaches, and administrators) access the system with specific permissions based on their roles.

The system is developed using the following technology stack:
- React.js and Bootstrap for a clean and mobile-friendly user interface.
- PHP (Laravel) for handling system processes and user logins.
- MySQL for storing athlete records, training logs, and medical data.
- XAMPP for running the system during development.

### Use Case Characteristics & Diagrams
Included diagrams:

- **Use Case Diagram**
![NEW](https://github.com/user-attachments/assets/a8717b2b-1eab-4df2-8a2d-ddadf447f932)

Use Case Diagram for the BatStateU ARASOF Athlete Monitoring System, highlighting how Athletes, Coaches, and Admins interact with the system. Athletes can track attendance via GPS, upload documents through OCR, view training schedules and performance, and update their details; Coaches manage training, monitor performance and compliance, and handle sports and user roles; Admins oversee the system, ensuring proper management and monitoring. These core functions, grouped within the system boundary, help streamline performance tracking, compliance, and training management for student-athletes.


- **Context Diagram**
 ![CONTEX](https://github.com/user-attachments/assets/fda00402-4d09-4d1c-9550-380c068764a9)

 Context Diagram of the BatStateU ARASOF Athlete Monitoring System, which acts as a central platform for managing athlete data, training schedules, compliance, attendance, and performance. It connects student athletes, coaches, and administrators, allowing each to send and receive relevant information like schedules, reports, and records. This setup improves data accuracy, streamlines tasks, and supports better tracking of student-athlete progress and development.


- **Data Flow Diagram**
![dfdnew](https://github.com/user-attachments/assets/1fa8ecfd-eeda-4191-a4d7-2a1f15775726)
Data Flow Diagram (DFD) of the BatStateU ARASOF Athlete Monitoring System, providing a structured representation of how data flows between different components. It outlines key processes, data stores, and interactions with external entities to ensure efficient management of student-athlete records, training sessions, compliance documents, attendance, and performance tracking. The diagram highlights the system’s workflow, showing how information is collected, processed, stored, and utilized for generating reports and maintaining accurate records. Each process plays a crucial role in organizing athlete data, ensuring smooth coordination between administrators, coaches, and student-athletes.


### Constraints, Limitations, and Dependencies
- Manual data input (no wearables)
- Internet connection required
- Local campus use only
- No financial, ticketing, or sponsorship modules


## Specific Requirements
### System Features
- Secure login and role-based access
- Athlete Registration – Add and manage athlete profiles.
- Training & Game Schedule – Coaches can set training and game dates.
- Practice & Game Tracking – Record attendance and performance.
- Training Compliance – Check if athletes are attending required practices.
- Document Scanner (OCR) – Upload and scan documents easily.
- Injury Tracking (Mobile App) – Track athlete injuries and recovery.
- Attendance with Location – Records where attendance was made.
- Academic Monitoring – Track grades and academic requirements.
- Role-Based Access – Each user sees only what they need (coach, athlete, etc.).


### Interface Requirements
### System Features
- Mobile and desktop responsive design 
- Easy-to-use design for all types of users
- Data visualization for analytics

###  Non-Functional Requirements
### Usability
- The system must be easy to use for athletes, coaches, and admins, even those who are not tech-savvy.
- Both the mobile and web versions should have a clean and user-friendly interface.
### Performance
- The system should load athlete records, schedules, and reports quickly when connected to a stable internet connection.
- The mobile app must run smoothly on Android smartphones and tablets.
### Reliability
- The admin panel must provide real-time updates for attendance, compliance, and performance.
- The system should be available 24/7, especially during training seasons, events, and evaluation periods.
### Security
- All user passwords must be stored securely using encryption or hashing.
- Role-based access should be enforced:
    - Athletes can only access their own records, schedules, and compliance status.
    - Coaches can manage their team’s training, attendance, and performance.
    - SDP Head/Admin can view full system reports and manage users.

### 📎 Other Requirements
### Hardware Needed
- Android Phone – Used to test the mobile version of the system and check if it works well for athletes on the go.
- Laptop/PC – Used for developing the system, updating records, and managing the database.
### User Roles
- Athlete
- Coach/Trainer
- SDP Head / Administrator
