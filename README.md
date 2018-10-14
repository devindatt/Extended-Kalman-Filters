# Udacity - Extended Kalman Filter 

[![N|Solid](https://media.giphy.com/media/cJoYG1whfhswGwLASr/giphy.gif)](https://medium.com/udacity/term-2-in-depth-on-udacitys-self-driving-car-curriculum-775130aae502)


This project implements an extended Kalman filter in C++ to tracking a object with simulated LIDAR and RADAR.

[![N|f](https://image.ibb.co/f6Lob9/lidar-radar-pic.png)]

Input data consisting of laser measurements (given directly as x and y positions, with some known uncertainty) and radar measurements (given as radius, angle, and radial velocity relative to some fixed measurement site, with some known uncertainty) are combined with a motion model to track a vehicle with much better accuracy than the individual measurements alone allow.

The code presented here is designed to work with the Udacity term 2 simulation executable, and so cannot be run standalone. You will need to install code that will allow a 'socket' from the server code to the client.

Please install uWebSocket plugin to create a connection to the simulator.
Once that is installed you can implement the simulator code.

-----------
