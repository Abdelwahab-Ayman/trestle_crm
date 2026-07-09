<img src="https://github.com/Abdelwahab-Ayman/trestle_crm/blob/main/img/logo%2005%20favicon.png" alt="trestle"></img>

### Trestle CRM
A cross-platform Customer Relationship Management (CRM) app built with Flutter, delivering a native look and feel across mobile, web, and desktop from a single codebase.
#### Features

- 📇 Contact and lead management
- 📊 Sales pipeline tracking
- 🔔 Task and follow-up reminders
- 📈 Deal and revenue overview
- 🌐 Cross-platform: Android, iOS, Web, Windows, macOS, Linux
#### Tech Stack
- **Framework:** Flutter
- **Language:** Dart
- **State Management:** _TBD (e.g. Provider / Riverpod / Bloc)_
- **Backend:** _TBD (e.g. Firebase / REST API)_

### Getting Started

#### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (stable channel)
- Dart SDK (bundled with Flutter)
- Android Studio / Xcode (for mobile builds)

#### Installation

```bash
git clone https://github.com/<your-username>/trestle_crm.git
cd trestle_crm
flutter pub get
```
#### Running the app

```bash
flutter run
```
To target a specific platform:

```bash
flutter run -d chrome     # Web
flutter run -d windows    # Windows
flutter run -d macos      # macOS
flutter run -d linux      # Linux
```

#### Project Structure
```
trestle_crm/
├── lib/
│   ├── main.dart
│   ├── models/
│   ├── screens/
│   ├── widgets/
│   └── services/
├── assets/
├── test/
└── pubspec.yaml
```
