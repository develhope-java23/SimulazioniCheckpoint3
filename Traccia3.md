# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Exercise:
  - id: long (Identifier)
  - description: String
  - minScore: float
- Submission:
  - id: long (Identifier)
  - exerciseId: long
  - score: float
  
The following constraint must be respected:
- Each submission must have a score which is greater or equal to the minimum score of its reference exercise

The application should provide endpoints to perform the following operations:
- Insert a new exercise
- Insert a new submission
- Retrieve all exercises
- Modify an exercise minimum score. Return an error if there is at least one submission which has a lower score than the new minimum.
