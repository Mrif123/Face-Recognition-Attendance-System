# Face Recognition Attendance System  

## 📌 Overview  
The **Face Recognition Attendance System** is a machine learning–based project designed to automate attendance recording using facial recognition technology. It captures real-time video from a webcam, detects and recognizes faces, and marks attendance automatically in a structured format.  

This project eliminates manual attendance processes, improves accuracy, and is scalable for classrooms, offices, or events.  

---

## 🚀 Features  
- 🔍 **Real-time Face Detection** using OpenCV and `face_recognition` library  
- 📷 **Live Webcam Integration** for continuous monitoring  
- 📝 **Automated Attendance Marking** in CSV/Excel files  
- 🔊 **Speech Notifications** (optional: system voice announces marked attendance)  
- 📊 **Attendance Logs** with timestamps  

---

## 🛠️ Tech Stack  
- **Languages & Frameworks:** Python  
- **Libraries Used:**  
  - `OpenCV` – Image & video processing  
  - `face_recognition` – Facial recognition & comparison  
  - `NumPy` – Data processing  
  - `pandas` – Attendance storage in CSV  
  - `pyttsx3` – Speech synthesis (optional)  

---

## 📂 Project Structure  
```
├── Face_Recognition.ipynb       # Main Jupyter Notebook
├── images/                      # Folder containing known faces
├── Attendance.csv               # Output attendance file
├── requirements.txt             # Dependencies
└── README.md                    # Project documentation
```

---

## ⚙️ Installation & Setup  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/face-recognition-attendance.git
cd face-recognition-attendance
```

### 2. Create virtual environment (recommended)  
```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies  
```bash
pip install -r requirements.txt
```

### 4. Run the notebook  
```bash
jupyter notebook Face_Recognition.ipynb
```

---

## 📊 Usage  
1. Place images of known individuals inside the `images/` folder.  
2. Run the notebook.  
3. The system captures real-time webcam footage.  
4. Attendance is marked automatically when a recognized face is detected.  
5. Data is saved into `Attendance.csv` with **Name, Date, and Time**.  

---

## ✅ Future Enhancements  
- Integration with **databases** (MySQL/PostgreSQL)  
- Cloud deployment for **remote access**  
- Enhanced **GUI features**  
- Mobile app support  

---

## 👨‍💻 Author  
**Mohammed Rifaiz**  
- 🌐 [GitHub](https://github.com/Mrif123)  
- 💼 [LinkedIn](https://linkedin.com/in/mohammed-rifaiz)  

---

## 📜 License  
This project is licensed under the MIT License – feel free to use and modify it.  
