# Virtual Hand Gesture-Based Keyboard

This project implements a **virtual keyboard** controlled using hand gestures. It utilizes **MediaPipe** for hand tracking and **OpenCV** for rendering the virtual keyboard, enabling users to type by simply moving their fingers in front of the camera.

### Key Features:
- **Hand Gesture Recognition**: Uses MediaPipe's hand tracking to detect gestures, enabling interaction with the virtual keyboard.
- **Customizable Virtual Keyboard**: Displays an on-screen keyboard with keys like letters, numbers, and a spacebar.
- **Typing Simulation**: Types characters by recognizing finger touches between the thumb and index finger, simulating typing on a real keyboard.
- **Interactive Design**: Includes a smooth gradient effect, glowing key text, 3D shadows for depth, and vibrant colors to enhance user experience.
- **Dynamic Text Display**: Typed text is shown in real-time as it is entered.
  
### Technologies Used:
- **Python**
- **OpenCV**: For handling video capture and rendering the virtual keyboard.
- **MediaPipe**: For hand tracking and gesture recognition.
- **PyAutoGUI**: To simulate typing input to the system.

### Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/virtual-hand-gesture-keyboard.git
   cd virtual-hand-gesture-keyboard
   ```
2. pip install opencv-python mediapipe pyautogui
30 python virtual_keyboard.py
