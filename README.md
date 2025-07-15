# Title: BrgyGo: Al-Assisted Resident Information Management System with Evacuation Area Mapping

## Members: 
Leynes, Chris Michael M. Rodriguez, Jon Mary R. Sapotalo, Jackie Mae G.
      
## Introduction/Summary

     Purpose 
         BrgyGo aims to minimize errors, reduce the administrative workload, and promote a more organized
         and efficient governance structure by replacing traditional paper-based processes with the BrgyGo platform.
         The system ensures that all records are securely stored and easily accessible to authorized personnel, facilitating 
         smooth and efficient barangay operations while maintaining data integrity.
     Scope
         This study was focused on the development of BrgyGo, an application and  web-based system designed to 
         enhance barangay management by improving information accessibility and simplifying record-keeping for Brgy. Burgos, Tuy, Batangas.
         The system is primarily intended for barangay officials, administrators, and residents, where the administrator manages user access,
         community profiles, monitors resident information, and ensures that the system functions smoothly, equipping them with digital tools to 
         efficiently store, update, and retrieve vital records, such as residents' profiles, certifications, clearances, and other barangay records.
     
      Definitions, acronyms and abbreviations
         AI GPS (Artificial Intelligence Global Positioning System)- A smart navigation and tracking system that
         uses artificial intelligence to improve accuracy and efficiency.
         
         Barangay Officials - A person working in Brgy. Burgos and who can manage all complaints, process requests, 
         and post announcements for residents.
         
         BrgyGO System - A web-based system developed to enhance barangay record management, document processing,
         and information accessibility for barangay officials and residents of Brgy. Burgos, Tuy, Batangas.
         
         Chatbot - Automated conversations and responses to assist users with inquiries and provide relevant information. 
         It can communicate in both Tagalog and English. 
         
         Database - A organized collection of data, generally stored and accessed electronically from a computer system.
         
         Desktop - A personal computer or workstation used by barangay officials and residents to access the BrgyGO system.
         
         Management- Refers to the execution of various tasks within the system, including certificate requests, announcements, and blotter records.
         Mobile Phones - An electronic device that the residents of Brgy. Burgos can be used to access the BrgyGO system anytime and anywhere.
         
         Residents - A individuals who live in Brgy. Burgos and are officially registered as barangay members. In the BrgyGO system,
         residents can access barangay services, request documents, submit complaints, and receive important announcements. 
         
         Role-Based Access Control (RBAC) - A permission system in BrgyGO that restricts access based on user roles, barangay captain,
         secretary, treasurer, or resident, ensuring that only authorized personnel can perform certain actions.
         
         Secure Socket Layer (SSL) - A security protocol that encrypts data sent between a browser and a website or server.
         
         TAM (Technology Acceptance Model) - A theoretical framework that explains how users come to accept and use a new technology. 
         It suggests that people are more likely to adopt a system if they find it useful and easy to use.
         
         Usability - A extent to which a product can be used by the specified user to achieve a specified goal with effectiveness,
         efficiency, and satisfaction in a specified context of use.
         
         Web-based System - A convenient and easy to use from anywhere with an internet connection.


## Overall Description

         Discuss system architecture 
              The System architecture of the system is designed to make community management simple, secure, and accessible for residents,
              staff, and administrators. It connects users through an easy-to-use platform wherethey can log in, request information, and manage records.
 <img width="1527" height="785" alt="System Archi" src="https://github.com/user-attachments/assets/90c1a90f-d2bd-45b5-9718-480a20e098db" />
             
              Administrator – Oversee the entire system. They manage user access, monitor data, and ensure that the system functions smoothly.
              
              AI Chatbot – Users can ask the AI chatbot for help, whether they need to find an update, or get quick answers, the chatbot responds
              immediately. This makes it easier for residents to get the information the need without waiting for staff assistance. 
              
              Database – The system securely stores user records, residents request, and other important data in a structured database. 
              This makes information easy to find when needed and keeps it safe from unauthorized access.

              Residents – can log in, check community announcements, ask for assistance or submit requests for services. They have access to essential information               that helps them stay informed.

              Security – Each user must log in with their correct credentials before accessing the system. If a login attempt fails, access is denied
              to prevent unauthorized users from viewing sensitive information.

              Staff – members are responsible for handling resident requests, updating records and ensuring that information is accurate and updated.
              They help bridge the gap between residents and administrators.

              User Interaction - The residents, staff and administrators can log in using laptops, desktops, or mobile phones making them system accessible
              anytime and anywhere. Each user sees different interfaces based on their role, ensuring that they only have access to what they need.

              Website – The website serves as the main point of interaction for all users. The design is clean and user friendly, making it easy to navigate even                          for those who are not very familiar with technology.

             Software perspective and functions
                   Operating System - Windows 11
                   Integrated Development (IDE) -Sublime and Vs code
                   Programming Languages - Front-end: HTML, CSS, JavaScript Back-end: PHP, Python, Node.js
                   Database Management system - MySQL
                   Web Server and hosting - Infinity Free
                   API Chatbot -  Api Ninjas
                   API GPS - Google Maps API  leaflet
      
## Use Case
<img width="865" height="523" alt="Case study" src="https://github.com/user-attachments/assets/f975b342-5f39-4731-862e-3bae178d6314" />

## Data flow Diagram 
<img width="840" height="502" alt="Data flow  diagram" src="https://github.com/user-attachments/assets/084e2578-f316-48ee-84fd-a4a2d068116f" />

## Context Diagram 
<img width="750" height="498" alt="Context" src="https://github.com/user-attachments/assets/f252b0d5-df81-4c83-bf72-890d802dda8b" />

## Entity Relationship Diagram
<img width="740" height="399" alt="ERD" src="https://github.com/user-attachments/assets/707c7ea5-5381-489b-a964-b0b7a99f064f" />
      
## Requirement Analysis 
<img width="1420" height="761" alt="Requirement analysis" src="https://github.com/user-attachments/assets/14f7275d-d8c4-48b4-821c-16d0a03b3603" />
       
## Constraints, limitation and dependencies
       
      - Contraints 
             BrgyGo must be developed for Barangay officials in Barangay Burgos Tuy Batangas.
             It  web browsers designed for Barangay officials  and android device designed for Residents.
             
      - Limitations
            It not support offline access and sms. 
            
      - Dependencies 
            BrgyGo relies on a stable internet connection, MySQL database, web hosting or server, and secure authentication 
            frameworks to ensure the availability, security, and proper functioning of the platform.
            
## Specific Requirements
### System features 
      -Api for Evacuation center
      -Api for Chatbot Assistance 
      -Document requests 
      -Emergency response 
      -Barangay Announcements 
      -Digitize record-keeping
      
 

### Interface requirements
       Application Interface 
         https://github.com/jomai0830/Resident_App 
         
       Web Interface 
         https://github.com/KEL013021/Capstone-code
         
### Non-functional requirements
      Fast and Easy to Use 
         -BrgyGo is designed to respond quickly. The system should feel smooth and simple enough that even those with little technical experience (like barangay staff or residents).
      
      Always Available 
         -The system should be available almost all the time. It should also work well on commonly used web browsers like Chrome, and on Android phones.
          To avoid losing data, regular system backups must be done, and the platform should be stable even when many users are using it at once.


          
       
       
       

       

            

              


         
    
