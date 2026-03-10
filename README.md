# Virtual Mouse Pro 🖱️🖐️

A high-performance virtual mouse controller with adaptive smoothing, cursor trails, and a polished modern HUD.

## 🚀 Key Features
- **Adaptive Smoothing**: Uses a dynamic smoothing algorithm that balances precision (for slow movements) and speed (for fast movements).
- **Zero-Lag Engine**: Asynchronous MediaPipe Tasks API for maximum FPS and minimal latency.
- **Visual Feedback**: Real-time cursor trails and glowing active area for a professional feel.
- **Modern HUD**: Polished, non-intrusive status overlay showing engine health and actions.
- **Smart Exit**: Close the application instantly with a fist gesture.

## 📝 Gesture Guide
| Action | Gesture | Visual Feedback |
| :--- | :--- | :--- |
| **Move Cursor** | Point Index Finger | Magenta Glow & Trail |
| **Left Click** | Pinch Index + Thumb | Green Pulse & Fill |
| **Right Click** | Pinch Middle + Thumb | Red Pulse |
| **Scroll Up/Down** | Join Middle + Ring | Yellow Pulse |
| **Close App** | Make a Fist | HUD "EXITING" |

## 🛠️ Setup
1. Install dependencies:
   ```bash
   pip install opencv-python mediapipe pyautogui numpy requests
   ```
2. Run the script:
   ```bash
   python main.py
   ```
