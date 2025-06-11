# 📋 ToDo List App with Flutter and Firebase

This is a simple ToDo List application built using **Flutter** and **Firebase Firestore**. It allows users to register, log in, and manage their daily tasks efficiently. Each task can have a title, description, and due date.

---

## 🚀 Features

- 🔐 Firebase Authentication (register & login)
- 📝 Add task with title, description, and date
- 📆 Tasks organized by selected date
- ☁️ Realtime Firestore database sync
- 💻 Works on Android emulator or real device

---

## 📸 Screenshots

> *(Add screenshots of your app interface here to showcase main features)*

---

## 🛠️ Tech Stack

- Flutter
- Dart
- Firebase Authentication
- Firebase Cloud Firestore
- Android Studio / VSCode

---

## 📦 Installation

### 1. Clone the Repository

git clone https://github.com/yourusername/flutter-todolist.git
cd flutter-todolist
##2. Install Flutter Dependencies

bash
Salin
Edit
flutter pub get

##3. Firebase Setup

Go to Firebase Console

Create a Firebase project (if you don’t have one)

Add an Android app in Firebase project settings

Download google-services.json

Place it inside your Flutter project at:

bash
Salin
Edit
android/app/google-services.json

##4. Configure Gradle for Firebase

In android/build.gradle:

gradle
Salin
Edit
classpath 'com.google.gms:google-services:4.3.15'
In android/app/build.gradle:

gradle
Salin
Edit
apply plugin: 'com.google.gms.google-services'

##▶️ Run the App
Make sure you have an emulator running or a physical device connected:

bash
Salin
Edit
flutter run

##📂 Folder Structure
css
Salin
Edit
lib/
│
├── main.dart
├── pages/
│   ├── home_page.dart
│   └── login_page.dart
├── widgets/
│   └── task_input_form.dart
##✅ Future Improvements
 Edit and delete tasks

 Task completion toggle

 Dark mode theme

 Push notifications

##👨‍💻 Author
Made with  by Erzet

##📄 License
This project is licensed under the MIT License.







