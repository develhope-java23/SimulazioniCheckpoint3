# Java 23 - Checkpoint 3
Realize a Spring application which handles the following data:
- Pilot:
  - id: int (Identifier)
  - nickname: String
  - speedRecord: int
- Car:
  - plate: String (Identifier)
  - maxSpeed: int
  - assignedPilot: Pilot (References Pilot.id)
  
The following constraint must be respected:
- A vehicle's maxSpeed cannot be negative
- A pilot can be assigned only to one vehicle and viceversa
- A pilot cannot be assigned to a vehicle's which maximum speed is lower than its speed record

The application should provide endpoints to perform the following operations:
- Insert a new pilot
- Insert a new vehicle
- Retrieve all vehicles assigned to a pilot
- Retrieve the vehicle with the greatest maximum speed
  
