# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Student
  - id: long (Identifier)
  - name: String
  - email: String
- ExerciseSubmission:
  - submissionId: long (Identifier) 
  - exerciseId: long
  - student: Student (References Student.id)
  - marks: byte
  
The following constraint must be respected:
- Submission marks must be comprised between 1 and 5

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new exercise submission
- Retrieve all exercise submissions
- Modify an exercise marks, respecting the relative constraint
- Get the number of exercises submitted by a student

