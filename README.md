# AI-Powered Emotion Monitoring System

## Overview

The **AI-Powered Emotion Monitoring System** is an advanced project that integrates **Computer Vision, Signal Processing, and AI** to analyze **human emotions** in real time. By leveraging **facial expressions, heart rate variability (HRV), micro-expressions, pupil dilation, and skin tone changes**, this system can detect emotional states such as **stress, anxiety, depression, happiness, and anger**.

## Features

✅ **Real-Time Facial Emotion Recognition** using deep learning models (CNNs, OpenCV, or MediaPipe)
✅ **Heart Rate Estimation** from facial skin tone variations using Eulerian Video Magnification (EVM)
✅ **HRV Analysis** for detecting stress and anxiety patterns
✅ **Micro-Expression Detection** to capture subtle emotions
✅ **Pupil Dilation and Eye Movement Tracking** for mental state analysis
✅ **Multimodal Data Fusion** integrating multiple physiological and visual cues
✅ **Data Visualization Dashboard** to monitor real-time emotional insights

## How It Works

1. **Face Detection & ROI Extraction**: The system detects a face and isolates the **Region of Interest (ROI)** for further analysis.
2. **Color Magnification & Signal Processing**: Subtle **color changes** in the skin (caused by blood flow) are amplified to estimate heart rate and HRV.
3. **Fourier Transform & Bandpass Filtering**: Extracts **frequency components** corresponding to pulse rate.
4. **Facial Expression Analysis**: A deep learning model classifies facial expressions into emotional categories.
5. **Micro-Expression & Eye Tracking**: Detects quick facial movements and pupil dilation variations.
6. **Emotion Classification Model**: Fuses all extracted features to classify emotions with a trained **AI model**.
7. **Real-Time Visualization**: Displays heart rate, HRV, facial analysis, and emotion insights on a dynamic dashboard.

## Tech Stack

- **Programming Language**: Python 🐍
- **Libraries**:
  - **Computer Vision**: OpenCV, cvzone, MediaPipe, Dlib
  - **Machine Learning**: TensorFlow/Keras, PyTorch
  - **Signal Processing**: NumPy, SciPy, FFT, Eulerian Video Magnification (EVM)
  - **Data Handling**: Pandas, Matplotlib, Seaborn
  - **Frontend Dashboard**: Streamlit/Dash for real-time visualization

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/emotion-monitoring.git
cd emotion-monitoring
```

Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate     # On Windows
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python main.py
```

This will start the **real-time emotion monitoring system**.

## Applications

🚑 **Mental Health Monitoring**: Helps in detecting early signs of depression, anxiety, and stress.
🎮 **Gaming & VR**: Adaptive experiences based on player emotions.
📊 **Workplace & Productivity**: Emotion tracking for stress management.
📚 **Educational Tools**: Personalized learning environments based on student engagement.

## Future Enhancements

🔹 **Multimodal AI Integration**: Combining speech tone and text sentiment analysis.
🔹 **BCI Integration**: Exploring Brain-Computer Interfaces for deeper insights.
🔹 **Real-Time Alerts & Notifications**: AI-based recommendations based on emotional fluctuations.

## Contributing

1. Fork the repository.
2. Create a new branch (`feature-branch`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push to your branch (`git push origin feature-branch`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

---

🌟 **Developed by Maha Baig** | Passionate about AI & Human Behavior
