# 📍 Smart Attendance System with GPS Verification

A simple and efficient **Smart Attendance System** that allows students to mark attendance using a **QR code and Google Form**, with **GPS location tracking** to ensure attendance is marked only from the correct location.

This project is designed to reduce proxy attendance and make attendance management easy, fast, and reliable.

---

## 🚀 Features

- 📱 QR Code–based attendance system  
- 📝 Google Form for attendance submission  
- 📊 Automatic data storage in Google Sheets  
- 📍 **GPS location tracking** to verify user location  
- ⏱ Timestamped attendance records  
- ❌ Prevents proxy or remote attendance  
- 🌐 Easy to deploy and use  

---

## 🛠 Technologies Used

- Google Forms  
- Google Sheets  
- Google Apps Script  
- HTML, CSS, JavaScript  
- QR Code Generator  
- GPS / Geolocation API  
- GitHub (for version control and hosting)  

---

## ⚙️ How the System Works

1. A **QR code** is generated and displayed in the classroom.
2. Students scan the QR code using their mobile device.
3. The QR code opens a **Google Form**.
4. The system captures:
   - Name  
   - Roll Number  
   - Class  
   - **GPS Location (Latitude & Longitude)**  
   - Timestamp  
5. The submitted data is stored automatically in **Google Sheets**.
6. Attendance is validated using the GPS location to ensure the student is present at the correct place.

---

## 📍 GPS Location Feature

- Uses the device’s **Geolocation API**
- Captures latitude and longitude during form submission
- Helps prevent fake or proxy attendance
- Ensures students are physically present in the classroom

---

## 📂 Project Structure
