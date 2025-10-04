# 🧠 Cybernetic AR HUD – AI-Based Augmented Reality System

This project implements a **real-time Augmented Reality (AR) Heads-Up Display (HUD)** using **OpenCV** and **MediaPipe**.  
It tracks **face, hand, and body pose landmarks**, overlays **interactive AR visuals**, and responds to **hand gestures** with dynamic effects — creating a futuristic *cyborg interface* experience.

---

## 🚀 Features

- **Face Mesh Tracking:** Real-time face landmark detection with scanning and AR overlays  
- **Pose Tracking:** Tracks body movement to render an animated cybernetic arm  
- **Gesture Recognition:** Detects gestures like open palm, fist, and pinch for interactive control  
- **HUD Elements:** Neural network visuals, system panels, progress bars, and crosshairs  
- **Dynamic Effects:** Pulsing lights, glowing circuits, scanning lines, and progress animations  
- **Performance Stats:** Real-time FPS counter and system information panel  

---

## 🧩 File Overview

| File | Description |
|------|--------------|
| `main.py` | Main application that handles camera input, gesture recognition, and AR overlays |
| `hud.py` | Defines `CyberneticHUD` class – draws all visual components on the frame |
| `utlis.py` | Utility functions for FPS tracking, performance monitoring, color interpolation, etc. |

---

## ⚙️ Requirements

Create a `requirements.txt` file with the following dependencies:

```txt
opencv-python
mediapipe
numpy
```

To install them, run:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/piyushkumar/Cybernetic-AR-HUD.git
   cd Cybernetic-AR-HUD
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the system:
   ```bash
   python main.py
   ```

4. Show these gestures to interact:
   - ✋ **Open Palm:** Activates glowing circuits  
   - ✊ **Fist:** Increases evolution progress  
   - 🤏 **Pinch:** Triggers face scanning animation  
   - ❌ Press **‘q’** to exit

---

## 🖥️ System Preview

- **Face AR Overlay:** Displays scanning frames and bounding boxes  
- **HUD Dashboard:** Shows system status and evolution bars  
- **Gesture Feedback:** Visual circuit patterns and motion effects  

---

## 💡 Future Improvements

- Add more gesture types and custom animations  
- Integrate voice feedback or speech recognition  
- Export AR video recordings automatically  

---

## 👨‍💻 Author

**Piyush Kumar**  
📍 Built with Python, OpenCV & MediaPipe  
🔗 [LinkedIn](https://linkedin.com/in/piyushkumar) • [GitHub](https://github.com/piyushkumar)


