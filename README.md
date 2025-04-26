# cs3630-project-6-warehouse-automation-solved
**TO GET THIS SOLUTION VISIT:** [CS3630 Project 6-Warehouse Automation Solved](https://www.ankitcodinghub.com/product/cs3630-3630-intro-to-robotics-and-perception-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127069&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3630 Project 6-Warehouse Automation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Overview

In this lab, your robot will be tasked with supervising a warehouse. The robot will have to map out its environment (using a lot of the same algorithms you have employed throughout the class), while avoiding obstacles (walls). If an obstacle is hit, the run is terminated. Your goal is to visit all of the five landmarks within 6 minutes (360 seconds). All the important files are present under the folder controllers/exploration_controller/. Specifically, focus on controllers/exploration_controller/exploration.py file.

Exploration task

Map Layout

The map is organized as an occupancy grid, where each cell in the grid is either labeled “free”, “obstacle”, or “landmark”. In addition, every cell in the map starts out as unexplored (grey area), and as grid cells enter the robot’s field of vision, the cells are detected by the robot’s sensors and should be marked as explored.

Localization

Planning

You will implement the frontier_planning() as well as the exploration_state_machine() functions in controllers/exploration_controller/exploration.py in order to traverse the map and visit all of the landmarks. Your frontiers are the unexplored cells in the map that are adjacent to the explored cells, and your algorithm should move to the centroid of the frontiers.

Local Testing:

Make sure to take advantage of functions in utils.py and remember that your run for either phase will terminate if you collide with an obstacle.

Grading

Rubric

Autograder will grade your exploration on 10 maps.

Submission Materials

Submit your exploration.py file to gradescope.

If you relied significantly on any external resources to complete the lab, please reference these in the submission comments.

Running with Webots

Once the exploration.py is complete, you can validate that your algorithm works with the WeBots simulator.

1. Open exploration_controller.py and ensure that the maze_name (line: 255) is set to the map you would like to test on. The map names are “maze1”, “maze2”, and “maze3”. A working implementation should work on all three maps.

2. Launch WeBots. Click File &gt; Open World, then navigate to the “worlds” subfolder. Open the .wbt file which matches the maze_name from step 1.

3. A GUI window should appear which shows your exploration code running in a simple 2D approximation of the world to find a path. Then, the robot in WeBots should start moving along this path.

a. We recommend selecting the “DEF e-puck Robot” object via the sidebar in the top-left of the WeBots screen. This will allow you to see the coordinate frame of the robot while it moves through the maze.

b. Note that the 2D GUI window should automatically close after the robot is done moving.

c. Also, the webots execution takes significantly longer time to run compared to GUI and autograder version.

Examples (Robot-GUI)

Robots should navigate towards the frontier

Robot can use RRT to get around the obstacle

Blue dot signifies the goal point

Dotted line signifies the path to the next waypoint in the RRT path
