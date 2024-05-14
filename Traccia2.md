# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Tutor:
  - id: long (Identifier)
  - name: long
  - expertise: String
- Student
  - id: long (Identifier)
  - name: String
  - email: String
  - assignedTutorId: long
  
The following constraint must be respected:
- Each student can only be assigned to one tutor

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new tutor
- Retrieve all tutors
- Modify a student's tutor
- Get the number of students assigned to a tutor
  
