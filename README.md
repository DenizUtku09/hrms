# HRMS
## Database
![image](https://github.com/ErenKCKL/hrms/assets/67120341/061e14e1-db1c-4719-8fb5-ef54b27b95f1)


## Project Overview

The Comprehensive HRMS project aims to develop a full-fledged Human Resource Management System that automates and streamlines various HR processes. The system will be built using Java as the primary programming language, with SQL for database management. This project will cover different aspects of HR management, including employee management, recruitment, payroll, and training.

## General Requirements

Create database for Human Resources Management System (HRMS) requires designing tables to store data related employees, departments, positions, attandence, leaves, recruitment, payroll and performance of employees.

### Req: 1-Job seekers should be able to register in the system.

1. During Registiration, the user asked for their first name, last name, national identification, or pesel, birth year, email, password and password confirmation.
2. All fields are mandatory.
3. If there is already a registered email or national identification number, registiration does not take place
4. Email verification is required for reqistiration.

### Req: 2- Employers should be able to register in the system

1. During reqistiration, the user asked for their company name, website, email with the same domain as the website, phone, password, and password conformation.
2. All fields are mandatory.
3. Email verification is required for reqistiration
4. If there is already a registered email or national identification number, registiration does not take place.

### Req: 3- General job position names should be added to the system.

1. These position connot be duplicated.

### Req 4: Employers should be listed. (Only the entire list)

### Req 5: Job seekers should be listed. (Only the entire list)

### Req 6: Job positions should be listed. (Only the entire list)

### Req 7: Employers should be able to add job postings to the system

1. In the job posting form
2. A general job position should be selectable from the dropdown list (For example, Java Developer) (Mandatory)
3. A job description entry should be possible. (For example; proficient in JAVA, C#, etc. languages for our company...) (Mandatory)
4. City information should be selectable from a dropdown list. (Mandatory)
5. A min-max entry for the salary scale should be possible. (Optional)
6. The number of open positions entry should be possible. (Mandatory)
7. The last application date entry should be possible.

### Req 8: All active job postings in the system should be listed.

1. The list should be in table format.
2. The list should include company name, general job position name, the number of open positions, publication date, and last application date information.

### Req 9: All active job postings in the system should be listed by date.

1. The list should be in table format.
2. The list should include company name, general job position name, the number of open positions, publication date, and last application date information.

### Req 10: All active job postings of a company in the system should be listed.

1. The list should be in table format.
2. The list should include company name, general job position name, the number of open positions, publication date, and last application date information.

### Req 11: Employers should be able to close a job posting in the system. (Inactive posting)

### Req 12: Candidates should be able to enter their CVs in the system.

1. Candidates should be able to add the schools they attended to the system. (School name, department)
2. They should be able to enter the years they attended these schools into the system.
3. If not graduated, the graduation year can be left blank.
4. Candidates' schools should be sorted in reverse order by graduation year. If not graduated, this school should still be displayed at the top and as "ongoing."
5. Candidates should be able to enter their work experience. (Company name, position)
6. They should be able to enter the years they did these experiences into the system.
7. If they still work, the year of leaving the job can be left blank.
8. Candidates' experiences should be sorted in reverse order by year. If they still work, this experience should still be displayed at the top and as "ongoing."
9. Candidates should be able to enter the foreign languages they know into the system. (Language, Level -\> 1-5)
10. Candidates should be able to enter a photo into the system. The candidate's photo will be stored at [https://cloudinary.com/pricing](https://cloudinary.com/pricing). (External service integration) Use the free account.
11. Candidates should be able to enter their GitHub addresses into the system.
12. Candidates should be able to enter their LinkedIn addresses into the system.
13. Candidates should be able to enter the programming languages or technologies they know into the system. (Programming/Technology name) For example; React
14. Candidates should be able to add a cover letter to the system. (For example: I love to work....)

### Req 13: The entire CV information of a candidate should be viewable.

For all requirements in our HRMS system;

Create a React project. Model your component hierarchy using the "UML component diagram" technique (research). Add your model image to your Github readme file. Create your React components. Create all your React components just in terms of design. Write JavaScript services and axios codes for all requirements. Do not connect them to React components. (Research Post, Put, Delete) Connect only the listing requirements with your JS service.

### Req 14: Employers, when sharing a job posting, should be able to enter which of the on-site or remote work types is suitable from the drop-down box.

### Req 15: Employers should be able to enter the working time feature of the job from the drop-down box. (For example: Part-time, full-time...)

### Req 16: Job postings entered by employers should be published after being approved by HRMS personnel.

### Req 17: Create the design of your forms using Formik. Connect to the backend (Research and implementation) [https://formik.org/](https://formik.org/)

Write both backend and frontend code for the following requirements.

### Req 18: Candidates should be able to update their CVs.

### Req 19: Employers should be able to update their company information. (Challenge requirement:))

#### Acceptance criteria

1. HRMS personnel approval is required for the update to become active.
2. Updates will become active after HRMS personnel approves.
3. Old information will be displayed until the HRMS personnel updates.
4. Until the HRMS personnel approves, when the employer views the company information, the old information should be displayed and the message "awaiting approval for update" should be displayed.

### Req 20: HRMS personnel should be able to update their information.

### Req 21: Candidates should be able to add postings to their favorites.

### Req 22: Candidates should be able to filter postings by location and work type (part-time, etc.) options.

### Req 23: When listings are displayed, there should be default pagination in tens. Users should be able to change the number of pages to 10-20-50-100.

## Technologies

1. Java as the programming language
2. React for the graphical user interface (GUI)
3. PostgreSQL for database management
4. JPA for database connectivity
5. Maven for build automation and dependency management

## Development Steps

1. Requirements Analysis: Gather requirements and define the scope of the project.
2. System Design: Design the system architecture, database schema, and user interfaces.
3. Implementation: Develop the system components and functionalities using Java and SQL.
4. Testing: Test the system for functional and non-functional requirements, including performance, security, and usability.
5. Deployment: Deploy the HRMS on a suitable platform, such as a web server or a local network.
6. Documentation: Prepare user manuals, system documentation, and other project artifacts.
7. Maintenance: Provide system updates, bug fixes, and enhancements as required.
"# hrms" 
