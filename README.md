# Turtlesim-Ros1
Manipulate with turtlesim package in ROS noetic

### Manipulate with turtlesim package in ROS noetic
1. Open a terminal and start roscore:
     ```bash
     roscore
     ```
     ![image](https://github.com/user-attachments/assets/733ea77e-f5a1-4be5-b95a-fecf65e5ced1)
2. install the turtlesim package:
     ```bash
     sudo apt-get install ros-noetic-turtlesim
     ```

3. Run the turtlesim node:
     ```bash
     rosrun turtlesim turtlesim_node
     ```
     ![image](https://github.com/user-attachments/assets/0cc0722f-287b-406a-92aa-0c91e010a723)

4. Draw a Square:
   - Open another terminal and run the following command to control the turtle and draw a square:
     ```bash
     rosrun turtlesim draw_square
     ```
     ![image](https://github.com/user-attachments/assets/a9c6d83d-8c05-482e-ab10-13818b3aecaf)

5. Launch rqt_graph:
   ```bash
     rosrun rqt_graph rqt_graph
     ```
   ![image](https://github.com/user-attachments/assets/4bf34e7c-b4a6-48f1-b0fb-0a2f241026a6)


6. Change the background color:
   ```bash
     rosparam set /turtlesim/background_r 150
     ```
   ![image](https://github.com/user-attachments/assets/0ea1225a-02b9-43c8-930c-b31d89f1b534)

7. Turtle keyboard teleoperation:
   - use the arrow keys of the keyboard to drive the turtle around
    ```bash
     rosrun turtlesim turtle_teleop_key
     ```
    ![image](https://github.com/user-attachments/assets/1380addb-1cbc-4c52-a52f-06b0c9b000b0)


# Learning Resources:
- https://www.youtube.com/watch?v=mwgiYzZZtCs&t=87s
- https://wiki.ros.org/ROS/Tutorials/UnderstandingTopics
  

   
   


   

     

     
