# WhatsApp Clone

Full Stack Whatsapp Clone with Flutter, Firebase & Riverpod!

## Features
- Phone Number Authentication
- 1-1 Chatting with Contacts Only
- Group Chatting
- Text, Image, GIF, Audio(Recording), Video & Emoji Sharing
- Status Visible to Contacts Only and Disappears after 24 hours
- Video Calling
- Online/Offline Status
- Seen Message
- Replying to Messages
- Auto Scroll on New Messages

## Installation
After cloning this repository, migrate to ```Whatsapp-Clone``` folder. Then, follow the following steps:
- Create Firebase Project
- Run the commands:
  - npm install -g firebase-tools
  - dart pub global activate flutterfire_cli
  - flutterfire configure
- Enable Authentication
- Add Firestore & Storage Rules
- Create Android & iOS Apps

Then run the following commands to run your app:
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator)
  flutter run
```

## Tech Used
**Server**: Firebase Auth, Firebase Storage, Firebase Firestore

**Client**: Flutter, Riverpod
    

