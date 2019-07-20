--源数据MYSQL
Create table If Not Exists courses (class varchar(255), ctype varchar(255))
drop table courses
insert into courses (class, ctype) values ('Chinese', 'major subject')
insert into courses (class, ctype) values ('Math', 'major subject')
insert into courses (class, ctype) values ('English', 'major subject')
insert into courses (class, ctype) values ('Biology', 'minor subject')
insert into courses (class, ctype) values ('Computer', 'minor subject')
select * from courses
Create table If Not Exists students (name varchar(255))
drop table students
insert into students (name) values ('A')
insert into students (name) values ('B')
insert into students (name) values ('C')
select * from students

--目标表ORACLE
Create table courses (id varchar(255), class varchar(255), ctype varchar(255), is_valid char(1))
drop table courses
Create table students (id varchar(255), name varchar(255), is_valid char(1))
drop table students
Create table students_courses (id varchar(255), sid varchar(255), cid varchar(255), is_valid char(1))
drop table students_courses
select * from students_courses
