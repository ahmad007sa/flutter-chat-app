# 💬 Flutter Chat App

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![Dart](https://img.shields.io/badge/Dart-Language-blue?logo=dart)
![License](https://img.shields.io/badge/License-MIT-green)

A modern **real-time chat application** built using **Flutter** and **Firebase**.
This project demonstrates how to build scalable mobile applications with authentication, cloud storage, push notifications, and real-time messaging.

---

# 🚀 Features

✨ Key features of the application:

* 🔐 **User Authentication**

  * Sign up and login using Firebase Authentication
  * Email & password validation

* 👤 **User Profiles**

  * Upload profile images during registration
  * Images stored in Firebase Storage

* 💬 **Real-Time Chat**

  * Messages stored in Cloud Firestore
  * Live updates using Firestore streams

* 🧑‍🤝‍🧑 **User Identification**

  * Messages display username and profile image

* 📱 **Push Notifications**

  * Firebase Cloud Messaging support

* 🎨 **Modern Chat UI**

  * Chat bubbles
  * Avatar display
  * Clean and simple interface

---

# 📱 Screenshots

### Signup Screen

![Signup](screenshots/signup_screen.png)

### Login Screen

![Login](screenshots/login_screen.png)

### Chat Screen

![Chat](screenshots/chat_screen.png)

### Form Validation

![Validation](screenshots/signup_validation.png)

---

# 🏗 Architecture

The application architecture is based on Flutter UI connected with Firebase services:

```
Flutter UI
    │
    ▼
Firebase Authentication
    │
    ▼
Cloud Firestore (Real-time chat)
    │
    ▼
Firebase Storage (Profile images)
    │
    ▼
Firebase Cloud Messaging
```

---

# 🛠 Tech Stack

| Technology              | Usage                       |
| ----------------------- | --------------------------- |
| Flutter                 | Cross-platform UI framework |
| Dart                    | Programming language        |
| Firebase Authentication | User login/signup           |
| Cloud Firestore         | Real-time database          |
| Firebase Storage        | Profile image storage       |
| Firebase Messaging      | Push notifications          |

---

# 📦 Packages Used

```
firebase_core
firebase_auth
cloud_firestore
firebase_storage
firebase_messaging
image_picker
```

---

# ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/ahmad007sa/flutter-chat-app.git
```

### 2️⃣ Navigate into the project

```
cd flutter-chat-app
```

### 3️⃣ Install dependencies

```
flutter pub get
```

### 4️⃣ Configure Firebase

Add your Firebase configuration file:

```
android/app/google-services.json
```

---

### 5️⃣ Run the application

```
flutter run
```

---

# 📊 Application Flow

1️⃣ User creates an account
2️⃣ Profile image uploaded to Firebase Storage
3️⃣ User information stored in Firestore
4️⃣ Messages stored in Firestore
5️⃣ Messages streamed instantly to all users

---

# 🎯 What I Learned

Through this project I learned:

* Building **real-time applications using Flutter**
* Integrating **Firebase Authentication**
* Using **Cloud Firestore streams**
* Uploading images with **Firebase Storage**
* Implementing **push notifications**
* Structuring scalable Flutter projects

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Add feature"
```

4. Push the branch

```
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

Developed by **Ahmad** as a Flutter learning project.

---

# ⭐ Support

If you like this project, consider giving it a **⭐ on GitHub**.

---

# 📄 License

This project is licensed under the MIT License.
