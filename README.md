# ✋ Gesture Controlled Web Browser

This is a Python + OpenCV-based project that detects hand gestures using your webcam and performs browser actions. By showing different numbers of fingers, users can open specific websites  — a fun and interactive way to control your computer hands-free!

---

## 👨‍💻 Developed By
**Abhin Sharma**  
Final Year B.Tech CSE Student  
GitHub: [@itsabhin](https://github.com/itsabhin)

---

## 🚀 Features

- 🔍 Real-time hand gesture detection using webcam
- ✌️ Shows 2, 3, or 4 fingers to open websites you choose
- 🧠 Uses contour detection, convex hulls & convexity defects
- 🔐 Safe and works without any external API calls

---

## 🛠️ Technologies Used

- Python 🐍
- OpenCV 📸
- NumPy 📊
- Math
- `webbrowser` & `os` modules

---

## 🧠 How It Works

1. The program captures your hand inside a fixed region on the webcam.
2. It calculates the number of fingers shown using the angle between defects in the hand contour.
3. Based on the number of fingers:
   - **2 fingers** → Opens Website 1
   - **3 fingers** → Opens Website 2
   - **4 fingers** → Opens Website 3
4. You define the websites at the beginning of the script.

---

## 🔧 How to Run

1. Clone the repo or download the code:
   ```bash
   git clone https://github.com/itsabhin/Gesture-Browser.git
   cd Gesture-Browser

2.Install dependencies:
  pip install opencv-python numpy

3.Run the script:
  python gesture_browser.py

4.Enter the websites when prompted. 
  Then, start using hand gestures in front of your webcam.
