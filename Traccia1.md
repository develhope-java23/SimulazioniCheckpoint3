# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Student
  - id: long (Identifier)
  - name: String
  - email: String
- Exercise:
  - id: long
  - student_id: long
  - marks: int
The following constraint must be respected:
- Each student can submit an exercise only once, therefore there cannot be two "Exercise" entries with the same id and student_id.

The application should provide endpoints to perform the following operations:
- Insert a new student
- Insert a new exercise
- Retrieve all students
- Modify an exercise marks
- Get the number of exercises submitted by a student
