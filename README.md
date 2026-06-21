## 🚀 Real-Time Face Blur AI Tool | Python + OpenCV 🔥

A real-time AI-powered face blur tool built using Python and OpenCV.

## 🎯 Features:
🔥 Real-time face detection
🔒 Automatic face blur for privacy
👨‍💻 Works with any webcam
🤖 Uses Haarcascade or DNN AI models
🎓 Ideal for college submissions & CV projects


## 🧠 Tech Stack: 
Tool	Purpose:
🐍 Python:	Main programming language
👁️ OpenCV:	Face detection & blurring
🤖 Haarcascade / DNN: 	Pre-trained AI models
🎥 Webcam	Real-time input feed

## ⚙️ Installation: 

1️⃣ Install OpenCV
pip install opencv-python

2️⃣ (Optional but Recommended) Download DNN Model
Download these files and place them in your project folder:
deploy.prototxt
res10_300x300_ssd_iter_140000.caffemodel

Download from OpenCV official model repo:
https://github.com/opencv/opencv/tree/master/samples/dnn/face_detector

▶️ Usage:
Run the real-time blur script:
python3 blur_realtime.py
Press Q to exit.

## 🧩 Core Logic Snippet
for (x, y, w, h) in faces:
    face = frame[y:y+h, x:x+w]
    blur = cv2.GaussianBlur(face, (75, 75), 30)
    frame[y:y+h, x:x+w] = blur
    
## 📜 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Aditya Kumar**

- B.Tech CSAI, USICT
- Frontend & Full Stack Developer

⭐ If you found this project useful, don't forget to star the repository!
