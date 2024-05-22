# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Tutor:
  - id: long (Identifier)
  - name: String
  - expertise: String
- Student
  - id: long (Identifier)
  - name: String
  - email: String
  - assignedTutor: Tutor (References Tutor.id)
  
The following constraint must be respected:
- Each tutor cannot be assigned to more than 3 students

The application should provide endpoints to perform the following operations:
- Insert a new tutor
- Insert a new student
- Get the tutors with the expertise "Java"
- Retrieve a specific tutor
- Modify a student's tutor

  
