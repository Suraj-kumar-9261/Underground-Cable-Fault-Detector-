# Underground Cable Fault Detector

### The **Underground Cable Fault Detector** is a system designed to detect faults in underground cables, identify the faulty phase, and determine the distance to the fault. Using components like Arduino Uno, GSM module, and an LCD display, it provides real-time fault status and location tracking, ensuring timely detection and maintenance of cable faults.

<div align="center">
  <img src="https://github.com/user-attachments/assets/underground-cable-fault-detector-demo" alt="Underground Cable Fault Detector Demo" />
</div>

## ► Features
| Feature             | Description                                                                            |
|---------------------|----------------------------------------------------------------------------------------|
| Fault Detection      | Detects in which phase the fault is created and calculates the distance to the fault.   |
| Fault Status Display | The 16x2 LCD display shows the status of the fault in real-time.                       |
| GSM Location Tracking| GSM module tracks and sends the actual location of the fault via SMS.                  |
| Rechargeable Battery | Lithium battery ensures continuous operation, and it's easily rechargeable.            |

## ► Technologies Used
| Component          | Description                                                        |
|--------------------|--------------------------------------------------------------------|
| Arduino Uno        | Main microcontroller that controls the system and interfaces with sensors. |
| GSM Module         | Sends the fault location via SMS to a pre-configured number.       |
| 16x2 LCD Display   | Displays real-time fault status and distance.                      |
| 4 Relay Module     | Manages switching between different phases.                        |
| Lithium Battery    | Rechargeable battery to power the system reliably.                 |
| SIM Card           | Required for GSM module communication.                            |
| Resistors, switches, jumper wires | Additional components for circuit connections and functionality. |

## ► Prerequisites & Installation
| Step | Description                                                                 |
|------|-----------------------------------------------------------------------------|
| 1    | Obtain all the components, including Arduino Uno, GSM module, LCD, and others. |
| 2    | Install the Arduino IDE and necessary libraries for GSM and LCD.            |
| 3    | Clone the repository for the Underground Cable Fault Detector project.      |
| 4    | Connect the components as per the circuit diagram provided in the documentation. |
| 5    | Upload the code to the Arduino Uno.                                         |
| 6    | Insert the SIM card into the GSM module and test the system for functionality. |

## ► Usage
| Feature           | Description                                                                     |
|-------------------|---------------------------------------------------------------------------------|
| Fault Detection    | Automatically detects the faulty phase and calculates the distance to the fault. |
| LCD Display        | Shows the phase and distance of the fault in real-time.                         |
| GSM Tracking       | Sends the fault location to the user's phone via SMS.                           |

## ► Acknowledgments
| Acknowledgment    | Description                                                                  |
|-------------------|------------------------------------------------------------------------------|
| 1                 | Thanks to the Arduino and electronics communities for guidance and resources. |
| 2                 | Inspired by the need for accurate and timely fault detection in electrical systems. |

