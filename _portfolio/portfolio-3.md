---
title: "Wood Bending Machine: A Mechatronic Solution for Curved Wood Bending (24-354)"
excerpt: "A mechatronic system designed to bend soaked wood into complex shapes, offering an affordable solution for designers and craftsmen. <br/><img src='/images/WoodBendingMachine.png'>"
collection: portfolio
---

---


### The Wood Designer: Automating Your Curves, One Bend at a Time! 
**Course:** Mechatronics Applications in Mechanical Engineering (24-354)  
**Team Role:** Controls and Force Measurement Integration Lead  
**CMU Mechanical Engineering | Fall 2023**

### Introduction  
In response to the rise of organic, curved designs in architecture and furniture design, our team developed a wood bending machine capable of transforming soaked wood into complex shapes. The goal was to provide a low-cost, accessible solution for designers and craftsmen who seek to replicate industry-grade curves without the cost or complexity of industrial bending systems. Our solution would essentially bridge the gap between engineering design and architectural intent in wood bending.

### Design Approach  
The system integrates two heavy-duty Actuonix linear actuators, load cells for force feedback, and a PID-controlled motor (drives 1/8-inch thick wooden planks up to 20 inches long) at multiple contact points. The structure was laser-cut from acrylic and reinforced with 3D printed brackets and clamps, creating a lightweight yet robust enclosure. Bending is achieved by soaking wood in 150°F water, clamping it at three points, and actuating the device through calibrated position commands.


<br/><img src='/images/loadcelll.png' alt="System View">

**Figure 1:** Load Cell incorporated in clamping mechanism

### Results & Evaluation  
- **Max Bend Achieved:** 5.12 inches of vertical deflection  
- **Cycle Time:** Under 40 seconds per test  
- **Precision:** ±10 mm accuracy in actuator travel  
- **Force Tracking:** Load cells enabled real-time monitoring of bending stress  
- **Safety & Stability:** Dual-clamp design with structural rigidity maintained  

Despite budget constraints and hardware setbacks (e.g., Linear Actuator Control (LAC) board failures, noisy load cell signals, and PID issues), the system met all but two technical goals — falling slightly short of a 90° bend and $300 cost cap. These gaps were mitigated by successful reengineering of the control circuit using L298N drivers and manually soldered PCB connections.

### Impact & Future Work  
This machine offers a unique blend of affordability and engineering precision for educational settings, design studios, and small workshops. Compared to $30,000 industrial wood benders, our ~$445 prototype demonstrates that fine-curved craftsmanship can be democratized and made readily available given a few mechatronic components. With further iteration, the device could support adaptive clamping, precisely tuned multi-axis motion, and computer vision, bringing sculptural woodworking within reach of hobbyists and makers.


<br/><img src='/images/woodbendiung.png' alt="System View">

**Figure 2:** A Comprehensive View of the Wood Bending System  

---


<br/><img src='/images/wood_bend_schematic.png' alt="System View">

**Figure 3:** Circuitry Schematic of System including Actuonix Motors and Load Cells  

---
 

<br/><img src='/images/IMG_2426.png' alt="System View">

**Figure 4:** Side angle view of layout   

### Real-time wood deformation with PID tuning
[![Your Video Title](https://your-image-host.com/your-thumbnail.jpg)](https://www.youtube.com/watch?v=Uxw91of9tSk)


