# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Student
  - id: long (Identifier)
  - name: String
  - email: String
- ExerciseSubmission:
  - submissionId: long (Identifier) 
  - exerciseId: String
  - student: Student (References Student.id)
  - marks: short
  
The following constraint must be respected:
- Submission marks must be comprised between 0 and 5. If marks is -1, it means that the exercise has not been assessed yet.

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new exercise submission
- Retrieve all exercise submissions from a given student that have not been assessed yet
- Modify an exercise marks, respecting the relative constraint
- 
