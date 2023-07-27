# NetSim
Wireless Sensor Network Routing Algorithm Simulation with Obstacles

![image](https://github.com/hsmazumdar/NetSim/assets/16040087/f01e1e3d-7021-4a93-b29c-ae8b1fef664f)

Figure 1: Routing with Red Obstacle using AStar and BestFirst Algorithms. AStar rout is shown in pink and BestFirst is in maroon colors. The scores of each algorithm (Total number of nodes per path) are displayed on the right.

 
![image](https://github.com/hsmazumdar/NetSim/assets/16040087/7c5be72b-abcb-40db-a3ff-d6f2f2c8b5bd)

 


1.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/bf9f2adc-37b6-465b-9d34-64e92dcdf89e)
Enter desired number of nodes and press Node button(5) to populate random distribution of desired number of nodes.

2.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/89eaf29c-067d-480f-8128-9bc7fa88336e)
Simulation zone is divided in Number of Column, Number of Rows (eg. 6,4) matrix to enable node distribution constrain of uniformly random distribution of nodes with 6 columns and 4 rows. Press Grid (3) to implement and show the grid.

3.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/b62093e6-3801-4c3d-b56d-a478c80eda02)
Select Grid check box to display grid as per the dimensions (Column, Row) as specified in Zones (2).

4.  ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/dcaf85c0-c3ba-479a-b401-1c3139b5802c)
Press Clear button to clear the nodes deployment. Pressing this will give blank region. 

5.  Press Node button to populate number of nodes as specified in a text-box with label “Nodes”.

6.    Press Re-Draw button to re-draw after performing A-Star and Best First Search experiment on selected source and destination nodes. It will re-draw  node deployment, selected source and destination nodes and obstacle. 

7.   Press Src-Dst button to randomly select source node and destination node to perform experiment with A-Star and Best First Search algorithm. If obstacle is selected then source node and destination nodes will be randomly selected on two sides of obstacle.

8.   Press A-star button to execute A-Star algorithm on selected source and destination nodes. It plots a path between source and destination.
9.   Press BstFst button to execute Best First Search algorithm on selected source and destination nodes. It plots a path between source and destination.

10.   Enter the value between 0 and 100 to specify the size of an obstacle as a percentage of the screen when checkbox is selected(11). 

11.   Select the checkbox to draw an obstacle as specified in textbox in (10). An obstacle coordinates are stored in PolyList.txt file.

12.  Enter the number of experiments you want to carry out for chosen configuration of nodes. It will start when Save button in (13) is pressed.

13.   Press Save button to executed large number of experiments and save its output. It creates two files namely Experiments.txt and Parameters.txt files. 

14.  Press Load button to display saved configuration of nodes and obstacle. It reads Parameters.txt and displays the saved configuration.

15.   Press Analysis button to see generated results after Save is pressed. It  displays (source,destination) node pair in combo-box from Experiments.txt file. This pair of nodes are those nodes whose number of intermediate node in A-Star output is less than Best First search output.

16.   Combo-box displays the result of experiment carried out and stored in Experiments.txt file. It displays source, destination node pair when Analysis button is pressed. It displays path between source and destination for both A-Star and Best First Search algorithm when a specific pair is selected from combo-box list. It displays on those pairs in which A-Star executes with fewer intermediate nodes than Best First Search.

