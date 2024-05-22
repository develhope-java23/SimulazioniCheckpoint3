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
- Submission marks must be comprised between -1 and 5. If marks is -1, it means that the exercise has not been assessed yet.
- A submission can be assessed only if it was not assessed yet, namely that marks == -1 

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new exercise submission
- Retrieve all exercise submissions from a given student that have been assessed already
- Modify an exercise marks, respecting the relative constraint.
