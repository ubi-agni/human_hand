Pisa Hand Model
===============

To use the Pisa URDF model of the hand, copy the pisa_hand_description and pisa_hand_publisher folders into your catkin_ws and launch "roslaunch pisa_hand_description display.launch" through the terminal.

You can select the visual mode, modifying the line #6 in pisa_hand_description/launch/display.launch, choosing among :

<arg name="use_joint_state_publisher" default="false"/> : in this mode, the model hand has 18 dof (15 dofs for the hand plus 3 dofs of the wrist) [Santello et al. 1998]. You can visualize the angles data that are written in "data.txt" (which can be modified; please remember that the number of columnes must be 15 and the number of rows must be equal to variable "campioni" at line #39 in pisa_hand_publisher/src/pisa_hand_publisher.cpp). The angles are expressed in rad.

<arg name="use_joint_state_publisher" default="true"/> : in this mode, the model hand has 23 dofs, i.e. the 15 dof model plus the distal joint angles and middle abduction, and you have a GUI, where you can modify the value of each hand joint as you prefer. The angles are expressed in rad.


For further information, please email to : r.nuti@hotmail.it; matteo.bianchi@centropiaggio.unipi.it; e.battaglia@centropiaggio.unipi.it