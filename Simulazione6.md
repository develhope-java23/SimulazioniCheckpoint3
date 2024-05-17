# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Dealer:
  - id: int (Identifier)
  - firstName: String
  - lastName: String
  - isAdmin: boolean
- Vehicle:
  - plate: String (Identifier)
  - power: long
  - cost: int
  - assignedDealer: Dealer (References Dealer.id)
  
The following constraint must be respected:
- A vehicle's power cannot be positive
- A vehicle's plate must contain exactly 7 characters

The application should provide endpoints to perform the following operations:
- Insert a new dealer
- Insert a new vehicle
- Retrieve all vehicles assigned to a dealer
- Retrieve the maximum power of a vehicle assigned to a specific dealer
  
