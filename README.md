# 🧠 CMRL_FaceRecognition  
### Deep Learning-based Face Recognition System  

A **deep learning-based Face Recognition System** developed for **Chennai Metro Rail Limited (CMRL)** to automate and secure employee verification.  
This system performs **real-time face verification** using webcam input and integrates **liveness detection**, **SQLite-based data management**, and a **PyQt5-based user interface** for smooth interaction.  

---

## 🚀 Features  
- Capture **20 images per user** with data augmentation and preprocessing  
- **Base64 image conversion** and storage in **SQLite database**  
- Train deep learning model with **face embeddings** for accurate recognition  
- **Liveness detection** to prevent spoofing or fake images  
- **Real-time webcam verification** for staff authentication  
- **PyQt5 GUI** for a clean, user-friendly interface  
- **Logging of verification details** (Name, Date, Time, Location, Accuracy)  

---

## 📂 Project Structure  
CMRL_FaceRecognition/
│
├── data/
│ └── images/ # Captured & preprocessed face images
│
├── embeddings/
│ └── face_embeddings.pkl # Serialized face embeddings
│
├── model/
│ └── face_recognition_model.h5
│
├── ui/
│ └── main_interface.py # PyQt5 GUI application
│
├── reports/
│ └── weekly_report.md # Weekly internship progress or reports
│
├── database/
│ └── verification.db # SQLite DB storing user data
│
├── scripts/
│ ├── capture_faces.py
│ ├── preprocess.py
│ ├── train_model.py
│ ├── verify_face.py
│
├── README.md
└── requirements.txt

---

## 🛠️ Installation  

### 1. Clone the Repository  
```bash
git clone https://github.com/AishwaryaDevi003/CMRL_FaceRecognition.git
cd CMRL_FaceRecognition

**### 2. Install Dependencies**
pip install -r requirements.txt
🚀 How to Run
Capture Faces
python scripts/capture_faces.py

Train Model
python scripts/train_model.py

Launch GUI
python ui/main_interface.py

🧾 Requirements

Add the following dependencies in requirements.txt:

opencv-python
numpy
Pillow
tensorflow
keras
pyqt5
sqlite3
imutils
scikit-learn

📊 About

This project was developed as part of an AI initiative at Chennai Metro Rail Limited (CMRL) to enable secure, real-time, and contactless staff verification using deep learning-based facial recognition.
It combines AI, computer vision, and database management to enhance security and improve operational efficiency.

👩‍💻 Developed By

AI Developer Team – Chennai Metro Rail Limited
Project Contributors: [Add your name or team members here]

📜 License

This project is part of an internal development initiative by CMRL.



