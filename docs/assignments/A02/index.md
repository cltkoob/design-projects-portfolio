# A2 – Truss Stress Analysis

## Objectives
-Design a lightweight planar truss using A500 steel or an alternative material.
-Create free body diagrams (FBDs) for joints and critical pins.
-Calculate the required cross-sectional area of truss elements with a safety factor.
-Determine pin sizes based on shear forces with a safety factor.
-Solve equations symbolically and numerically for both truss and pin design.
-Estimate the total weight of the truss and pins.
-Create a CAD model with accurate dimensions and connections.
-Compare CAD weight predictions with hand calculations.
-Document key engineering lessons learned from the process.
 
## Communicate
For my first step, the design, I went with a 7 member symmetrical truss that utilizes 5 pins at every connection to maximize sturdiness. The lengths are a = 0.4m and b = 0.3m with a force (P) of 30kn, which was my choice. After that, I started solving for the internal forces using the equations of equilibrium and sum of moments and forces. I decided to go with the Method of Joints to solve for the forces in the joints. I stared with Joint B and worked my way through: A , C , and E. 

![Internal Forces](handcalc1.jpeg)
![Internal Forces](handcalc2.jpeg)

After I had complete the internal forces, it was time to take the largest internal force which was 24.09kN, and use that to calculate the minimum area. I listed all of my knowns and unknowns and using a factor of safety of 3.5, I found the minimum area to be 0.00026397m^2 (265.97mm^2). After that, I found the combined weight of 7 member that I was going to be using with the formula w = mg and I got w = 67.05N.

![Calculations](handcalc3.jpeg)

Moving on from the truss calculations, I focused on the details of the pins that I would be using. I listed the knowns and unknowns and used a factor of safety of 4. Using FOS * V / yield strength, I was able to calculate the minimum area and then use the formula 
A = pi*d^2 / 4 to find the diameter. 

For my CAD drawing, I started out with a perimeter of the truss using the given dimensions of the members.
