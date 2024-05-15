# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Dealer:
  - id: int (Identifier)
  - name: String
  - isOwner: boolean
- Vehicle:
  - plate: String (Identifier)
  - model: String
  - cost: int
  - assignedDealer: int
  
The following constraint must be respected:
- A vehicle's cost must be positive
- A vehicle's plate must contain exactly 6 characters

The application should provide endpoints to perform the following operations:
- Insert a new dealer
- Insert a new vehicle
- Retrieve all vehicles assigned to a dealer
- Retrieve the sum of costs of vehicles assigned to a dealer
  
