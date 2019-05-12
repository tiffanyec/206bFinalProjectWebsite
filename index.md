## Project Overview

The goal of our project was to have a multifingered robotic hand be able to reshape a soft object into a desired shape. This functionality could be utilized in industries where soft and malleable objects need to be reshaped consistently or in places where the object needing to be reshaped could consist of potentially harmful chemicals or materials and a human could potentially be exposed to danger or harm. Replacing the human with a robotic arm capable of performing the same task would decrease the risk of a person getting harmed while also increasing the consistency of the reshaping. Some examples of industries in which this could be utilized include the food processing industry, biomedical processing, and robotized surgery. 

<img src="images/image28.png" style="width: 50%; display: block; margin: auto;" />

## Implementation

We formulated our problem as having a soft object (in our case a ball of dough) in an initial shape and having some desired end shape that we want the robot to mold the object into. To do this, our main problem for the project was for the robot to find the amount of force it needs to apply in order to achieve the goal shape.

<img src="images/problemStatement.png" style="width: 60%; display: block; margin: auto;" />

For our project, we used a 4 DOF BarrettHand BH8-282 implented with ROS, a 6 DOF Robot Arm (FANUC LRMate 200iD/7L) implemented with MATLAB, and 2 cameras (Ensenso N35) implented with MATLAB. 

<img src="images/image33.png" style="width: 50%; display: block; margin: auto;" />

We broke up our project into two stages: the teaching stage and the testing stage. In the teaching stage, the soft object begins in some initial shape and the robot applies some force F on it to reshape it. A point cloud of the objects new shape is then obtained to observe what applying the force did to reshape the object. In the testing tage, the robot is given a desired shape that we wish the soft object to become. It then calculates a rigid body transformation using the point clouds obtained in the teaching stage in order to find the force needed it needs to apply in order to reshape the object into the goal shape. 

<img src="images/stages.png" style="width: 60%; display: block; margin: auto;" />

## Results
<iframe width="560" height="315" src="https://www.youtube.com/embed/knuFI5SsM_Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div style="text-align: center;">
  <img src="images/image24.png" style="width: 30%;" /><img src="images/image23.png" style="width: 30%;" />
</div>

<div style="text-align: center;">
  <img src="images/image31.png" style="width: 30%;" /><img src="images/image32.png" style="width: 30%;" />
</div>

## Conclusion


## Team Bios

### Xinghao Zhu 

### Guangzhao Yang 

### Ting Xu 

### Tiffany Cappellari

