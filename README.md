# 🖥️ Automated Attendance System using Face Recognition

An AI-powered attendance system that detects and recognizes faces in real-time, automatically marking attendance in a CSV file.  
Built with **Python**, **OpenCV**, and **face recognition algorithms**.

---

## 📌 Features
- 🎯 **Face Registration** – Add new faces easily using the `add_faces.py` script.
- 📷 **Real-time Detection** – Detects and recognizes faces via webcam.
- 📝 **Automated Attendance** – Marks attendance in a CSV file with date and time.
- 📊 **Attendance History** – Stores attendance records for each session.
- 🔍 **Face Data Storage** – Uses serialized pickle files for fast access.

---

## 📂 Project Structure
```plaintext
face_recognition_project/
│
├── face_recognition_project-main/
│   ├── README.md                 # Project documentation
│   ├── add_faces.py               # Script to add new faces to the system
│   ├── app.py                     # Main application for real-time attendance
│   ├── test.py                    # Testing script for debugging
│   ├── background.png             # UI background image
│   │
│   ├── Attendance/
│   │   └── Attendance_07-04-2023.csv  # Sample attendance record
│   │
│   ├── data/
│   │   ├── faces.pkl              # Stored face encodings
│   │   ├── names.pkl              # Stored face names
│   │   └── haarcascade_frontalface_default.xml # Haar cascade model for detection

# Clone the repository
git clone https://github.com/yourusername/Automated_Attendance_System.git
cd Automated_Attendance_System

# Install dependencies
pip install -r requirements.txt

python add_faces.py
