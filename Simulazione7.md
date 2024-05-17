# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Tutor
  - id: long (Identifier)
  - name: String
  - email: String
- ExerciseSubmission:
  - submissionId: long (Identifier) 
  - exerciseId: long
  - assignedTutor: Tutor (References Tutor.id)
  - marks: byte
  
The following constraint must be respected:
- Submission marks must be comprised between 0 and 5. If marks is 0, it means that the exercise has not been assessed yet.

The application should provide endpoints to perform the following operations:
- Insert a new tutor
- Insert a new exercise submission
- Retrieve all exercise submissions for a given tutor
- Modify an exercise marks, respecting the relative constraint
- Get the number of exercises assigned to a tutor that have not been assessed yet.
