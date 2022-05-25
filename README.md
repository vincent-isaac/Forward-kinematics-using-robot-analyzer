# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles.

### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values with the link lenght wherever necessary.
4. simulate the model for forward kinematics.
5. plot the graph between the link and the joints.
6. update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 

#### Screenshot

#### 6 DOF
![Capture39](https://user-images.githubusercontent.com/75234588/170179004-4bee09d6-661e-4bda-8e8c-9b40e5ab58f4.PNG)

#### 4 DOF
![Screenshot (84)](https://user-images.githubusercontent.com/75234588/170179125-213fc2c4-926d-47f2-b15f-7c1f39083360.png)

### PLOT 
 
#### 6 DOF

![Capture38](https://user-images.githubusercontent.com/75234588/170178987-30505364-41cb-4e70-823d-056eabcdf500.PNG)

![Capture37](https://user-images.githubusercontent.com/75234588/170178997-d2957217-7a21-42d1-bf5e-70c0f9731d92.PNG)



#### 4 DOF
![Screenshot (86)](https://user-images.githubusercontent.com/75234588/170179149-e49a2204-5177-46ab-8e4c-a1a08b93b94d.png)

![Screenshot (88)](https://user-images.githubusercontent.com/75234588/170179475-678582f0-bf73-49e5-ac6c-5fb749227815.png)

### RESULTS : 
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
