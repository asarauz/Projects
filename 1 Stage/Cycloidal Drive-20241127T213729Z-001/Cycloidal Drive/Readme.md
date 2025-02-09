**Cycloidal Gearbox - First Iteration (14:1 Gear Ratio):**
This cycloidal gearbox is part of the design for the elbow joint of a Mars rover developed by the club We Mars at Western University. The goal is to create a compact, efficient gearbox that can handle the unique demands of the rover’s arm, ensuring smooth and reliable movement in the challenging conditions of space exploration. This first iteration focuses on achieving a 14:1 gear ratio, optimizing torque and minimizing friction for the rover’s elbow joint.
This cycloidal drive was designed with a 14:1 gear ratio using barrel screws as output shaft pins. A cycloidal gearbox operates by converting rotary motion into an output with a very smooth, precise motion that offers higher torque output and less backlash compared to traditional gear systems. The drive is composed of a cycloidal disk, which is rotated by a set of rollers that follow a cycloidal path. As the disk turns, the rollers move along the edges and transmit motion to the output shaft through its output pins.

**Working Principle:**
In a cycloidal drive, the output shaft is driven by the pins that roll on a cycloidal disk, which is created using parametric equations. This design typically uses an eccentric shaft to allow the rollers to follow the correct path and transmit motion efficiently. The number of rollers, the eccentric offset, and the radii of the rotor and rollers are key parameters that have to be chosen carefully in order to obtain a functioning disk.

**Gear Ratio:**
For this particular design, a 14:1 gear ratio was achieved. This was achieved by carefully designing the geometry of the cycloidal disk to interact with the rollers in a way that reduces the mechanical stress and optimizes torque transmission.

The design uses the following parametric equations for the cycloidal path:

X(t) = (Rcos(t)) - (Rrcos(t + arctan(sin((1-N)t)/((R/EN) - cos((1-N)t)))))-(Ecos(Nt))

Y(t) = (-Rsin(t)) + (Rrsin(t + arctan(sin((1-N)t)/((R/EN) - cos((1-N)t))))) + (Esin(Nt))

Where:

R = Rotor radius (1.75 inches)

Rr = Roller radius (0.25 inches)

E = Eccentric offset (0.075 inches)

N = Number of rollers (15)

**Design Challenges:**
One of the biggest challenges was the need for an eccentric shaft or bearings to ensure the rollers track the correct path. Due to manufacturing limitations, an eccentric shaft wasn't feasible, so we opted for using eccentric sleeves and spacers that are being custom-manufactured. The eccentric shaft would have allowed the rollers to maintain a precise distance from the center, ensuring the drive operates smoothly without excess friction..
In conclusion, this first iteration of the cycloidal gearbox offers a compact, efficient design with good torque characteristics, but some adjustments in manufacturing are required to achieve the desired precision. 

Furthermore, this was just a first iteration design where we underestimated the amount of torque required in order to move the elbow joint of the mars rover. Hence we need a more optimal gearbox which includes PTFE washer spacers for lower friction between the cycloidal disk and the output disk. Furthermore we need to add another cycloidal disk in order to reduce vibrations due to the eccentric rotation from a single disk. This is all done in the second iteration of our gearbox.


**Assembly**

<img width="450" alt="image" src="https://github.com/user-attachments/assets/77cc066d-f979-4ece-90e6-ffee889bd460" />

**Motion Study**

[![Watch the video](https://img.youtube.com/vi/p2H8cW7Wuto/0.jpg)](https://youtu.be/p2H8cW7Wuto)

