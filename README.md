# Automatic-Attendance-Using-Python

## About Project

This project is made in Python for taking attendance automatically using camera. It can scan QR codes and mark attendance in Excel file. It can also be changed to face detection attendance system.

This project is useful for colleges, schools, offices and events.

---

## Features

* Automatic attendance using camera
* QR code scanning
* Attendance saved in Excel
* Voice announcement
* Duplicate entry check
* Daily attendance report

---

## Tools Used

* Python
* OpenCV
* NumPy
* OpenPyXL
* Pyttsx3

---

## Install Libraries

```bash id="psxjrv"
pip install opencv-python numpy openpyxl pyttsx3 pyzbar
```

---

## How to Run

```bash id="kiz4zu"
python Attendance_Program.py
```

or

```bash id="2m0pnh"
py -3.12 Attendance_Program.py
```

---

## Working

1. Open camera
2. Show QR code in front of camera
3. System scans roll number
4. Attendance marked in Excel file
5. Voice says present
6. Duplicate scan not allowed

---

## Output File

Excel file contains:

* Roll Number
* Name
* Time
* Present Count

---

## Future Improvement

* Face recognition attendance
* Database connection
* Web application
* Email report

---

## Author

Vaishnavi Patil

