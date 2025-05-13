# Human Emotion Detection Web Application (Image, Video, Real-Time)

This project is a **Flask-based Web Application** that can detect human emotions from:

- 📷 Uploaded Images  
- 🎥 Uploaded Videos  
- 🎥 Real-Time Webcam Feed

It uses a **Deep Learning model** trained to recognize emotions like Angry, Happy, Sad, Neutral, etc., and is fully mobile-friendly!

## 🌟 Features

- ✅ Upload an image ➔ Detect emotions ➔ View processed image  
- ✅ Upload a video ➔ Detect emotions ➔ View processed video  
- ✅ Real-time webcam emotion detection directly in browser  
- ✅ Beautiful Bootstrap 5 frontend  
- ✅ Loading spinners during processing for smooth experience  
- ✅ Mobile & Desktop compatible (Responsive design)  
- ✅ Lightweight and easy to deploy

## 🛠️ Technology Stack

| Component        | Technology         |
|------------------|--------------------|
| Frontend         | HTML5, Bootstrap 5 |
| Backend          | Flask (Python)     |
| ML Model         | TensorFlow/Keras   |
| Image Processing | OpenCV             |
| Deployment       | Render, Heroku, or localhost |

## 🚀 Installation and Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Mubassira-Esha/human-emotion-detection
cd human-emotion-detection
````

### 2. Create and Activate a Virtual Environment

```bash
python3 -m venv .env
# Activate on Windows:
source .env\Scripts\activate
# (Or use source .env/bin/activate on Linux/Mac)
```

### 3. Install the Required Dependencies

```bash
pip3 install -r requirements.txt
```

### 4. Run the Flask App

```bash
python3 app.py
```

The app will start running at: `http://127.0.0.1:5000/`

## 📂 Project Structure

```bash
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── static/                 # CSS, JS, and assets
├── templates/              # HTML templates
├── models/                 # Pre-trained emotion detection model
└── README.md               # Project documentation
```

## 📸 Emotion Categories Detected

* Angry 😠
* Disgust 😒
* Fear 😨
* Happy 😄
* Sad 😢
* Surprise 😲
* Neutral 😐

## 📌 Notes

* Make sure your system has a working webcam for real-time detection.
* TensorFlow may require additional dependencies based on your OS and Python version.
* For best performance, use Python 3.9–3.11.

## 📃 License

This project is licensed under the **Apache License**.

## 👩‍💻 Developed by

**Mubassira Esha**
Feel free to connect on [GitHub](https://github.com/Mubassira-Esha)
