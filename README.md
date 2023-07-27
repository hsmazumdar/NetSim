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

5.  ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/d2d091f8-4b6d-4a8a-8ae0-0dd1d825aff1)
Press Node button to populate number of nodes as specified in a text-box with label “Nodes”.

6.    ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/efb0df3e-d8d0-42de-9f12-4a3e2b894f53)
Press Re-Draw button to re-draw after performing A-Star and Best First Search experiment on selected source and destination nodes. It will re-draw  node deployment, selected source and destination nodes and obstacle. 

7.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/962f8525-debc-4606-b90a-f4c60796b72d)
Press Src-Dst button to randomly select source node and destination node to perform experiment with A-Star and Best First Search algorithm. If obstacle is selected then source node and destination nodes will be randomly selected on two sides of obstacle.

8.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/cd571086-b5a5-408a-9ed3-5f335e2688c7)
Press A-star button to execute A-Star algorithm on selected source and destination nodes. It plots a path between source and destination.
9.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/0a5459ef-74e2-4735-b04f-7c45afad51c0)
Press BstFst button to execute Best First Search algorithm on selected source and destination nodes. It plots a path between source and destination.

10.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/bd9c9a32-dc0a-421d-b65f-71ac62544f33)
Enter the value between 0 and 100 to specify the size of an obstacle as a percentage of the screen when checkbox is selected(11). 

11.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/6c6078bd-9167-4546-acfa-041a268209a4)
Select the checkbox to draw an obstacle as specified in textbox in (10). An obstacle coordinates are stored in PolyList.txt file.

12.  ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/01a90c87-07a2-4c7b-986e-a72e0630650e)
Enter the number of experiments you want to carry out for chosen configuration of nodes. It will start when Save button in (13) is pressed.

13.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/98e92165-a70f-4c68-8344-148dc5868808)
Press Save button to executed large number of experiments and save its output. It creates two files namely Experiments.txt and Parameters.txt files. 

14.  ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/bcba653c-a181-483f-92d1-cf9ae107eabe)
Press Load button to display saved configuration of nodes and obstacle. It reads Parameters.txt and displays the saved configuration.

15.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/e441949e-9386-4dbb-aade-c5ce5f1c63dd)
Press Analysis button to see generated results after Save is pressed. It  displays (source,destination) node pair in combo-box from Experiments.txt file. This pair of nodes are those nodes whose number of intermediate node in A-Star output is less than Best First search output.

16.   ![image](https://github.com/hsmazumdar/NetSim/assets/16040087/c4aa2357-b98c-4edf-b215-8e175ea5b5c9)
Combo-box displays the result of experiment carried out and stored in Experiments.txt file. It displays source, destination node pair when Analysis button is pressed. It displays path between source and destination for both A-Star and Best First Search algorithm when a specific pair is selected from combo-box list. It displays on those pairs in which A-Star executes with fewer intermediate nodes than Best First Search.

