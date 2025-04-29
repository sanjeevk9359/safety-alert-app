# Safety Alert App 🚨

A mobile application that allows users to quickly report harassment, stalking, or assault incidents by capturing an offender's photo and current location. Reports are securely sent to authorities and saved for personal record.

---

## 📱 Features

- 📸 Capture offender's photo instantly.
- 📍 Send exact GPS location with the photo.
- ☁️ Upload report directly to cloud (Firebase).
- 📊 Admin dashboard to view all reports.
- 🔒 Secure login using phone number (OTP-based).
- 🌐 Supports Hindi and English languages.
- ⚡ One-tap emergency report system.
- 🧠 Face detection and time/location stamping (future update planned).

---

## 🛠 Technology Stack

- Flutter 3.x
- Firebase Authentication (Phone OTP Login)
- Firebase Firestore (Store reports)
- Firebase Storage (Store captured images)
- Geolocator Plugin (Get GPS coordinates)
- Image Picker Plugin (Camera access)

---

## 🔥 How It Works

1. User logs in using their mobile number.
2. User clicks **Report Emergency** button.
3. App opens the camera → Captures a photo.
4. App auto-gets GPS location.
5. App uploads the report (photo + location) to Firestore and Storage.
6. Admin can view all reports through the dashboard.

---

## 🎨 UI & Branding

- Red-themed design (alert-focused).
- Modern clean interface.
- "Made by Sanjeev Kumar" proudly shown inside the app.

---

## 🚀 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/sanjeevk9359/safety-alert-app.git
   cd safety-alert-app
