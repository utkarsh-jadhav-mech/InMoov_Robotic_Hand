### InMoov Robotic Hand Project - README

This project involves the design and development of a 3D-printed robotic hand inspired by the InMoov platform. It uses servo motors, Arduino control, and a tendon-driven mechanism to achieve human-like finger movement.

<img width="1919" height="1042" alt="Robotic Arm" src="https://github.com/user-attachments/assets/0352f695-f1af-4e5b-8eee-2c6df70470ca" />

## 📚 Table of Contents
1. [Project Overview](#project-overview)
2. [Required Components](#required-components)
3. [3D Printing the Parts](#3d-printing-the-parts)
4. [Circuit Diagram](#circuit-diagram)
5. [Assembly Instructions](#assembly-instructions)
6. [Testing and Calibration](#testing-and-calibration)
7. [Additional Resources](#additional-resources)
8. [Contributing](#contributing)
9. [License](#license)
10. [Final Note](Final-Note)

## Project Overview

This project involves the complete development of a 3D-printed robotic hand based on the InMoov platform, integrating mechanical design, electronics, and control systems. The hand uses servo motors and a tendon-based mechanism to achieve human-like finger motion, controlled through an Arduino microcontroller. The project highlights end-to-end engineering workflow, from CAD modeling to system integration and testing. 

## Required Components

### Hardware
- 3D Printed Parts (InMoov STL files)
- Servo Motors (MG996R / SG90 – 5 to 6 units)
- Arduino UNO or compatible board
- External Power Supply (5V–6V recommended)
- Jumper wires and connectors
- Screws, nuts, and fasteners

### Tools
- 3D Printer (PLA or ABS compatible)
- Screwdriver set
- Pliers and cutters
- Soldering kit (optional)

## 3D Printing the Parts

1. Download STL files from the official InMoov platform  
2. Configure printing settings:
   - Layer Height: 0.1 – 0.2 mm  
   - Infill: 20–30%  
   - Material: PLA / ABS  
3. Print all components carefully to ensure dimensional accuracy  

## Circuit Diagram

Basic connection of servo motors with Arduino:

```
                 +----+          +---------+
                 |    |          |         |
            +5V  |    |----------| VCC     |
                 |    |          |         |
    Microcontroller|  |          | Servo 1 |
       (Arduino) |    |          |         |
            GND  |    |----------| GND     |
                 |    |          |         |
            PWM1 |    |----------| Signal  |
                 |    |          +---------+
                 |    |              .
                 |    |              .
            PWM2 |    |          +---------+
                 |    |          |         |
                 +----+          | Servo 5 |
                                 |         |
                                 +---------+
```

- **PWM1 - PWM5**: Connect to digital pins on the Arduino (e.g., 9, 10, 11, 12, 13).
- **VCC**: Common 5V power supply for all servos.
- **GND**: Common ground.

## Assembly Instructions

### Step 1: Finger Assembly
- Connect finger segments using joints
- Insert tendon wires (nylon/fishing line)
- Attach servo motors at base

### Step 2: Palm Assembly
- Fix all fingers to palm structure
- Ensure smooth movement of joints

### Step 3: Wrist Assembly
- Attach wrist servo for rotation
- Connect to forearm structure (optional)

### Step 4: Wiring
- Connect all servos to Arduino
- Ensure proper grounding and stable connections

## Testing and Calibration

1. Power ON the system  
2. Check individual servo movement  
3. Adjust servo angles in Arduino code  
4. Calibrate finger positions for smooth motion  

## Additional Resources

- **InMoov Forum**: For community support and discussions.
- **YouTube Tutorials**: Search for "InMoov hand assembly" for visual guidance.


## Contributing

Contributions are welcome!  
You can improve this project by:
- Enhancing CAD design  
- Improving control system  
- Adding sensors or AI-based control

## License

This project follows open-source principles inspired by the InMoov platform.  
Refer to the LICENSE file for more details.

## Final Note

The InMoov robotic hand project is a great starting point for learning robotics, combining 3D printing, electronics, and programming into a single system. It provides hands-on experience in building real-world mechatronics applications.
