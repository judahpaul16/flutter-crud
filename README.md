# 📱 Flutter Firebase CRUD App

Simple app to demonstrate CRUD operations using Flutter and Firebase.

## 🚀 Quick Start

1. **Clone** this repo.
2. **Install** dependencies:
```
flutter pub get
```
3. **Run** the app:
```
flutter run
```

## 🔧 Setup

- **Firebase**: Set up your Firebase project and download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) files. Since `firebase_options.dart` is ignored (check `.gitignore`), generate it using the Firebase CLI or manually input your Firebase project configuration.

## 🛠️ Features

- **Create**: Add new records.
- **Read**: Fetch and display records.
- **Update**: Modify existing records.
- **Delete**: Remove records.

## 🗂️ Important Files

- `lib/main.dart`: Entry point of the app.
- `.gitignore`: Includes `firebase_options.dart` to avoid exposing Firebase credentials.

## 📝 Note

Ensure you have configured your Firebase project correctly and added your app's Android/iOS configurations as mentioned in the Firebase setup guide.

## 📄 License

MIT License. See `LICENSE` file for details.
