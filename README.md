# Face Recognition Based Attendance System

A Python-based attendance system with a graphical user interface, using **Dlib** for face recognition.

## 🖥️ Overview

This system captures student faces through a webcam and marks their attendance by recognizing their faces using **Dlib's facial encodings**. A user-friendly GUI is developed using **Tkinter**, making it accessible for all users.

---

## 💻 Technologies Used

- **Tkinter** – GUI development  
- **Dlib** – Face detection & recognition using HOG + face encodings  
- **OpenCV** – Webcam access and image capture  
- **CSV, Pandas, NumPy, Datetime** – Data processing and file handling  

---

## 🚀 Features

- Simple and interactive GUI interface  
- Password-protected face registration for new users  
- Automatic CSV generation for:
  - Student registration details
  - Daily attendance logs (with timestamps)
- Live tabular display of daily attendance (ID, Name, Date, Time)  
- Real-time face recognition using **Dlib’s 128-dimensional face embeddings**

---

## 📁 Output

- A CSV file is generated or updated each day with the attendance records.
- Student registration details are stored in a separate CSV file.

---

## 📝 Note

This project uses **Dlib** instead of traditional OpenCV methods like `cv2.face.LBPHFaceRecognizer_create()` for improved accuracy and robustness in face recognition.

---

## 📌 Requirements

- Python 3.x  
- `dlib`, `opencv-python`, `numpy`, `pandas`, `tkinter`

Install required libraries:

```bash
pip install dlib opencv-python numpy pandas
