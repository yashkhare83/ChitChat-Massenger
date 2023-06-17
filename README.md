# ChitChat-Massenger(In-Progress)

# Flutter Firebase Chat App

This is a chat application built with Flutter and Firebase, allowing users to send and receive messages in real-time.

## Features

- User authentication: Users can sign up and log in using their email and password.
- Real-time messaging: Users can send and receive messages in real-time.
- User presence: Users' online/offline status is displayed in the app.
- User profiles: Users can update their profile information, including profile picture and display name.
- Push notifications: Users receive push notifications for new messages when the app is in the background.

## Screenshots

Include a few screenshots of your app to showcase its appearance.

## Prerequisites

- Flutter SDK: [Installation Guide](https://flutter.dev/docs/get-started/install)
- Firebase project: Create a new project on the [Firebase Console](https://console.firebase.google.com) and enable Firebase Authentication and Cloud Firestore.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yashkhare83/ChitChat-Massenger
   ```

2. Navigate to the project directory:

   ```bash
   cd chat
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Update Firebase configuration:

   - Android:
     - Download the `google-services.json` file from the Firebase Console.
     - Place the file in the `android/app` directory of your project.

   - iOS:
     - Download the `GoogleService-Info.plist` file from the Firebase Console.
     - Place the file in the `ios/Runner` directory of your project.

5. Run the app:

   ```bash
   flutter run
   ```

## Configuration

Update the Firebase configuration in the `lib/services/firebase_service.dart` file with your Firebase project credentials:

```dart
const firebaseConfig = {
  'apiKey': 'YOUR_API_KEY',
  'authDomain': 'YOUR_AUTH_DOMAIN',
  'projectId': 'YOUR_PROJECT_ID',
  // Add other Firebase configuration properties here
};
```

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

```

Make sure to replace "your-username" and "your-repository" with your GitHub username and repository name, respectively. Also, remember to provide the appropriate Firebase configuration details in the `lib/services/firebase_service.dart` file.

Feel free to customize this README file to fit your specific project requirements and add any additional sections or information that you think would be helpful.
