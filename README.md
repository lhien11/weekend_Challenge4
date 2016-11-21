# To Do List App
This is a 'To Do List' app I designed. It allows the user to create a new task and check it off when complete.

### To Do
- Delete button functionality

## Set-up
Create this table using Postico:

1. ``CREATE DATABASE to_do;``

2. ``CREATE TABLE tasks (
id SERIAL PRIMARY KEY,
task varchar(80) NOT NULL,
complete varchar (5)
)``

### Example Table:

| id     | task          | complete |
| -------|-------------- | -------- |
| 1      | Do the dishes |    no    |
| 2      | Walk the dog  |   yes    |



# Author
- Hien
