# University-DBMS  
The objective of this project is to design and implement a comprehensive data management system for a university using SQL, PLSQL, Advanced PLSQL, Red Hat, Bash scripting, Java SE, and OOP principles. 
## Database:
mapping:  
Department (dname (PK), dept_description, manager_id (FK))  
Student (stud_id (PK), fname, lname, address, email, gender, faculty, dname (FK)))  
Stud_pho (stud_id (FK), phone)  
Professor (professor_id (PK), fname, lname, salary, address, email, dname (FK))  
Prof_pho (professor_id (FK), phone)  
Course (cid (PK), c_name, c_hours, dname (FK), professor_id (FK))  
Stud_course (stud_id (FK), cid (FK),grade)    
## PLSQL Implementation: 
-	Updating some information.  
-	Calculating GPA.  
-	Test the PLSQL scripts with sample data.  
## Automation Scripts:
-	Bash script for database backup.  
-	Bash script for monitoring disk space and sending alerts.  
-	Schedule a script to check for anomalies and send notifications.  
## Java Application Development:
-	Develop Java classes for Student, Course, and Department using OOP principles.  
-	Implement CRUD (Create, Read, Update, Delete) operations in the Java application.  
-	Integrate the Java application with the SQL database.  
-	Test the application with various scenarios.  
## Integration and Reporting:
-	Implement a feature in the Java application to generate a report.
-	The report should display a list of courses, enrolled students, and average GPA for each course.
-	Ensure seamless integration between the Java application and the database.
-	Make the presentation for the project.
