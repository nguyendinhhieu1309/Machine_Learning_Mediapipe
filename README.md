
# 🖐️ Hand Gesture Controlled Mouse Using Mediapipe

This project uses **Mediapipe** for hand detection and **pydirectinput** to control the mouse on your computer. By tracking hand landmarks via your webcam, it can control mouse movements and simulate mouse clicks based on specific hand gestures.

## 🛠️ Technologies and Libraries Used
- ![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
- ![OpenCV](https://img.shields.io/badge/OpenCV-4.5.3-blue.svg) 
- ![Mediapipe](https://img.shields.io/badge/Mediapipe-0.8.7-green.svg)
- ![pydirectinput](https://img.shields.io/badge/pydirectinput-1.0.4-orange.svg)

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Hand-Gesture-Controlled-Mouse.git
   cd Hand-Gesture-Controlled-Mouse
   ```

2. **Install the required libraries:**
   Make sure you have Python 3.9+ installed. Then install the necessary dependencies:
   ```bash
   pip install opencv-python mediapipe pydirectinput
   ```

## 🚀 How to Use

1. **Run the Script**: 
   Execute the main script using the following command:
   ```bash
   python hand_controlled_mouse.py
   ```

2. **Hand Gestures**:
   - **Mouse Movement**: Move your hand in front of the webcam to control the mouse pointer. The tip of your index finger controls the mouse pointer.
   - **Mouse Click**: If your index finger is extended and other fingers are curled, the mouse will click. Release to stop clicking.

## 🖼️ Demo

A quick demo showcasing the project’s functionality.

![Hand Gesture Demo](https://github.com/user-attachments/assets/demo.gif)

## 📂 Project Structure

```
Hand-Gesture-Controlled-Mouse/
│
├── hand_controlled_mouse.py     # Main script for hand detection and mouse control
├── README.md                    # Project documentation
└── requirements.txt             # List of required libraries
```

## 🧑‍💻 Author
Developed by **Nguyễn Đình Hiếu**

---

_If you found this project helpful, please give it a ⭐ on [GitHub](https://github.com/nguyendinhhieu1309/Machine_Learning_Mediapipe.git)!_
