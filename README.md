# 🎯 Concentration Tracker

A real-time computer-vision experiment that estimates attentiveness from webcam input using eye blinks, gaze direction, and head pose.

## ✨ Features

- 👁️ Eye-blink detection using Eye Aspect Ratio (EAR)
- 👀 Gaze-direction estimation
- 🧭 Head-pose estimation
- 📊 Composite concentration score
- 🖥️ Live visual feedback
- ⚠️ Distraction tracking
- 📈 FPS and status indicators

## 🧠 How It Works

1. MediaPipe FaceMesh detects facial landmarks.
2. EAR is used to identify blinking and eye closure.
3. Iris landmarks help estimate gaze direction.
4. Facial geometry is used to infer head orientation.
5. The signals are combined into a concentration score.
6. Results are rendered live over the webcam feed.

## 🛠️ Tech Stack

- Python 3.x
- OpenCV
- MediaPipe
- NumPy

## 🚀 Run Locally

```bash
git clone https://github.com/Neetesh1541/concentration_tracker.git
cd concentration_tracker
pip install -r requirements.txt
python concentration_tracker.py
```

## ⚠️ Important Note

The concentration score is an experimental computer-vision estimate, not a medical or scientifically validated measurement of attention.

## 🔮 Future Improvements

- Calibration for different users
- Better gaze estimation
- Session history and analytics
- Configurable attention thresholds
- Improved robustness under different lighting

## 👨‍💻 Author

Built by **Neetesh Sharma**.
