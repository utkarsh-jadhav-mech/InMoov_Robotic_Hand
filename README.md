This project is a 3D-printed InMoov Robotic Hand designed and assembled as a low-cost humanoid robotic system. The hand is inspired by the open-source InMoov project and is controlled using servo motors, Arduino, and mechanical linkages to replicate human finger movements.

The project focuses on combining mechanical design, electronics, and basic programming to achieve real-time hand motion control.

⚙️ Components Used
Mechanical
3D Printed Hand Parts (PLA/ABS)
Nylon string / fishing line (tendon mechanism)
Springs (finger return mechanism)
Fasteners (nuts, bolts, screws)

⚡ Electronics
Arduino UNO / Nano
Servo Motors (SG90 / MG90S / similar)
Bluetooth Module (HC-05 / HC-06) (optional for wireless control)
External Power Supply

Working Principle
Each finger is controlled using a servo motor
Motion is transmitted using string-based tendon mechanism
Arduino sends PWM signals to control servo angles
Fingers move in coordination to simulate human hand gestures
Optional Bluetooth control allows wireless operation via mobile app

InMoov_Robotic_Hand/
│
├── CAD_Designs/          # 3D model files (.STL / .SLDPRT)
├── Arduino_Code/         # Servo control programs
├── Assembly_Guide/       # Step-by-step assembly instructions
├── Images/               # Project photos
└── README.md

<img width="1919" height="1042" alt="Robotic Arm" src="https://github.com/user-attachments/assets/5b3f7ea7-1944-4ca8-b229-7d6ea4e90b08" />

📈 Future Improvements
EMG sensor-based control (muscle signals)
AI-based gesture recognition
Stronger servo motors for higher load
Full robotic arm integration

👨‍💻 Author

Utkarsh Jadhav
Mechanical Engineering Student
GitHub: https://github.com/utkarsh-jadhav-mech
