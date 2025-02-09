**Senior Design Competition, Western University London**,


 	In this competition, teams were tasked with designing and building an RC rover in an 8 hour time frame, using a set of materials and electronics provided. The goal was to create a robot that could traverse an obstacle course, pick up magnetic material from a height of 5 cm, and deposit it at a base station 10 cm above the ground. Built Rover can be seen in Figure 1
  
Throughout the competition, my team followed an iterative design process. Initially, we considered using an arm to collect and dispose of the magnetic material, but we debated whether a spool mechanism would be better. I argued that, given the low operating torque of the motor, the electromagnet would be too heavy, especially with a long moment arm. I suggested using a spool and motor system to pull the arm up with a fishing line to eliminate the moment force, allowing the system to operate with pure tension. However, our team ultimately decided to go with the arm design, thinking it would be simpler to implement given the time constraint. See Figure 2 to see the designed model on Solidworks before implementation.
   
My primary contribution to the project involved handling the electronics and coding. Given my greater experience in these areas compared to my other team members, I was responsible for troubleshooting the electromagnet, relay, infrared sensor/remote, and distributing power. I had to configure a variety of hardware, but the most tedious task was configuring the infrared sensor and remote. I individually configured each button on the remote by checking the signal each button emitted on the serial monitor. I then assigned functions to each button in the code based on the signal of each button. Each button had a specific task, such as slowing down the motors for speed control, lifting the arm, providing voltage to a relay to turn the electromagnet on/off, and performing other functions. Additionally, I worked on distributing power to the electronics to ensure the system functioned properly, as shown in Figure 2.
   
During testing, we initially couldn't even lift the arm due to the long moment arm. To resolve this, we shortened the moment arm and raised the motor height until we achieved the required minimum 10 cm height elevation with the arm. Even with this modification we experienced issues with the arm shaking and struggling to hit its full range of motion during the competition presentations. Although this is true, we were still able to pick up most of the magnetic material and traverse the obstacle course using our infrared sensor remote. With this accomplishment we were able to place third place in this competition. This challenge taught me to step outside my comfort zone. We feared implementing the spool system because it is a more complex system and we only had a limited amount of time to build this rover. In hindsight, trying the spool design might have solved some of the problems we faced. Ultimately, we secured third place in the competition, but the experience emphasized the importance of iterating, testing, and pushing the boundaries of our initial ideas.

 
 ![image](https://github.com/user-attachments/assets/0db44a9d-95c2-492a-bbcb-b29400dc7252)

_Figure 1_
   

<img width="434" alt="image" src="https://github.com/user-attachments/assets/68ef0a07-4962-4fde-b475-21b281bd7443" />

_Figure 2_


![image](https://github.com/user-attachments/assets/973b3f14-25c1-432e-8a3f-0fdf0e6337a3)

_Figure 3_



    
    
