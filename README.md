# Cars-Reenactment
The project is a final roject for CSC376: Fundamentals to Robotics. 
It is a mini car pit stop inspired by a scene from the film "Cars" where the Franka Emika Panda Robot pick and places parts of the car and screws the parts together.
Utilized the Franka Desk software to implement the actions on the Franka Emika Panda Robot.



<h2>Simulation</h2>

[![Simulation](https://img.youtube.com/vi/phOzr_P2_O4/0.jpg)](https://www.youtube.com/watch?v=phOzr_P2_O4)


Steps the Franka Robot takes:
1. Pick up the bottom of the car from remote position and place the car on a pre-made set-up station.
2. Pick up the cover of the car and places it on top of the bottom of the car.
3. The robot waits for a human to place the screws in the holes.
4. Once the human taps the front of the robot, it grabs the electric screwdriver.
5. Then with the screwdriver it grabbed, it tries to screw the screws placed on the car. The moving down motion is programed by applying relative motion and force downwards.
6. Once the screwing is done, the robot drops the screwdriver at designated "orange" space.
7. Picks up the built car and places it outside of the set-up station. 
