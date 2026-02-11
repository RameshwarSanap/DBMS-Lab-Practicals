CREATE DATABASE CollegeDB;
USE CollegeDB;

CREATE TABLE Student(
    RollNo INT PRIMARY KEY,
    Name VARCHAR(50),
    Age INT,
    Marks INT
);

INSERT INTO Student VALUES
(1,'Ram',20,85),
(2,'Shyam',21,78),
(3,'Sita',19,90);

SELECT * FROM Student;
