# vehicles
The following project contains two subtasks:

Their are classes Vehicle, Car, and F1.
Their is interface WaterVehicle.
The details of the classes that constitute the project are:

Vehicle: name, currentSpeed, currentDirection

constructor: given the name of the vehicle, initialize speed and direction as 0.
move(speed, direction): set the current speed and direction
steer(direction): Add direction to the currentDirection
stop(): Stop the car by setting current speed to 0
Car: extends Vehicle
accelerate(rate): add rate to the current speed and change the gear accordingly
Boat: implements WaterVehicle interface

