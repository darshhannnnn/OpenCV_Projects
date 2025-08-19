# Hand Gesture Controlled LED System ✋💡

This project uses **OpenCV**, **cvzone HandTrackingModule**, and **Arduino (via pyFirmata)** to detect hand gestures from a webcam and control LEDs connected to an Arduino board.  

The number of fingers shown to the camera determines how many LEDs light up.  

---

## 📌 Features
- Detects hand gestures in real-time using a webcam.  
- Maps finger count (0–5) to corresponding LED outputs.  
- Displays finger count on the video feed.  
- Controls Arduino-connected LEDs using **pyFirmata**.  

---

## 🛠️ Requirements

### Hardware
- Arduino UNO (or compatible board)  
- 5 LEDs  
- Resistors (220Ω recommended)  
- Jumper wires & breadboard  
- Webcam  

### Software
- Python 3.8+  
- Libraries:
  - `opencv-python`
  - `cvzone`
  - `pyfirmata`  

Install dependencies with:
```bash
pip install opencv-python cvzone pyfirmata
