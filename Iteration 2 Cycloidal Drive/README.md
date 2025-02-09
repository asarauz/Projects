**Cycloidal Gearbox - Second and Final Iteration**

After performing torque calculations and considering the requirements of the elbow joint on the Mars rover, we realized that the initial gearbox design needed more torque to handle the load. The system would be using a Neo Vortex brushless DC motor, which has a 3.6 Nm stall torque and an operating range just under 2 Nm. Since the motor would not be continuously running but rather operating in short intervals, we could utilize the motor in its intermittent range. However, we still needed to increase the torque to meet the demands of moving about 10 kg of weight.

To address this, we redesigned the gearbox to achieve a higher gear ratio of 29:1, which would provide the required torque. Instead of using barrel screws for the output shaft, we switched to regular countersunk screws, paired with a nut and spacer for the output pin. We also introduced PTFE spacers between the two cycloidal disks, as well as between the output disk and the casing to reduce friction and ensure smooth operation.

One of the key changes was the addition of a second cycloidal disk, which is positioned exactly 180 degrees out of phase with the first one. This modification helps to reduce vibrations, providing more stability and precision in the movement of the elbow joint.

The updated parametric equations for this new design are as follows:

N = 31
R = 1.75 inches
Rr = 0.125 inches
E = 0.05 inches
Parametric Equations:
X(t) = (Rcos(t)) - (Rrcos(t + arctan(sin((1-N)t)/((R/EN)-cos((1-N)t)))))-(Ecos(Nt))
Y(t) = (-Rsin(t)) + (Rrsin(t + arctan(sin((1-N)t)/((R/EN)-cos((1-N)t))))) + (Esin(Nt))
For the updated design:

X(t) = (1.75cos(t)) - (0.125cos(t + arctan(sin((1-31)t)/((1.129)-cos((1-31)t)))))-(0.05cos(31t))
Y(t) = (-1.75sin(t)) + (0.125sin(t + arctan(sin((1-31)t)/((1.129)-cos((1-31)t))))) + (0.05sin(31t))
These adjustments to the gearbox design allow us to better meet the torque requirements while also improving the overall performance of the elbow joint system. The increased gear ratio and the addition of the second cycloidal disk ensure that the rover’s arm can operate more smoothly, even under heavier loads.

<img width="342" alt="image" src="https://github.com/user-attachments/assets/4c23f4f3-d01a-423e-a365-b6546df3aa52" />


<img width="478" alt="image" src="https://github.com/user-attachments/assets/aefe267f-59b1-47b3-8715-3d9a997f93b4" />


<img width="470" alt="image" src="https://github.com/user-attachments/assets/abd8ac35-4065-4b79-ab11-0e2c41774cc5" />



