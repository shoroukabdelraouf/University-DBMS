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
