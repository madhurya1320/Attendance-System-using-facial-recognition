# 🎓 Attendance System Using Face Recognition

An automated attendance tracking system built with **Python** that uses **Face Recognition** technology to identify and log attendance in real-time. This project eliminates manual attendance marking, reduces human error, and ensures a faster, contactless process.

---

## 🚀 Features
- ✅ Real-time face detection and recognition using webcam  
- 📸 Automatic attendance marking in an Excel sheet with timestamps  
- 🧠 Facial encoding and comparison using **OpenCV** and **dlib**  
- 💾 Pre-trained database of student/employee images  
- 🕒 Timestamp-based tracking for punctuality monitoring  
- 🔒 Prevents proxy or duplicate attendance entries  
- 📊 Generates easy-to-read attendance logs in Excel format  

---

## 🧰 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Programming Language** | Python |
| **Libraries/Frameworks** | OpenCV, dlib, face_recognition, NumPy, OS |
| **Environment** | Jupyter Notebook |
| **Output Format** | Excel (.xlsx) |

---

## 🧩 How It Works

1. The webcam captures an image of the student/employee.  
2. The system encodes facial features using **face_recognition** and compares them with a pre-trained dataset.  
3. Once a match is found, the system logs:
   - **Name of the person**
   - **Time of recognition**
   - **Date of attendance**
4. The attendance record is stored in an **Excel sheet** automatically.  

---

## ⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Attendance-System-Using-Face-Recognition.git
   cd Attendance-System-Using-Face-Recognition
````

2. Install the required dependencies:

   ```bash
   pip install opencv-python face-recognition dlib numpy
   ```

3. Add a folder named `Images` containing subfolders for each person (e.g., `/Images/John`, `/Images/Mary`).

4. Run the project:

   ```bash
   python attendance_system.py
   ```

5. Attendance will be automatically saved in an Excel file named `Attendance.xlsx`.

---

## 📊 Example Output

| Name                     | Time     | Date       |
| ------------------------ | -------- | ---------- |
| Kosti Gowri Sai Madhurya | 09:02:34 | 2025-10-20 |
| Pasupuleti Bhargavi      | 09:03:01 | 2025-10-20 |

---

## 🔍 Future Enhancements

* Add mask recognition to handle post-COVID scenarios
* Integrate cloud storage for centralized data management
* Implement mobile or web dashboard for administrators
* Add email/SMS alerts for absentees

---

## 🧑‍💻 Contributors

* **Kosti Gowri Sai Madhurya**
* Pasupuleti Bhargavi
* Kota Lekhya
* Bhanu Prakash Racha

---

## 🏫 Institution

**Department of Computer Science and Engineering**
**GITAM (Deemed to be University), Visakhapatnam**

---

