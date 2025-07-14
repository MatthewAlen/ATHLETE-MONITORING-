# BatStateU ARASOF Athlete Monitoring System A Data-Driven Approach to Performance, Health, and Compliance Management

##  Group Members
- Botones, John Dave B.
- Pereyra, Matthew Alen P.
- Dimafelix, Dane Joshia B.

## Introduction / Summary
###
Athlete monitoring at Batangas State University is still done manually, which makes it hard to track performance and ensure athletes follow requirements. Without a central system, communication between coaches and school staff is slow, causing delays and messy records. This study suggests creating a web-based and mobile application system to make data tracking easier, faster, and more useful for improving athlete performance and managing sports programs better.

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

### System Architecture
<img width="1011" height="678" alt="image" src="https://github.com/user-attachments/assets/984d9fbc-c2da-4d7a-b7ac-35d6309cbec9" />
The BatStateU Athlete Monitoring System is used by administrators, athletes, coaches through both desktop and mobile devices. All data is stored in one central server, allowing users to easily access and update training, performance, and health records. This setup helps track athlete progress better, supports quick decisions, and makes managing the sports program easier.

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
<img width="851" height="1003" alt="image" src="https://github.com/user-attachments/assets/d6754ea9-4aa7-4b9b-9bc5-f92c65f4f48c" />

Use Case Diagram of the BatStateU Athlete Monitoring System, highlighting how Student Athletes, Coaches and Administrators interact with the system. Each user has specific tasks, such as viewing schedules, updating records, or generating reports, all grouped within the system’s main functions. The diagram helps show how the system supports efficient tracking, health monitoring, and training management for student-athletes.


- **Context Diagram**
  <img width="930" height="464" alt="image" src="https://github.com/user-attachments/assets/bcfd57aa-bcb7-4d6d-83e9-5e164eca9691" />
context diagram of the BatStateU Athlete Monitoring System, which acts as a central platform for managing athlete data, training schedules. It shows how coaches, athletes, and administrators interact with the system by inputting and receiving important information like reports and updates. This setup improves communication, keeps data accurate, and helps monitor athlete progress more effectively.


- **Data Flow Diagram**
 <img width="930" height="637" alt="image" src="https://github.com/user-attachments/assets/502a67d8-4fbd-4976-910c-54f1ff634210" />
Data Flow Diagram (DFD) of the system, which explains how data moves between users, processes, and storage. It outlines how information like training records, and performance details is collected, processed, and used to create reports. This helps ensure smooth coordination among administrators, coaches, medical staff, and student-athletes while keeping records accurate and organized.


- **Entity-Relationship Diagram **
<img width="930" height="666" alt="image" src="https://github.com/user-attachments/assets/92d90717-a2a5-46fb-8918-e420712fe3f2" />
Entity-Relationship Diagram (ERD) of the Athlete Monitoring System, which maps how different parts of the system work together to manage athlete information. It includes ten main entities such as UserAccounts, Athletes, Coaches, TrainingSessions, each playing a role in tracking training, attendance, performance, compliance, and health. The relationships between these entities ensure that data is well-organized, helping the system monitor athlete progress, eligibility, and overall well-being effectively.

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
- Mobile and desktop responsive design 
- Easy-to-use design for all types of users
- Data visualization for analytics
