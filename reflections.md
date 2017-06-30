## Refections
The requirement of the project is to drive the car at a maximum reference speed around the track with no tire leaving the drivable portion of the track surface.
### Model
The model used was Kinematic model which is simplification of dynamic models that ignore tire forces, gravity and mass.  The state of the car is determined by following variables:
1. x position
2. y position
3. cross track error (cte)
4. velocity (v)
5. orientation (psi)
6. orientation error (espi)

#### Actuators:
1. steering angle (delta)
2. acceleration (throttle)

Using the following equation we can predict the state at t + 1 :
![alt text][/mages/state_equation]
