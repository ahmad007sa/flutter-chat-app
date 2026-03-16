# 💬 Flutter Chat App

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![Dart](https://img.shields.io/badge/Dart-Language-blue?logo=dart)
![License](https://img.shields.io/badge/License-MIT-green)

A **modern real-time chat application** built with **Flutter** and **Firebase** that demonstrates how to build scalable mobile apps with authentication, cloud storage, push notifications, and real-time messaging.

---

# 🚀 Features

✨ Core functionality of the application:

* 🔐 **User Authentication**

    * Sign up & login using Firebase Authentication
    * Secure email/password authentication

* 👤 **User Profiles**

    * Upload profile images during registration
    * Images stored using Firebase Storage

* 💬 **Real-Time Messaging**

    * Messages stored in Cloud Firestore
    * Instant updates using Firestore streams

* 🧑‍🤝‍🧑 **User Identification**

    * Each message displays username and profile image

* 📱 **Push Notifications**

    * Firebase Cloud Messaging integration
    * Users automatically subscribe to chat topic

* ⚡ **Live Updates**

    * Real-time UI updates with StreamBuilder

* 🎨 **Modern Chat UI**

    * Chat bubbles
    * Avatar support
    * Grouped messages

---

# 📱 Screenshots

*(Add screenshots of your app here)*

Example:

```
screenshots/
 ├── login.png
 ├── signup.png
 ├── chat.png
```

Then add them like this:

```
![Login Screen](screenshots/login.png)
![Chat Screen](screenshots/chat.png)
```

---

# 🏗 Architecture

The app follows a simple and scalable architecture:

```
Flutter UI
    │
    ▼
Firebase Authentication
    │
    ▼
Cloud Firestore (Real-time messages)
    │
    ▼
Firebase Storage (User images)
    │
    ▼
Firebase Cloud Messaging (Notifications)
```

---

# 📂 Project Structure

```
lib/
 ├── screens/
 │   ├── auth.dart
 │   ├── chat.dart
 │   └── splash.dart
 │
 ├── widgets/
 │   ├── chat_messages.dart
 │   ├── message_bubble.dart
 │   ├── new_message.dart
 │   └── user_image_picker.dart
 │
 └── main.dart
```

---

# 🛠 Tech Stack

| Technology         | Purpose                     |
| ------------------ | --------------------------- |
| Flutter            | Cross-platform UI framework |
| Dart               | Programming language        |
| Firebase Auth      | User authentication         |
| Cloud Firestore    | Real-time database          |
| Firebase Storage   | Image storage               |
| Firebase Messaging | Push notifications          |

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

Add the Firebase configuration file:

```
android/app/google-services.json
```

---

### 5️⃣ Run the app

```
flutter run
```

---

# 📊 Application Flow

1️⃣ User creates an account
2️⃣ Profile image uploaded to Firebase Storage
3️⃣ User data stored in Firestore
4️⃣ Messages stored in Firestore
5️⃣ Messages streamed to all connected users

---

# 🎯 Learning Goals

This project demonstrates how to:

* Build **real-time chat applications**
* Use **Firebase with Flutter**
* Implement **authentication flows**
* Handle **image uploads**
* Build **reactive UI using streams**

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve the project:

1. Fork the repository
2. Create a new branch

```
git checkout -b feature-name
```

3. Commit your changes

```
git commit -m "Add feature"
```

4. Push to the branch

```
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

Developed by **Ahmad** as a Flutter learning project.

---

# ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub!

---

# 📄 License

This project is licensed under the MIT License.
