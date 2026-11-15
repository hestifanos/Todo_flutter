# Smart To-Do

A Flutter task planner for creating tasks with a title, deadline, and description. The current implementation keeps tasks in memory for the active app session.

## Features

- Add tasks with deadlines and descriptions.
- View tasks in a styled Material 3 interface.
- Use Poppins typography and a bundled background image.

## Requirements

- Flutter SDK with Dart SDK `^3.9.2`
- Android Studio, Xcode, or a supported Flutter desktop/web target

## Run and test

```bash
flutter pub get
flutter test
flutter run
```

Tasks are not persisted between app restarts yet. The main UI and task model currently live in `lib/main.dart`; the bundled image is in `asset/`.
