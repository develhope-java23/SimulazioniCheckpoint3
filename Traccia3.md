# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Tutor:
  - id: long (Identifier)
  - name: String
  - email: String
  - yearsOfExperience: byte
- Student
  - id: long (Identifier)
  - name: String
  - assignedTutor: Tutor (References Tutor.id)
  
The following constraint must be respected:
- A tutor's years of experiences must be between 0 and 20

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new tutor
- Retrieve the students assigned to a specific tutor
- Modify a student's tutor
  
