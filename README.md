# DatingApp

A modern dating application built with Android and Firebase.

## Project Overview

DatingApp is a beginner-friendly dating platform featuring:
- User authentication and profile management
- Profile discovery with swipe/like functionality
- Real-time messaging
- User matching algorithm
- Push notifications

## Tech Stack

- **Frontend:** Android (Kotlin)
- **Backend:** Firebase (Firestore, Authentication, Storage)
- **Real-time Chat:** Firebase Realtime Database
- **IDE:** Android Studio

## Project Structure

```
DatingApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/smarty/datingapp/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
├── gradle/
├── build.gradle
├── settings.gradle
└── README.md
```

## Features (Planned)

### Phase 1: Core Setup
- [ ] Firebase project setup
- [ ] User authentication (Email/Phone)
- [ ] Basic profile creation
- [ ] User database schema

### Phase 2: Discovery
- [ ] Profile cards with swipe functionality
- [ ] Like/Dislike/Super Like system
- [ ] Matching algorithm
- [ ] Profile filters (age, location, interests)

### Phase 3: Messaging
- [ ] Real-time chat interface
- [ ] Message notifications
- [ ] Chat history

### Phase 4: Polish
- [ ] Push notifications
- [ ] Image optimization
- [ ] User safety features
- [ ] Profile verification

## Getting Started

### Prerequisites
- Android Studio (latest version)
- Firebase account
- Minimum API Level 21 (Android 5.0)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Smarty2531/Smarty-.git
   cd Smarty-
   ```

2. Open in Android Studio
   - File → Open → Select project folder

3. Configure Firebase
   - Create Firebase project at https://console.firebase.google.com
   - Download `google-services.json`
   - Place in `app/` directory

4. Build and Run
   - Click "Run" or press Shift + F10

## Dependencies

```gradle
// Firebase
implementation 'com.google.firebase:firebase-auth:21.3.0'
implementation 'com.google.firebase:firebase-firestore:24.8.1'
implementation 'com.google.firebase:firebase-storage:20.2.1'
implementation 'com.google.firebase:firebase-messaging:23.2.1'

// UI Libraries
implementation 'androidx.appcompat:appcompat:1.6.1'
implementation 'com.google.android.material:material:1.9.0'
implementation 'androidx.constraintlayout:constraintlayout:2.1.4'

// Networking
implementation 'com.squareup.okhttp3:okhttp:4.11.0'
implementation 'com.squareup.retrofit2:retrofit:2.9.0'

// Image Loading
implementation 'com.github.bumptech.glide:glide:4.15.1'
```

## File Structure Explanation

- **Models:** User, Profile, Message, Match classes
- **Activities:** MainActivity, LoginActivity, ProfileActivity, ChatActivity
- **Fragments:** DiscoveryFragment, ChatListFragment, ProfileFragment
- **Adapters:** UserProfileAdapter, MessageAdapter
- **Utilities:** FirebaseUtil, ImageUtil, ValidationUtil
- **Services:** NotificationService, MatchingService

## Contributing

This is a learning project. Feel free to experiment and improve!

## License

MIT License - See LICENSE file for details

## Contact

Created by [@Smarty2531](https://github.com/Smarty2531)
