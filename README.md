[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/AlBFWSQg)

# a14g-final-submission

    * Team Number:24
    * Team Name:IDK
    * Team Members:Zhongkun Xue,Yanzhao Wang
    * Github Repository URL:https://github.com/ese5160/a14g-final-submission-s25-t24-idk.git
    * Description of test hardware: development boards, sensors, actuators, laptop + OS, etc

## 1. Video Presentation



## 2. Project Summary


Device Description


Device Functionality


Challenges



Prototype Learnings


Next Steps & Takeaways


Project Links




## 3. Hardware & Software Requirements



Hardware Requirements Specification (HRS)


| **Requirement ID** | **Requirement Description**                                                                         | **Performance Metric**              | Achievement |
| ------------------------ | --------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ----------- |
| HRS 01                   | The system shall use the ICM-20948 sensorfor 9-axis motion tracking.                                      | Sensor data sampled at up to 1.1 kHz.     |             |
| HRS 02                   | The system shall display metrics in real-time using the ST7735R LCD.                                     | Display refresh rate ≥ 30 FPS.           |             |
| HRS 03                   | The system shall use the SAMW25 microcontroller to manage data processing and Wi-Fi communication.       | Data transmission latency ≤ 100 ms.      |             |
| HRS 04                   | The hardware shall be powered by a single-cell Li-Ion battery(3.7V nominal voltage).                     | Battery life ≥ 4 hours.                  |             |
| HRS 05                   | All components shall be integrated into a custom PCB for compact and portable design.                     | PCB dimensions ≤ 500x500 mm.             |             |
| HRS 06                   | The system shall include Wi-Fi functionality for data transmission via the SAMW25.                        | Wi-Fi range ≥ 10 meters indoors.         |             |
| HRS 07                   | The hardware shall include an SD card slot for data storage and retrieval.                               | Data write speed ≥ 3 MB/s.              |             |
| HRS 08                   | The system shall include a switch button to pause sensor recording and activate review mode on the LCD.  | Button response time ≤ 100 ms.           |             |
| HRS 09                   | The PCB shall include appropriate voltage regulators to provide 3.3V and 5V as needed for all components. | Voltage output variation ≤ ±0.1V.       |             |
| HRS 10                   | The hardware shall withstand typical tennis swings without detachment or damage.                          | Withstand forces up to 300g acceleration. |             |


HOW to measure


Software Requirements Specification (SRS)


| **Requirement ID** | **Functionality Description**                                                                         | **Performance Metric**               | Achievement |
| ------------------------ | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------ | ----------- |
| SRS 01                   | The system shall collect and process motion data from the ICM-20948 sensor.                                 | Data processing within 100 ms.             |             |
| SRS 02                   | The software shall display real-time metrics and trajectory simulations on the ST7735R LCD.                 | Metrics updated at 30 FPS.                 |             |
| SRS 03                   | The system shall pause data recording and display the last recorded data when the switch button is pressed. | Pause functionality response ≤ 100 ms.    |             |
| SRS 04                   | The software shall store swing data on an SD card for later retrieval.                                      | Write speed ≥ 5 MB/s.                     |             |
| SRS 05                   | The system shall transmit processed data wirelessly using the SAMW25 microcontroller.                       | Wi-Fi latency ≤ 100 ms.                  |             |
| SRS 06                   | The software shall retrieve and display previously stored swing data from the SD card.                      | Data retrieval within 200 ms.              |             |
| SRS 07                   | The software shall indicate system status via the LCD.                                                      | LCD updates within 1 second.               |             |
| SRS 08                   | The software shall simulate the simple swing trajectory on LCD after click the button.                     | LCD update the trajectory within 3 second |             |
| SRS 09                   | The computer software shall simulate the 3D version of swing trajectory.                                  | Simulation within 1 mins                   |             |



HOW to measure



## 4. Project Photos & Screenshots


*** Required photos and screenshots include:

* Your final project, including any casework or interfacing elements that make up the full project (3D prints, screens, buttons, etc)
* The standalone PCBA, top
* The standalone PCBA, bottom
* Thermal camera images while the board is running under load (you may use your Board Bringup Thermal image here!)
* The Altium Board design in 2D view (screenshot)
* The Altium Board design in 3D view (screenshot)
* Node-RED dashboard (screenshot)
* Node-RED backend (screenshot)
* Block diagram of your system (You may need to update this to reflect changes throughout the semester.)

**


## Codebase

- A link to your final embedded C firmware codebases
- A link to your Node-RED dashboard code
- Links to any other software required for the functionality of your device
