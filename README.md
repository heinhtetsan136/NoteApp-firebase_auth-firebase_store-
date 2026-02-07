# NoteApp with Firebase Auth & Firestore (BLoC Pattern)

A cross-platform note-taking app built with Flutter (Dart) that uses Firebase Authentication for user login and Firestore for storing notes, structured with the BLoC (Business Logic Component) pattern.

## Features

- **User Authentication**
  - Login & registration via Firebase Auth (email & password)
  - Logout
- **Firestore Integration**
  - Cloud Firestore for creating, reading, updating, and deleting (CRUD) notes
  - Real-time updates of notes
- **Notes Management**
  - Add, edit, and delete notes
  - List all notes for the authenticated user
- **State Management**
  - Uses the [BLoC](https://bloclibrary.dev/#/) pattern for UI and logic separation
- **Cross-Platform**
  - Runs on Android, iOS, and Web
- **Other Tech**
  - Dart, C++, Swift, CMake (for platform integrations)
  - Responsive design

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Firebase Project & Configuration](https://firebase.google.com/docs/flutter/setup)
- Dart enabled in your environment

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/heinhtetsan136/NoteApp-firebase_auth-firebase_store-.git
   cd NoteApp-firebase_auth-firebase_store-
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Follow the official [Firebase Flutter Setup Guide](https://firebase.flutter.dev/docs/overview/) to add your Google Services files and web keys.

4. **Run the app**
   ```bash
   flutter run
   ```

## Project Structure

```
lib/


