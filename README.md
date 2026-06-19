# 🤟 Sign Language Detection using Streamlit

A real-time Sign Language Detection web application built with Streamlit, MediaPipe, and WebRTC. The application captures live video from a webcam and detects hand gestures/signs in real time.

## 🚀 Features

- Real-time webcam streaming
- Hand landmark detection using MediaPipe
- Live sign language recognition
- User-friendly Streamlit interface
- Low-latency video processing with WebRTC

## 🛠️ Technologies Used

- Python
- Streamlit
- MediaPipe
- OpenCV
- streamlit-webrtc
- PyAV

## 📂 Project Structure

```
project/
│
├── app.py
├── backend/
│   └── camera_stream.py
├── requirements.txt
└── README.md
```

## ✋ Supported Signs

| Sign | Description |
|--------|------------|
| ✊ | FIST |
| ✋ | FIVE |
| ☝ | ONE |
| ✌ | VICTORY |
| 👍 | THUMBS UP |
| 🤟 | LOVE YOU |
| L | L Sign |

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sign-language-detection.git
cd sign-language-detection
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📸 How It Works

1. Access your webcam through the browser.
2. MediaPipe detects hand landmarks.
3. The backend processes the landmarks.
4. Recognized gestures are displayed in real time.

## 📋 Requirements

```txt
streamlit
streamlit-webrtc
mediapipe
opencv-python
av
numpy
```

## 🔮 Future Improvements

- More sign language gestures
- Deep Learning-based recognition
- Sentence formation from gestures
- Multi-hand detection
- Model accuracy improvements

## 👨‍💻 Author

Developed by **Tejaswi Kolluri**

## 📜 License

This project is open-source and available under the MIT License.
