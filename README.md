Download Link: https://assignmentchef.com/product/solved-dbs-lab2-student-database
<br>
Create a student database with following Tables:

<strong>Student(snum: integer, sname: string, major: string, level: string, age: integer)  </strong>

<strong>Class(coursename: string, meets_at: time, room: string, fid: integer)  </strong>

<strong>Enrolled(snum: integer, coursename: string)  </strong>

<strong>Faculty (fid: integer, fname: string, deptid: integer,Salary:integer) </strong>




Level includes FR(Fresher), SO(Sophomore), JR(Junior) and SR(Senior).

Major denotes the specializations of the department a student is enrolled in. For e.g. COE department can have Software Engineering, Human Computer Interaction, Data Science, Theoretical Computer Science as its majors. Enrolled has one record per student-class pair such that the student is enrolled in the course

A student may attend courses assigned in different rooms. Assume that a faculty can also teach an online video lecture course(e.g. couresera, educity) in a class room without students being enrolled in it. So, a faculty can teach maximum 5 courses.

<strong> </strong>




Write sql queries for the following questions:




<ol>

 <li>Display student name, major who is the youngest of all students</li>

 <li>Display student name, major who is the oldest of all students</li>

 <li>Display student name, major who is the youngest of all students Using “<strong>LIMIT” </strong>Keyword</li>

 <li>Display student name, major who is the oldest of all students Using <strong>“LIMIT”</strong> Keyword</li>

 <li>Display students records whose major starts with “D” or ends with “N”</li>

 <li>Display student records in alphabetical order</li>

 <li>Determine faculty id, dept id , who has highest salary</li>

 <li>Increment salary of faculty by 20%</li>

 <li>Display faculty id and fname who are from computers department or salary &gt;</li>

</ol>

=50000 in ascending order of there salary

<ol start="10">

 <li>Display student records who are from “S.E” major and taking DBMS course in alphabetical order</li>

 <li>Display student id, name whose name starts with “S” or ends with ”A”</li>

 <li>Find all student records containing the word “ha” .</li>

 <li>Display senior students from “sofware engineering”</li>

 <li>Display records of students who took a course on <strong>DBMS</strong></li>

 <li>Determine the faculty id and the department id where a faculty teaches courses in room H05</li>

 <li>Display Average salary of the faculty from Computers department</li>

 <li>Determine courseid, course name in which maximum students are enrolled</li>

 <li>Determine course id,course name in which minimum students are enrolled</li>

 <li>Determine faculty id, faculty name who is offering more number of courses</li>

 <li>Find the names of all Juniors (level = JR) who are enrolled in a class taught by ‘Jagadessh.K’.</li>

 <li>Display the names of all online courses a particular faculty</li>

</ol>











