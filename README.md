# CECS475
475Labs
The database SchoolDB  has has different tables, stored procedures and views.

One-to-One: Student and StudentAddress have a one-to-one relationship eg. Student has zero or one StudentAddress. <br/>
One-to-Many: Standard and Teacher have a one-to-many relationship eg. many Teachers can be associate with one Standard. <br/>
Many-to-Many: Student and Course have a many-to-many relationship using StudentCourse table where StudentCourse table includes StudentId and CourseId. So one student can join many courses and one course also can have many students.

<br/>

# Task
Write a client to implement CRUD operations  to test all the methods defined in the class BusinessLayer. <br/>

Table Teacher <br/>
Create, update, and delete - Update by seaching teacher id or teacher name
Input the teacher id and then display all courses that has that teacher id.
Display all standards

Table Courses <br/>
Create, update, and delete - Update by searching course id or course name.
Display all courses
