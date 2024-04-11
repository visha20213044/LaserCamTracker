<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LaserTracker</title>
</head>

<body>
    <h1>LaserTracker</h1>

    <img src="demo.gif" alt="LaserTracker Demo">

    <p>LaserTracker is a real-time laser point tracking system that combines computer vision techniques with servo
        control. It detects and tracks a laser point within a video feed captured by a webcam, adjusting the position
        of the laser using a pan and tilt setup to keep it centered within a detected circular reference point.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>Real-time Laser Point Tracking:</strong> Detects and tracks a laser point in real-time using
            computer vision techniques.</li>
        <li><strong>Webcam Integration:</strong> Utilizes a webcam to capture the video feed for laser point detection.
        </li>
        <li><strong>Pan and Tilt Servo Control:</strong> Adjusts the position of the laser using a pan and tilt setup
            with mounted lasers for precise positioning.</li>
        <li><strong>Security Camera Integration:</strong> Can be adapted for use in security camera systems to track
            and monitor movement within a designated area.</li>
        <li><strong>Circle Detection:</strong> Detects circular reference points within the video frame to align the
            laser point.</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li><strong>Clone the Repository:</strong><br>
            <code>git clone https://github.com/yourusername/LaserTracker.git</code></li>
        <li><strong>Install Python Dependencies:</strong><br>
            <code>pip install opencv-python numpy pyserial</code></li>
        <li><strong>Upload Arduino Sketch:</strong><br>
            <ul>
                <li>Connect your Arduino board to your computer via USB.</li>
                <li>Open the Arduino IDE and upload the provided Arduino sketch (`servo_control.ino`) to your Arduino
                    board.</li>
            </ul>
        </li>
        <li><strong>Hardware Setup:</strong><br>
            <ul>
                <li>Connect your webcam to your computer.</li>
                <li>Connect the pan and tilt setup with mounted lasers to your Arduino board.</li>
            </ul>
        </li>
    </ol>

    <h2>Usage</h2>
    <ol>
        <li><strong>Run the Python Script:</strong><br>
            <code>python circle_detection.py</code></li>
        <li><strong>Point the Laser:</strong><br>
            <ul>
                <li>Point a laser at the webcam.</li>
                <li>Observe how the system tracks the laser point by adjusting the pan and tilt angles.</li>
            </ul>
        </li>
    </ol>

    <h2>Contributing</h2>
    <p>Contributions to LaserTracker are welcome! If you'd like to contribute, please fork the repository, make your
        changes, and submit a pull request. Feel free to open an issue if you encounter any bugs or have suggestions
        for improvements.</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>

</html>
