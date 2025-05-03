---
title: "Falcon-Inspired Robotic Glider with Multi-Joint Wing Morphing (24-775)"
excerpt: "A bio-inspired robotic glider designed to mimic the peregrine falcon’s wing dynamics with a multi-joint morphing wing system for improved diving speed and vibration reduction. <br/><img src='/images/FalconGlider.png'>"
collection: portfolio
---

---

### Falcon-Inspired Robotic Glider with Multi-Joint Wing Morphing  
**Course:** Bio-Inspired Robot Design and Experimentations (24-775)  
**Team Role:** Electronics Design and Sensor Data Logging Lead  
**Carnegie Mellon University | Fall 2024**

### Introduction  
Since the Wright Brothers invented the first lighter-than-air aircraft in the early 1900s, aerial engineering has evolved to enhance the performance of aircraft, particularly in diving speed and vibration management. Deeply inspired by the peregrine falcon's wing shaping mechanism, this project aimed to design and evaluate a two-joint variable-sweep wing system. The goal was to investigate whether this system could outperform traditional fixed-wing and single-joint variable-sweep designs in terms of both diving speed and vibration reduction. The ablation studies hypothesized that a two-joint wing system, mimicking the falcon's natural wing morphing during flight, would improve these key performance indicators for unmanned aerial vehicles.

### Design Approach  
The design implementation featured a two-joint wing system, capable of zero joint actuation (standard fixed-wing), single joint actuation, and double joint actuation. The NACA 2412 airfoil profile was selected for its proven aerodynamic efficiency. The wing assembly included five components: two outer wings, two inner wings, and a base wing, with design considerations aimed at weight reduction without sacrificing structural integrity. The morphing design was powered by a torsional spring and servo-connected spool system. The spring allowed planar rotation while the servo-spool enabled the wings to adjust during flight. The assembly was fabricated using 3D printing technology and covered with a transparent cellophane sheet for aerodynamic performance.


<br/><img src='/images/FalconWingCAD.png' alt="System View">

**Figure 1:** CAD Rendering of Wing Configurations

### Contribution

My core role in this project was to lead the electronic design and data analysis;
This involved the following:

- **Sensor Integration:** Integrated barometer (BMP390), SD Card Data Logger, Vibration Sensors, Servo Motor and Battery Power
- **Vibration & Altitude Performance:** I was able to calculate tangential velocity using our testbed landing locations and altitude (barometer) sensor readings.  I applied the Savtisky-Golay filter to the vibration datasets and used altitude

<br/><img src='/images/flycirc' alt="System View">

**Figure 1:** CAD Rendering of Wing Configurations

### Results & Evaluation  
- **Speed Performance:** Double-joint wings achieved the highest average speed of 5.29 m/s, compared to single-joint (~4.46 m/s) and fixed wings (~1.36 m/s)
- **Vibration Performance:** Double-joint wings exhibited the highest average vibration levels, followed by single-joint wings, and fixed wings. While the double-joint configuration did not reduce vibrations as hypothesized, it significantly outperformed the fixed-wing in terms of speed.  
- **Statistical Analysis:** Using t-tests and noisy filtering methods (Savistky-Golay and Rolling Average filters), significant differences were found in velocities across all configurations, with double-joint wings showing a clear advantage. Vibrational data showed no significant difference between single and double-joint configurations, suggesting that further optimization of the wing morphing system may be needed to 

Despite these challenges, the project provided valuable insights into wing morphing systems, proving that multi-joint wings can increase speed without significantly compromising structural stability.

### Impact & Future Work  
This work contributes to the ongoing development of bio-inspired aerial robotics, opening new possibilities for wing morphing technologies in UAVs. While double-joint wings demonstrated higher speeds, further refinement is needed to address the vibration issue. Future iterations will focus on improving vibration suppression and exploring alternative actuation mechanisms for better control and stability. Additionally, real-time feedback mechanisms could be integrated into the system for more adaptive morphing during different flight regimes. Aside from additional design improvements, the project can also feature more data processing features that are geared towards improving more accurate data logging. Signal processing methods, such as the Kalman Filter, Fourier Transform, Wavelets and Low-Pass filtering, can help reduce system noise introduced via human error and predict three dimensional trajectories, allowing for greater analysis into the differences between double and zero joint configurations. It would also be great to simulate flight conditions in a flight simulator or wind tunnel for manual atmospheric conditions, damage reduction during flight and more controlled testing parameters. 
 

<br/><img src='/images/FalconWingPrototype.png' alt="System View">

**Figure 2:** Prototype Wing Assembly



---

<br/><img src='/images/poster_bioinspired.png'>

###  Check out this fun video my team made!

[![Your Video Title](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=sQKwbzWWPtY)





