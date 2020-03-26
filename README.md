# Build My World

Project Aim: 

   1) To build a single floor wall structure with models and robots in Gazebo.

   2) Modelling a robot with links connected to joints in Gazebo.

   3) Importing wall structure and two instances of the created models of robot inside an empty Gazebo World.

   4) Writing C++ World Plugins to interact with the above created world.


Instructions to download and run the project:
 
   0) Make sure you have a stable version of gazebo downloaded and running (Gazebo Tutorials: http://gazebosim.org/tutorials?cat=guided_b&tut=guided_b1 )

   1) Create a new folder, say _Build__My__World_ and clone this repository with ```git clone https://github.com/sourabhmisal/Build_My_World.git ```

   2) Create a build directory and compile the code in the following steps:
      $ cd ~/Build_My_World
      $ mkdir build
      $ cd build
      $ cmake ../
      $ make
      $ export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/path-to-your-folder/Build_My_Robot/build   

   3) Launch the world file in gazebo to load the world
      $ cd ~/Build_My_World/world
      $ gazebo my_world.world

   4) Visualize the output 

