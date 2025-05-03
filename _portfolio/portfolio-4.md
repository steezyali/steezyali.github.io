---
title: "PosChair: Posture Sensing and Correction Device (24-441)"
excerpt: "Proof of concept product that can detect posture, make users aware of their posture, and correct that behavior for people seated at a desk. <br/><img src='/images/POSCHAIR.png'>"
collection: portfolio
---

---
### PosChair: Posture Sensing and Correction Device  
***Course:*** Mechatronics Design Engineer (24-441)  
***Team Role:*** Controls and Force Measurement Integration Lead  
***CMU Mechanical Engineering | Fall 2022***

### Introduction  
From our extensive customer and market research, posture-related health issues, such as back pain and discomfort, are increasingly common among individuals who spend long hours seated at desks. Aiming to tackle this issue, our team designed PosChair, a device that directly senses posture deviations and provides corrective feedback to improve seated posture, all non-invasively. By integrating multiple sensors, including infrared (IR) sensors for back position and load cells for weight distribution, our product provides real-time feedback to help users adjust their seating position in a myriad of seated environments. This project was forged from the team’s desire to offer a low-cost, effective solution for office workers, students, and anyone in need of posture correction.

### Design Approach  
Posture-related health issues, such as back pain and discomfort, are increasingly common among individuals who spend long hours seated at desks. Aiming to tackle this issue, our team designed PosChair, a device that senses posture deviations and provides corrective feedback to improve seated posture. By integrating multiple sensors, including infrared (IR) sensors for back position and load cells for weight distribution, PosChair provides real-time feedback to help users adjust their seating position. This project was born out of a desire to offer a low-cost, effective solution for office workers, students, and anyone in need of posture correction


<br/><img src='/images/final cad rended or entire product.png' alt="System View">

**Figure 1:**  CAD Render of Entire Product

### My Contribution

My core role in this project was to lead the Infrared Proximity Sensor implementation within the seat design. This involved mounting three Sharp GP2Y0A41SK0F sensors onto a vertical frame that would be embedded within the back-cushions of the seat. I calibrated and de-noised the sensor readings with simple rolling averages, which succesfully allowed the team to measure the distance between a chare back cushion and a seated person's back with a consistent error of 2-3 cm. This implementation allowed me to simulate the user's back angle posture via horizontal distance measurements and calculate angles that can dictate poor posture. This electronic setup was also connected to the vibration sensors, signalling vibrations in the bottom cushion when certain distance thresholds were violated.

### Results & Evaluation  
- **Sensing Accuracy:** IR sensors achieved an error margin of 2 cm, ensuring precise back angle measurement.  
- **Load Cell Sensitivity:** Successfully mapped pressure distribution, with a maximum weight detection of 110 lbs per cell.  
- **Feedback Effectiveness:** Vibration feedback was effective in alerting users of poor posture, with customizable intensity levels for different postural deviations.  
- **User Comfort:** The product met comfort ratings of 8-10/10, with minimal intrusion into the user's daily routine.  
- **System Integration:** All subsystems (sensing, feedback, and interface) were successfully integrated and tested in tandem, ensuring seamless user interaction.

Despite challenges in sensor calibration and integration, including the adjustment of load cells and fine-tuning the motor feedback, the product successfully met its functional goals.

### Impact & Future Work  
PosChair offers a strategic approach in addressing multiple areas of the body and providing continuous feedback. Compared to existing market solutions, such as wearable posture devices or expensive ergonomic chairs, PosChair stands out due to its comprehensive feedback system, affordability (approximately $275), and ease of setup. Future iterations could include enhancements like adaptive feedback, additional sensor calibration, and wireless connectivity for data tracking. With further refinement, PosChair could be a valuable tool for individuals seeking long-term posture improvement. Within the project, a more defined machine learning design could be implemented that could collect data from the user and predict their future movements all based off the infrared distance and vibration distribution readings. Signal processing methods such as Savitsky-Golay and Low-Pass filters can also be used to reduce unnecessary noise and anomalies within the output sensor data.


<br/><img src='/images/Poschair OVerview.png' alt="System View">

**Figure 2:** Design Overview


<br/><img src='/images/poschair circuit.png' alt="System View">

**Figure 3:** Circuitry Schematic of System Infrared and Vibration Sensors  

---

### Presentation  
