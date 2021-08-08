# RoboND-myRobot
### To Build and Run
  
  `clone this repo.
 - $ cd /home/RoboND/Project1
 - $ mkdir build
 - $ cd build/ 
 - $ cmake ../
 - $ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/RoboND/Project1/build
 - $ cd /home/RoboND/Project1/world/
 - $ gazebo SomeWorld`




 - $ gedit SomeWorld
 - #Copy this code
 - `<plugin name="welcome" filename="welcome.so"/>`
 - #and paste it under
 - `<world name="default">`
  
