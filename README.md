📱 TruecallerLite – Rachit Sapkota Edition

A lightweight caller identification app inspired by Truecaller.
Built with Kotlin (Jetpack Compose) and a Node.js + PostgreSQL backend, localized for Nepal.

✨ Features

🔎 Caller Identification – Lookup numbers with spam/safe scoring.

🎨 Custom Branding – Splash screen + overlay popup: Developed by Rachit Sapkota.

🌍 Nepal Defaults – Country code +977, A.D./B.S. date toggle.

📂 Backend API – Express.js + PostgreSQL with search & spam-report endpoints.

🛡 Privacy-first – Minimal data usage, user-controlled number reporting.

📂 Project Structure
TruecallerLite/
│── android/       # Android app (Kotlin, Jetpack Compose UI)
│── backend/       # Node.js + Express + PostgreSQL API
│── docs/          # Documentation & API references

🚀 Getting Started
Android App

Open android/ in Android Studio.

Run:

./gradlew assembleDebug


Install the generated APK:

app/build/outputs/apk/debug/app-debug.apk

Backend

Navigate to backend/.

Install dependencies:

npm install


Start server:

npm run dev

🛠 Tech Stack

Android: Kotlin, Jetpack Compose, Retrofit

Backend: Node.js, Express.js, PostgreSQL

Database: PostgreSQL with Sequelize ORM

🌏 Localization

Default country: Nepal (+977)

Date formats: A.D. & B.S. toggle

👨‍💻 Author

Developed & Designed by Rachit Sapkota
