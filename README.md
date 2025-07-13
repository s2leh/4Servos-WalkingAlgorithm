# Overview
This project consists of two tasks:

Controlling Servo Motors using Arduino (Code to control servo motors attached to pins 6, 7, 8, and 9).

Humanoid Robot Walking Algorithm to simulate the walking process of a humanoid robot.

# Task 1: Servo Motors Control
Description
This task involves controlling four servo motors using an Arduino. The servo motors are connected to pins 6, 7, 8, and 9 on the Arduino board. The code moves the servos back and forth through a 180-degree sweep, with a slight delay in each step. After the sweep, the servos are moved to a neutral 90-degree position and held there.

# Task 2: Humanoid Robot Walking Algorithm
Description
This algorithm simulates the walking process of a humanoid robot. The walking motion is broken down into a series of steps, where each leg alternately moves forward, with the weight shifting from one leg to the other to maintain balance.

# Algorithm Steps:
1. Shift Weight to Left Leg

Right knee bends slightly to lift the right foot.

Left leg remains straight to support weight.

Hips tilt slightly to the left for balance.

2. Swing Right Leg Forward

Right hip rotates forward.

Right knee lifts to clear the ground.

Left leg holds firm.

3. Plant Right Foot

Right knee straightens to touch the ground.

Right hip adjusts to neutral.

4. Shift Weight to Right Leg

Left knee bends to lift the left foot.

Right leg straightens to support weight.

Hips tilt to the right.

5. Swing Left Leg Forward

Left hip rotates forward.

Left knee lifts.

Right leg holds firm.

6. Plant Left Foot

Left knee straightens.

Left hip returns to neutral.

7. Repeat Cycle

Return to Step 1 for continuous walking.

