
#  LaserCamTracker

LaserTracker is a Python-based system for real-time laser point tracking using computer vision techniques and servo control. It detects and tracks a laser point within a video feed, adjusting the position of a camera mounted on servo motors to keep the laser centered on a detected circular reference point.
![WhatsApp Image 2024-04-26 at 11 42 46 PM](https://github.com/visha20213044/LaserCamTracker/assets/97392436/145d4440-e278-44ac-a787-a52580701399)



## Features

- Real-time laser point detection and tracking using a webcam
- Utilizes a pan and tilt setup with mounted lasers for precise positioning
- Suitable for security camera systems and experimental setups
- Detects and tracks circular reference points, adjusting the laser position accordingly


## Requirements:
- Python 3.x with OpenCV and NumPy
- Arduino IDE for servo control
- Compatible webcam, Arduino nano board, 2 axis pan and tilt setup with mounted lasers(green),7805,Sg90,adapter,DC Jack,Jumper wire,Mini BreadBoard
## Circuit Diagram
![Screenshot 2024-04-12 031112](https://github.com/visha20213044/LaserCamTracker/assets/97392436/8272a956-6fcd-4828-976c-92a14f475677)
## Setup
- Install Python Dependencies:

  pip install opencv-python numpy pyserial

- Upload Arduino Sketch


- Connect your Arduino board to your computer.
- Open the Arduino IDE and upload the provided Arduino sketch (arduino_nano.ino) to your Arduino board.
- Connect your webcam to your computer and ensure it's recognized.
- Connect the pan and tilt setup with mounted lasers to your Arduino board.
- Run the Python script (Opencv_code.py) to start the tracking system:python Opencv_code.py

- Point the laser at the camera and observe how the system tracks the laser point by adjusting the pan and tilt angles.
## Contributing

Contributions are welcome! Fork the repository, make enhancements, and submit pull requests.

Feel free to use this modified description for your LaserTracker project. Let me know if you need further assistance!

