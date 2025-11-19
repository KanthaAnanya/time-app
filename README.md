⏱️ Time App
Digital Clock | Timer | Stopwatch

A simple, responsive, and interactive time utility web application built using HTML, CSS, and JavaScript.
The app provides three core time functions:

 Digital Clock
 Stopwatch (Start / Stop / Reset / Lap Recording)
 Countdown Timer

This project is also packaged as a mobile Android app using Capacitor and Android Studio.

 Features
🕒 Digital Clock

Live real-time hours, minutes, seconds

12-hour or 24-hour mode (depending on system)

⏱️ Stopwatch

Start / Stop / Reset functionality

Lap recording

Millisecond precision

⏲️ Countdown Timer

Custom time input (minutes & seconds)

Start / Pause / Reset

Alerts when countdown ends

📱 Android App Version

Built using Capacitor

Packaged and exported as an Android APK

Works offline

Clean UI optimized for mobile

🛠️ Technologies Used

HTML5

CSS3

JavaScript (ES6)

Capacitor.js (for Android app packaging)

Android Studio (APK build)
📁 Project Structure
time-app/
│── www/
│    └── index.html
│
│── android/                # Android project files (auto-generated)
│── capacitor.config.json   # Capacitor settings
│── package.json
│── package-lock.json

📦 Installation & Run (Web Version)
1. Clone repository
git clone https://github.com/KanthaAnanya/time-app.git
cd time-app

2. Open the web app

Just open:

www/index.html


The clock/timer/stopwatch will run directly in your browser.

📱 Build Android APK
1. Install dependencies
npm install

2. Copy web assets
npx cap copy

3. Open Android Studio
npx cap open android

4. Build APK

In Android Studio:
Build → Build APK(s)

APK will appear in:

android/app/build/outputs/apk/debug/app-debug.apk
