# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Tutor:
  - id: long (Identifier)
  - name: String
  - seniority: int
- Student
  - id: long (Identifier)
  - name: String
  - email: String
  - assignedTutor: Tutor (References Tutor.id)
  
The following constraint must be respected:
- A tutor's seniority must be between 1 and 4

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new tutor
- Retrieve the students assigned to a specific tutor
- Modify a student's tutor
  
