<h1>Implementation of Dijkstra's & AStar Algorithm for a rigid robot with Animation!</h1>

  <h2>Pre-requisites to run the code:</h2>

    1. Python 3 should be installed on your system.
    2. PyGame - Install it using 'pip install pygame'
    3. ROS melodic with Gazebo and turtlebot3 packages are required

Note:  Other libraries used are inbuilt.</br>

  <h2>Instructions to run the code:</h2>
  
    1. Clone the repository by clicking the big green button located here: https://github.com/DrKraig/Planning-Algorithms
    2. Open command prompt or terminal.
    3. Navigate to this directory using 'cd Planning-Algorithms/TurtleBot/'
    4. To Run Dijkstra, Navigate to 'cd Dijkstra'. If OS is Ubuntu, type 'python3 Dijkstra.py'
    4. To Run AStar, Navigate to 'cd Astar'. If OS is Ubuntu, type 'python3 AStar.py'
    5. To Run AStar with Dublin Curves on pygame, Navigate to 'cd DubinCurves/pygame'. If OS is Ubuntu, type 'python3 AStar.py'
    6. Enter the parameters of the robot
    7. Enjoy!


<h2>Videos are present in the 'Output Videos' folder. The output can also be viewed below in GIF format.</h2>

## A few instresting things about this prorgam.
  1. For each and every node, its co-ordinates, neighbours, parent and the cost that node is being stored.
  2. The parent node has been created so that once the final state is found, a solution could be backtracked.
  3. The math for finding out the line, rectangle, circle and ellipse equations was found by plotting the map on GeoGebra.
  4. The program will let you know if the starting point or ending point is inside the obstacle or outside the arena
  5. All the equations for the algebraic planes are defined in their approppriate methods.