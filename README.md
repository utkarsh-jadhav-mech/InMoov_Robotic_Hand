🤖 InMoov Robotic Hand Project
📌 Project Overview

The InMoov Robotic Hand is an open-source, 3D-printed robotic system designed for learning robotics, prosthetics, and mechanical design.
This project replicates human hand movements using servo motors controlled by Arduino, making it a low-cost and educational robotic solution.

It integrates:

Mechanical design (3D printing + assembly)
Embedded systems (Arduino control)
Actuation system (servo-based motion)
📷 Project Preview
<p align="center"> <img src="Images_And_Video/Robotic%20Arm.png" width="450"/> </p>
🧩 Required Components
🔧 Mechanical Parts
3D Printed Hand Components (PLA/ABS)
Nylon string / fishing line (tendon system)
Springs for finger return mechanism
Screws, nuts, and fasteners
⚡ Electronics
Arduino UNO / Nano
Servo Motors (MG996R / SG90 / equivalent)
5V External Power Supply
Jumper wires
🛠 Tools Required
3D Printer
Screwdriver set
Soldering kit (optional)
Cutting pliers
🖨 3D Printing the Parts
Download STL files from:
👉 https://inmoov.fr/hand-and-forarm/
Recommended print settings:
Material: PLA / ABS
Layer height: 0.1 – 0.2 mm
Infill: 20–30%
Strong bed adhesion required
Print all parts carefully and clean supports after printing.
⚡ Circuit Overview

Each servo motor is connected to the Arduino as follows:

Signal Pins → Digital PWM pins (e.g., 9, 10, 11, 12, 13)
VCC → External 5V power supply
GND → Common ground
Simple Connection Logic:
One servo per finger
Arduino controls angle using PWM signals
External power ensures stable servo operation
🔩 Assembly Instructions
1. Finger Assembly
Attach servo motors at each finger base
Connect tendon strings for motion control
Ensure smooth joint movement
2. Palm Assembly
Mount all fingers to palm structure
Secure servo alignment properly
3. Wrist Integration
Attach wrist servo (if applicable)
Connect movement mechanism
4. Wiring
Connect all servos to Arduino
Ensure proper power distribution
Verify ground is common for all components
🧪 Testing & Calibration
Initial Test
Power ON Arduino and check servo response
Ensure all fingers move correctly
Calibration
Adjust servo angles in Arduino code
Fine-tune finger range of motion
Reduce mechanical stress in joints
📈 Key Features
Human-like finger movement
Low-cost robotic design
Modular and scalable structure
Arduino-based control system
3D printable mechanical system
📚 Learning Outcomes
Robotics mechanism design
Servo motor control using Arduino
3D CAD modeling & manufacturing
Embedded systems integration
Mechanical linkage systems (tendon-based motion)
🚀 Future Improvements
Bluetooth / Mobile app control
EMG (muscle signal) integration
AI-based gesture recognition
Full robotic arm expansion
Stronger industrial-grade servos
🤝 Contributing

Contributions are welcome.
Feel free to fork this repository and submit pull requests for improvements.

📄 License

This project is licensed under the MIT License.

⭐ Author

Utkarsh Jadhav
Mechanical Engineering Student
GitHub: https://github.com/utkarsh-jadhav-mech
