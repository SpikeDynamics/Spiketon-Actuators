# Amplified Linear Actuator Spike AA1

<img src="images/Spiketon T1.png" alt="Guided Spiketon T1" width="400">
AA1 is a lightweight Amplified Actuator for moving the tip of the actuator up to 0.5mm-1mm with a pushing force up to 1000N and high frequency. It can be used as a standalone product or as part of a more complex product (such as Spiketon).

## What AA1 Is For

The purpose of the AA1 is to amplify the oscillations of a piezo stack within a compact volume.
 If the amplification ratio is 10, then with piezo stack vibrations of 100 microns, the AA1 produces oscillations in the same direction of about 1 mm.
 Since levers are involved, the generated force decreases proportionally. However, the compactness of this device is unprecedented.
There are amplified actuators worldwide designed for the same purpose, but they are typically bulky and heavy.

## AA1 Structure

The AA1 consists of several parts.
 Two identical metal plates are placed at the top and bottom. They include all the required links and levers for proper operation.
 Each plate has three pairs of holes on its support pads — used for joining with pins, bolts, or rivets. 
 Although the plates are identical, they are positioned so that the long linkages are on opposite sides.
Between the support pads, thick metal shims are placed. These can be spot-welded, in which case the pairs of holes are not needed.
 A piezo stack is mounted between the middle and the far support pads.
 The whole structure has a bit of spring compliance, so the piezo stack is securely held by elastic force.

## How It Works

Typically, a piezo stack can increase its length by about 0.1%.
 You may find the movements on the video. The acting forces are shown with arrows.
 When the piezo stack changes its height slightly, the overall height of the device changes by roughly an order of magnitude more (≈1%).
In the accompanying FEA (Finite Element Analysis) simulation, the deformations appear exaggerated — this is a standard visualization mode in SolidWorks, which was used for modeling.
 The same analysis can be performed using other CAD tools such as Autodesk Fusion 360 or Ansys.

## Why Compact Amplified Actuators Matter

Why is it so important to make a compact amplified actuator?
 Because it moves the system from the micron range into the millimeter range.
 Micron-scale mechanisms require extremely precise parts and expensive manufacturing equipment.
 By shifting the motion range to millimeters, the product becomes suitable for mass production with simpler processes and lower precision requirements. This may drastically reduce the cost.
Another consequence: this transition moves the actuator out of the high-cost, ultra-precise, ultra-slow market segment and into the affordable, high-speed market.
 This makes it possible to achieve much higher motion speeds while maintaining excellent precision and repeatability.

## Application in the Modified M1

We used AA1  to create a modified version of the M1 actuator (see figure).
What’s interesting about the result?
 Because each step of the actuator is now 10× longer, we gained the ability to increase the linear motion speed by a factor of 10.
The trade-off is a reduced maximum generated force.
 To compensate, the cross-sectional area of the piezo stack must be increased roughly 10×.
During M1 operation, the ends of its legs follow an elliptical trajectory.
 The ellipse dimensions are determined by the motion of the central section (the body of the actuator) and the front/rear sections (the clamps or jaws).
Previously, the M1 step size was too small to use toothed rails — the distance between teeth was bigger than the step. By other words, teeth were to small to be properly implemented. 

 Now, with an amplified actuator in the central section, the design allows the use of teeth (see figure).
In this new M1 modification, the carriage legs are held not by friction but by mechanical interlocking with teeth, which provides maximum holding force for configurations using larger piezo stacks and higher forces.
The factor of 10 in this description is just an example — real projects may require higher or lower amplification ratios.

  
