# EYE-DIRECTIVE-WHEELCHAIR
EYE DIRECTIVE WHEELCHAIR( SHOWCASED ON DESIGN IMPACT MOVEMENT):
🚀 Project Overview:
The Eye Directive Wheelchair is an innovative assistive technology designed for individuals with limited mobility, particularly those with conditions like Amyotrophic Lateral Sclerosis (ALS). This system uses eye-tracking technology to control wheelchair movement, providing a hands-free and intuitive navigation experience.

🏆 Key Features:
Eye-Tracking Navigation: Specialized cameras track eye movement to determine the intended direction.
Microcontroller-Based Control: Uses two microcontrollers for processing and transmitting signals.
Obstacle Avoidance: Equipped with ultrasonic sensors to prevent collisions.


Dual Operation Modes:
Mode 1 - Eye Directed Mode: Eye movement is detected and translated into movement commands.
Mode 2 - Joystick Mode: A joystick is available as an alternative control method.
Emergency Stop Mechanism: A stop button ensures immediate cessation of movement when required.


🔧 How It Works:
Image Capturing: A wireless pinhole camera captures real-time eye movement.
Processing Unit: Images are transmitted to a computer and processed using OpenCV to track pupil movement.


Microcontroller Communication:
A transmitting microcontroller converts pupil position data into control signals.
A receiving microcontroller interprets these signals and directs wheelchair movement accordingly.


Motion Control:
If the eye looks left → Wheelchair moves right
If the eye looks right → Wheelchair moves left
If the eye looks straight → Wheelchair moves forward.


🛠️ Technologies Used:
Python & OpenCV for image processing
Arduino (Microcontrollers) for control and signal processing
Ultrasonic Sensors for obstacle detection
Wireless Camera for capturing real-time eye movements


📌 Installation & Setup:
Install OpenCV in your system:
bash
Copy
Edit
pip install opencv-python
Set up the Arduino microcontrollers with the necessary firmware.
Connect the wireless camera to the base station.
Run the eye-tracking script and ensure proper pupil detection before testing on the wheelchair.


📢 Acknowledgments:
This project was developed as part of Titan Company Ltd.'s Social Initiative under the Design Impact Movement.

💡 Future Enhancements:
Integration with AI for improved accuracy in eye-tracking.
Adding voice commands for additional accessibility.
Developing a mobile app for remote wheelchair control.
