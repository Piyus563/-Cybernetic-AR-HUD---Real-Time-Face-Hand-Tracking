#Real-Time-Face-Hand-Tracking
Created by @piyush kumar

A futuristic cyberpunk-style AR/HUD overlay system that tracks your face and hand gestures in real-time, just like in the reference images!



GitHub: @piyus563
Project Owner: Piyush Kumar

🚨 Please give credit when using or sharing this project!

If you use this code, fork it, or create content with it, please mention:


🚀 Features
Real-time face mesh tracking with MediaPipe
Hand gesture recognition (Open Palm, Fist, Pinch)
Futuristic HUD overlays with cyberpunk aesthetics
Neural network visualization (left side wireframe)
Evolution progress tracking ("cyborg evolution: X% complete")
Biometric scanning effects with animated crosshairs
Circuit overlays that react to gestures
System status panels with real-time data
Smooth animations and glowing effects
FPS counter and performance monitoring
🎮 Gesture Controls
Gesture	Effect
Open Palm 🖐️	Glowing circuit overlays around hands
Fist ✊	Progress bar: "cyborg evolution: X% complete"
Pinch 🤏	Face scanning animation with crosshairs
🛠️ Installation
Prerequisites
Python 3.9+
Webcam/Camera
563Windows/Mac/Linux
Quick Setup
Clone/Download this project to an empty folder

Install dependencies:

pip install -r requirements.txt
Run the application:

python main.py
Manual Installation (if pip fails)
pip install opencv-python==4.8.1.78
pip install mediapipe==0.10.5  
pip install numpy==1.24.3
pip install pygame==2.5.2
🎯 Usage
Launch the app:

python main.py
Position yourself in front of your webcam

Show hand gestures to activate different HUD effects:

Hold up your open palm → See glowing circuits
Make a fist → Watch evolution progress increase
Pinch with thumb & index → Activate face scanning
Press 'q' to quit safely

📁 Project Structure
Cybernetic AR HUD/
├── main.py              # Main application entry point
├── hud.py               # HUD drawing and visual effects
├── gestures.py          # Hand gesture recognition logic  
├── utils.py             # FPS counter and helper functions
├── requirements.txt     # Python dependencies
├── README.md           # This file
└── assets/             # Optional fonts/textures
⚙️ Configuration
Performance Tuning
Default resolution: 1280x720
Target FPS: 30+
Detection confidence: 0.5
Tracking confidence: 0.5
Customization
Edit values in main.py:

# Adjust camera resolution
cap.set(cv2.CAP_PROP_FRAME_WIDTH, 1280)  
cap.set(cv2.CAP_PROP_FRAME_HEIGHT, 720)

# Modify detection confidence
min_detection_confidence=0.5
min_tracking_confidence=0.5
🎨 Visual Effects
Neural Network (Left Side)
Animated wireframe network
Pulsing connections
Data flow indicators
Matches reference image style
Progress Bars (Right Side)
"cyborg evolution: X% complete"
"borg evolution level: X% complete"
Animated scan lines
Orange/cyan color scheme
Face Scanning
Real-time crosshair tracking
Animated scan lines
"FACIAL RECOGNITION ACTIVE" text
Red targeting overlay
Hand Circuits
Radiating connection lines
Pulsing circuit nodes
Central hub visualization
Responds to open palm gesture
🐛 Troubleshooting
Camera Issues
# Test camera access
python -c "import cv2; cap = cv2.VideoCapture(0); print('Camera OK' if cap.read()[0] else 'Camera Error')"
Performance Issues
Lower camera resolution in main.py
Reduce detection confidence
Close other camera applications
Use better lighting
Import Errors
# Reinstall dependencies
pip uninstall opencv-python mediapipe numpy pygame
pip install -r requirements.txt
Windows Specific
Install Visual C++ Redistributable if OpenCV fails
Try pip install --upgrade pip first
📱 System Requirements
CPU: Multi-core processor (Intel i5+ or AMD equivalent)
RAM: 4GB+ recommended
Camera: Any USB webcam or built-in camera
OS: Windows 10+, macOS 10.14+, Ubuntu 18.04+
Python: 3.9, 3.10, 3.11, or 3.12
🚨 Known Issues
First launch may be slower (MediaPipe model loading)
Gesture detection works best with good lighting
Face tracking requires clear view of face
Performance varies by hardware
📊 Performance Tips
Lighting: Use bright, even lighting for best tracking
Background: Plain backgrounds work better
Distance: Sit 2-3 feet from camera
Gestures: Make clear, deliberate gestures
CPU: Close unnecessary applications
🔧 Advanced Configuration
Modify Colors (in hud.py)
self.cyan = (255, 255, 0)      # BGR format
self.orange = (0, 165, 255)
self.red = (0, 0, 255)
Adjust Evolution Speed (in main.py)
# Faster evolution
self.cyborg_evolution = min(100.0, self.cyborg_evolution + 0.2)  # Was 0.1
Change Gesture Sensitivity (in gestures.py)
# Pinch detection threshold
if distance < 0.08:  # Was 0.05 (higher = easier to trigger)
🎬 Demo
The system creates a cyberpunk-style AR overlay that matches the reference images:

Left side: Animated neural network wireframe
Right side: Evolution progress bars
Center: Face tracking with crosshairs
Hands: Circuit overlays on gesture detection
UI: Futuristic cyan/orange color scheme
🆘 Support
If you encounter issues:

Check camera permissions
Verify Python version (3.9+)
Try different lighting conditions
Restart the application
Check system requirements
🚀 Future Enhancements
 Voice command integration
 Custom gesture training
 Recording/playback features
 Multi-person tracking
 VR headset integration

❌ Copy without giving credit to the original creator
❌ Claim it as your own work
❌ Remove attribution from the code
🙏 Credits & Acknowledgments
AI Computer Vision: MediaPipe by Google
Graphics Processing: OpenCV
Inspired by: Cyberpunk 2077, Ghost in the Shell, The Matrix
🤝 Contributing
Want to make this even more awesome? Contributions are welcome!

Fork this repository
Create a feature branch
Make your epic improvements
Submit a pull request
Get featured as a contributor!
Please maintain attribution to @tubakhxn as the original creator.




⭐ Don't forget to star this repo if you found it awesome! ⭐
